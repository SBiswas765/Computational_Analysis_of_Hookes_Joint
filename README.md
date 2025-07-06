🔩 Computational Analysis of Hooke's Joint
A Python tool to analyze and visualize the kinematics of a Hooke's (universal) joint. It calculates critical parameters like shaft speeds, angular acceleration, and angles (θ₁–θ₄), then generates both a polar velocity diagram and a real-time simulation of the joint's motion.

Ideal for:

🛠 Mechanical design validation

🎓 Educational demonstrations

📊 Kinematic analysis projects

📌 Features
🧮 Analytical Calculation
Computes:

Input/output shaft speeds (RPM)

Output shaft angular acceleration (rad/s²)

Characteristic angles: θ₁, θ₂, θ₃, θ₄

📈 Polar Velocity Diagram

Visualizes velocity variation of the driven shaft

Shows max/min RPM in polar format

🎞 Animated Simulation

Real-time animation of input and output shaft motion

Visual demonstration of angular misalignment effects

🖥 Interactive CLI

User input for driving shaft speed (N) and shaft angle (α)

🚀 Getting Started
📦 Prerequisites
Ensure Python 3.x is installed along with the following libraries:

bash
Copy
Edit
pip install numpy matplotlib
▶️ Run the Script
bash
Copy
Edit
python hookes_joint_analysis.py
Follow the CLI prompts:

Enter driving shaft speed in RPM

Enter angle between shafts in degrees

📽 Output Preview
Polar plot with min/max speeds and angular markers

Real-time animation of joint movement for 100 frames

🛠 Technologies Used
Python 3

NumPy

Matplotlib

Matplotlib's FuncAnimation for simulation

📚 Applications
Kinematic study of mechanical linkages

Classroom demonstrations of universal joint behavior

Design validation for shafts with angular misalignment

📄 License
This project is open-source and free to use under the MIT License.


