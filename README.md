# Robot-Arm-Movement-Prediction-using-Machine-Learning
This project simulates a robotic arm and collects its joint state data during motion. A machine learning model is then trained to predict the next movement of the arm based on previous joint states — showcasing a fusion of robotics and AI.

# Project Goals

- Simulate a robotic arm in a 3D environment
- Collect time-series data of joint angles and velocities
- Train an ML model to predict the next joint state
- Visualize model performance and compare predictions

#  Tools & Technologies

| Tool            | Purpose                             |
|----------------|-------------------------------------|
| Python          | Core programming language           |
| PyBullet        | Robotic simulation environment      |
| NumPy/Pandas    | Data handling and processing        |
| Matplotlib/Seaborn | Data visualization               |
| Scikit-learn / PyTorch | Machine learning models      | 


# Project Structure

robot-arm-ml-prediction/ │ 
                          ├── data/ # Logged simulation data (CSV) 
                            ├── models/ # Trained ML models
                               ├── src/ # Core Python scripts │ 
                                 ├── simulator.py # Robot arm simulation & control │ 
                                   ├── data_logger.py # Logging joint states │ 
                                      ├── preprocess.py # Data cleaning & prep │  
                                        ├── train_model.py # ML training script │ └── predict.py # Predict and visualize 


# Machine Learning Pipeline

1. **Simulation**: Control robot arm to follow motion trajectories.
2. **Data Logging**: Record joint angles, velocities, timestamps.
3. **Preprocessing**: Format data for supervised learning.
4. **Model Training**: Train model to predict next joint state.
5. **Evaluation**: Compare predicted vs actual movement

#  Sample Result
Random generated data [file:///home/mohammed-kumail-abbas/Pictures/Screenshots/Screenshot%20from%202025-05-01%2015-57-34.png]
trainning the data[file:///home/mohammed-kumail-abbas/Pictures/Screenshots/Screenshot%20from%202025-05-01%2015-59-08.png]
file:///home/mohammed-kumail-abbas/Pictures/Screenshots/Screenshot%20from%202025-05-01%2016-00-27.png

[robot_arm_predictions](https://github.com/user-attachments/assets/07988a36-fa31-4cfe-911b-34fb0598ca2a)
  
> Example: Predicted vs Actual joint angle over time.
