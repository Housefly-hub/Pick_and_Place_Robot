# 🤖 Pick and Place Robot using Micro-Electromagnet Gripper

This is an Arduino-based Pick and Place robot that uses a micro-electromagnet as a gripper to pick up small metal cubes and place them in a looped sequence. The robot combines servo and stepper motors to perform automated pick-and-place operations.

---

## 🎯 Objective

Design and implement a robotic arm capable of picking up small metallic objects using a micro-electromagnet and placing them at predefined locations in a loop using Arduino control.

---

## 🧰 Components Used

### 🔌 Electronic Components
- Arduino UNO  
- LM2596 DC to DC Buck Converter  
- A4988 Stepper Motor Driver  
- 60Kg RDS5160 Servo Motor  
- 42HD4045-02 Stepper Motor  
- 12V Micro-Electromagnet  
- 1N5399 Schottky Diode  
- 2N222A NPN Transistor  
- 1k and 25Ω Resistors  
- Limit Switch  
- 12V 5A SMPS  
- 45µF Capacitor  
- Jumper Wires  
- 6-Pin JST PH Connector  

### ⚙️ Mechanical Components
- M8 Lead Screw (x3)  
- Flexible Shaft Connector  
- M6 20mm Head Screw (x18)  
- M3 20mm Countersink Screw (x4)  
- M8 Hex Nut (x8)  
- M2 20mm Lead Screw (x5)  
- M2 10mm Lead Screw (x2)  
- Slider Bearing (inner D: 8mm)  
- 3D Printed Parts  
- PVC Pipe  

---

## 🧠 How It Works

- The **servo motor** rotates the robot arm to specific angles.
- The **stepper motor** moves the arm vertically to pick or place an object.
- The **micro-electromagnet** acts as a gripper to lift and release metal cubes.
- A **limit switch** is used for homing the vertical axis.
- The robot starts on button press and executes a predefined loop of pick-and-place steps.

---

## 💻 Arduino Code

The main Arduino sketch is in `PickandPlace_Robot.cpp`. It includes:
- `EndEffector` class to manage electromagnet control.
- Smooth servo rotation through gradual positioning.
- Homing and referencing of the vertical axis.
- A loop that controls multiple pick and place movements.

---

## ▶️ Usage

1. Assemble the mechanical frame and wiring.
2. Change the extension of the sketch from `.cpp` to `.ino`
3. Upload `PickandPlace_Robot.ino` to the Arduino UNO.
4. Power the circuit using a 12V 5A SMPS.
5. Press the button to start the loop.
6. The robot will automatically run through the predefined pick and place routine.

---

## 👤 Author

**Deepak Yadav**  
Robotics and Automation Engineering Student

---

## 📄 License

This project is provided for **educational and demonstrative purposes only**.  
It is **not licensed for commercial use or redistribution**.  
Please contact the author for permissions or inquiries.

