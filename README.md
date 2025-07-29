# 🛠️ Arduino Auto Driving Robot

This is an Arduino-based self-driving robot project that includes basic driving logic, line tracing, obstacle avoidance, and AI-based decision making using simple machine learning logic.

## 📂 Project Structure

AutoDrivingRobot/
├── autoDrivingRobot_init.ino # Initialization and basic drive logic
├── AutoDriveRobot_LineTrace.ino # Line tracing functionality
├── AutoDriveRobot_ObstacleDetect.ino # Ultrasonic obstacle detection driving
├── obstacle.ino # Obstacle detection test
├── AutoDrivingRobot_AI.ino # AI-based driving logic
├── BP_MachineLearning.zip # Backpropagation-based machine learning script
└── Arduino IDE.lnk # Shortcut to Arduino IDE


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

## 🔌 Hardware Components

- Arduino Uno
- Ultrasonic Sensor (HC-SR04)
- IR Line Sensors
- Servo Motor
- L298N Motor Driver
- 2x DC Motors
- Battery Pack
- (Optional) Bluetooth Module or LCD

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

- **Juhyung Kim** – Project planning, implementation, and code design

---

## 📜 License

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it.

---

