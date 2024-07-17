# Traffic Management System

This is a Python-based application for predicting and managing traffic volume using machine learning models and real-time incident reporting. It provides a graphical user interface (GUI) for traffic prediction, visualization, and incident reporting.

![Traffic Management System](traffic_management_system.png)

## Features

- **Traffic Prediction**: Predicts traffic volume based on weather conditions and time of day using machine learning models (Linear Regression and Random Forest).
- **Graphical Visualization**: Displays historical and predicted traffic volumes on a graphical interface for easy analysis.
- **Traffic Light Control Simulation**: Simulates a changing traffic light based on predefined traffic conditions.
- **Incident Reporting**: Allows users to report traffic incidents with location and description inputs.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/EkeminiThompson/traffic-management-system.git
   cd traffic-management-system
   ```

2. **Install dependencies**:

   Ensure you have Python 3 installed. Install the required Python packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**:

   Execute the main Python script to launch the application:

   ```bash
   python traffic_management_app.py
   ```

## Usage

- **Traffic Prediction**:
  - Select a location, enter a date in YYYY-MM-DD format, and choose a machine learning model (Linear Regression or Random Forest).
  - Click on "Predict Traffic" to see the predicted traffic volume for the selected date and location.
  - The graph updates to display historical traffic data, the prediction date, and the predicted traffic volume.

- **Graph Display**:
  - The graph shows historical traffic volumes as blue dots connected by lines.
  - The red dashed line indicates the prediction date.
  - The green dot represents the predicted traffic volume.

- **Traffic Light Control**:
  - The application simulates a traffic light that changes color (red, yellow, green) every 5 seconds based on predefined conditions.

- **Incident Reporting**:
  - Users can report traffic incidents by entering the location and description of the incident.
  - Click on "Report Incident" to submit the incident report.

## Development

- **Models**: The application uses two machine learning models for traffic prediction: Linear Regression and Random Forest.
- **GUI**: Built using Tkinter for the graphical user interface and Matplotlib for plotting graphs.
- **Data Mocking**: Mock data is used for demonstration purposes, including weather conditions and historical traffic data.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the need for effective traffic management systems in urban areas.
- Built as a demonstration of integrating machine learning with real-time data visualization.

