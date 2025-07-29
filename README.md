# 🛠️ Arduino Auto Driving Robot

This is an Arduino-based self-driving robot project that includes basic driving logic, line tracing, obstacle avoidance, and AI-based decision making using simple machine learning logic.

## 📂 Project Structure

-----

## 📂 Project Structure

Here's the project structure for your AutoDrivingRobot, formatted for a GitHub README:

```
AutoDrivingRobot/
├── autoDrivingRobot_init.ino           # Initialization and basic drive logic
├── AutoDriveRobot_LineTrace.ino        # Line tracing functionality
├── AutoDriveRobot_ObstacleDetect.ino   # Ultrasonic obstacle detection driving
├── obstacle.ino                        # Obstacle detection test
├── AutoDrivingRobot_AI.ino             # AI-based driving logic
├── BP_MachineLearning.zip              # Backpropagation-based machine learning script
└── Arduino IDE.lnk                     # Shortcut to Arduino IDE
```

---

## 🚗 Features

### 🔧 1. `autoDrivingRobot_init.ino`
- Sets up pin configurations and initializes motors
- Includes basic drive functions

### 🟡 2. `AutoDriveRobot_LineTrace.ino`
- Uses IR sensors for line tracing
- Implements simple threshold-based logic (no PID)

### 🚧 3. `AutoDriveRobot_ObstacleDetect.ino`
- Uses ultrasonic sensor (HC-SR04) for obstacle detection
- Stops or avoids when obstacle is within a certain distance

### 🤖 4. `AutoDrivingRobot_AI.ino`
- Implements simple AI decision-making logic
- Can integrate basic trained data to decide movement

### 🧠 5. `BP_MachineLearning.zip`
- Python scripts implementing a simple backpropagation neural network
- Can be used to train model on driving decisions based on sensor input

### 🧪 6. `obstacle.ino`
- Simplified test script for obstacle detection

---

# 🔌 Hardware Components

This project utilizes the following hardware components:

| Component | Image | Description |
|---|---|---|
| **Arduino Uno** | <img width="250" alt="Arduino Uno" src="https://github.com/user-attachments/assets/79ac66c8-53ee-4aa3-aee3-e0bf4d8c516c"> | The central microcontroller for processing sensor data and controlling actuators. |
| **Ultrasonic Sensor (HC-SR04)** | <img width="250" alt="Ultrasonic Sensor (HC-SR04)" src="https://github.com/user-attachments/assets/ca69fb8e-2dfb-4540-8233-05e256d0059d"> | Used for measuring distances and obstacle detection. |
| **IR Line Sensors** | <img width="250" alt="IR Line Sensors" src="https://github.com/user-attachments/assets/635e110a-a274-460e-87ba-953a050c160c"> | Essential for line following and edge detection. |
| **Servo Motor** | <img width="250" alt="image" src="https://github.com/user-attachments/assets/cfe1479a-6a14-4050-a973-9a1fb4513cf6" >| A precision motor used for controlling rotational position, often for steering or sensor positioning. |
| **Battery Pack** | <img width="250" alt="image" src="https://github.com/user-attachments/assets/cc853cde-f2b2-47bf-8b03-a802ab23f4ce">| Supplies power to all the electronic components. |


---
## 📦 How to Use

1. **Install Arduino IDE**
   - Download from [official website](https://www.arduino.cc/en/software)

2. **Open .ino File**
   - Choose the `.ino` file depending on the feature you want to test (e.g. AI, Line Trace, etc.)

3. **Board and Port Setup**
   - Board: Arduino Uno
   - Port: Select correct USB COM port

4. **Install Required Libraries**
   - e.g., Servo.h, NewPing.h (if applicable)

5. **Upload and Run**
   - Connect your robot to the PC and upload the sketch

---

## 🧠 AI & Machine Learning

- The included `BP_MachineLearning.zip` implements a simple backpropagation algorithm.
- Training is typically done on PC, and the inference can be either transmitted to Arduino or translated into simpler logic.

---

## ✍️ Author

- **JuHyeong Kim** – Embedded Developer (Vision/Sensors)

---

## 📜 License

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it.

---

