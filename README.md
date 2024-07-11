# User Activity Detection Based on Sensor Data

## Introduction
This project aims to detect user movement, phone direction, and distinguish between walking and static states using sensor data from a smartphone. Due to the lack of a real dataset, a random dataset was generated with columns for gyroscope, accelerometer, and magnetometer readings. A `determine_activity` function was written to calculate user behavior based on this data. Additionally, a target section was created in the dataset to facilitate the use of machine learning models for training and classification.

## Getting Started

### Prerequisites
Ensure you have the following libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Action-And-Direction-Detection.git
    ```
2. Navigate to the project directory:
    ```bash
    cd IndoorNavigation_ActionAndDirection
    ```
3. Open the Jupyter Notebook `IndoorNavigation_ActionAndDirection.ipynb` in your preferred environment.

## Running the Project

### Running Locally
1. Ensure all required libraries are installed.
2. Open and run all cells in the Jupyter Notebook to execute the code, generate the dataset, and analyze user activity.

### Running on Google Colab
1. Open the provided Google Colab link in the main code (7th row in `IndoorNavigation_ActionAndDirection.py` project directory).
2. Run all cells to see the visualizations and evaluations.


## Libraries and Functions Used

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical computations.

## Project Steps and Outputs

### Data Generation
Generated a random dataset with columns:
- Gyroscope X (rad/s)
- Gyroscope Y (rad/s)
- Gyroscope Z (rad/s)
- Accelerometer X (m/s²)
- Accelerometer Y (m/s²)
- Accelerometer Z (m/s²)
- Magnetometer X (μT)
- Magnetometer Y (μT)
- Magnetometer Z (μT)
- Activity (target column)


## Libraries and Functions Used

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical computations.

## Project Steps and Outputs

### Data Generation
Generated a random dataset with columns:
- Gyroscope X (rad/s)
- Gyroscope Y (rad/s)
- Gyroscope Z (rad/s)
- Accelerometer X (m/s²)
- Accelerometer Y (m/s²)
- Accelerometer Z (m/s²)
- Magnetometer X (μT)
- Magnetometer Y (μT)
- Magnetometer Z (μT)
- Activity (target column)

### Activity Detection
Implemented the `determine_activity` function to calculate user behavior based on sensor data. The function distinguishes between walking and static states and interprets phone direction.

### Example Output

1. **User Activity Detection**
   - The `determine_activity` function processes the sensor data to detect whether the user is walking or static and determines the phone's direction.

## Conclusion
The project demonstrates effective data generation and activity detection techniques. While machine learning models were not used in this project, the structured dataset facilitates their future use for training and classification, providing valuable insights into user behavior based on sensor data.
