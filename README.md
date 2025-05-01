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
Random generated data ![Screenshot from 2025-05-01 15-57-34](https://github.com/user-attachments/assets/a0192450-6b66-48aa-a1ac-3f980bc51165)

trainning the data ![Screenshot from 2025-05-01 15-59-08](https://github.com/user-attachments/assets/9ab15546-e861-461a-b00b-0d56993dbae5) ![Screenshot from 2025-05-01 15-59-08](https://github.com/user-attachments/assets/06b480e2-05a0-415e-a47e-7a193446ed5b)
[robot_arm_predictions] ![robot_arm_predictions](https://github.com/user-attachments/assets/a4fb8007-a844-4342-a22c-a90509b235f0)
 
> Example: Predicted vs Actual joint angle over time.
