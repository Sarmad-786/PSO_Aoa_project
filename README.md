# PSO_Aoa_project
# Particle Swarm Optimization (PSO)

## 📌 Project Title
**Implementation and Evaluation of Particle Swarm Optimization Using the Sphere Function**

## 👨‍💻 Author
- **Name**: Muhammad Sarmad Chughtai  
- **SAPP ID**: 54915  
- **Course**: Analysis of Algorithm  
- **Instructor**: Sir Usman Sharif  
- **University**: Riphah International University, Islamabad

## 🧠 Description
This project implements the **Particle Swarm Optimization (PSO)** algorithm in C++ to solve continuous optimization problems. The benchmark problem used for testing is the **Sphere Function**, a common mathematical function used to evaluate optimization algorithms.

## ⚙️ Algorithm Summary
Particle Swarm Optimization is a population-based search technique inspired by the social behaviour of birds and fish. It uses particles (potential solutions) that move through the solution space and adjust their positions based on their personal best and the global best.

## 📌 Key Features
- Simple C++ implementation using only standard headers
- Tested on the Sphere Function
- Configurable parameters like number of particles, dimensions, and iterations
- Tracks global best and personal best

## 🛠️ How to Compile
```bash
g++ -o pso pso.cpp
**## How to Run**
./pso
🧪 Sample Output
Global Best Solution: 0.00345 0.00291
Global Best Fitness Value: 0.00002
📊 Time and Space Complexity
Time: O(N * D * T)
Space: O(N * D)
Where:
N = number of particles
D = number of dimensions
T = number of iterations

📚 Applications
Engineering Design Optimization
Machine Learning (e.g., Feature Selection)
Control Systems
Signal Processing

⚠️ Limitations
May converge to local minima
Performance may degrade in high-dimensional or noisy search spaces



