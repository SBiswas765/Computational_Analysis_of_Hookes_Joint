# 🔩 Computational Analysis of Hookes Joint

A Python tool to **analyze and visualize the kinematics** of a Hooke's Universal Joint. It calculates critical parameters like shaft speeds, angular acceleration, and angles (θ₁–θ₄), then generates both a **polar velocity diagram** and a **real-time simulation** of the joint's motion.

Ideal for And Used For
- 🛠 Mechanical Design Validation  
- 🎓 Educational Demonstrations  
- 📊 Kinematic Analysis Projects  

---

## 📌 Features

- 🧮 **Analytical Calculation**  
  - Input/output shaft speeds (RPM)
  - Output shaft angular acceleration (rad/s²)
  - Characteristic angles: θ₁, θ₂, θ₃, θ₄

- 📈 **Polar Velocity Diagram**  
  - Visualizes velocity variation of the driven shaft
  - Shows max/min RPM in polar format

- 🎞 **Animated Simulation**  
  - Real-time animation of input and output shaft motion
  - Visual demonstration of angular misalignment effects

- 🖥 **Interactive CLI**  
  - User input for driving shaft speed (N) and shaft angle (α)

---

## 🚀 Getting Started

### 📦 Prerequisites

Install Python 3 and the required libraries:

### ✅ Required Python Libraries

<pre> pip install numpy matplotlib </pre>

These libraries are used for:
- **NumPy** → Mathematical computations and array operations
- **Matplotlib** → Plotting the polar velocity diagram and creating animations using FuncAnimation

## ▶️ Run the Script
<pre> python hookes_joint_analysis.py </pre>

Follow the CLI prompts:
- Enter driving shaft speed in RPM
- Enter the angle between shafts in degrees

# 📽 Output Preview
- Polar plot with min/max speeds and angular markers
- Real-time animation of joint movement for 100 frames

# 🛠 Technologies Used
- Python 3
- NumPy
- Matplotlib
- Matplotlib's `FuncAnimation` for simulation

# 📚 Applications
- Kinematic study of mechanical linkages
- Classroom demonstrations of universal joint behaviour
- Design validation for shafts with angular misalignment

# 📄 License
This project is open-source and free to use under the MIT License.



