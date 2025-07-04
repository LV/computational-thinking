# 🧠 MIT Computational Thinking
Links: [Fall 2020](https://computationalthinking.mit.edu/Fall20/), [Fall 2024](https://computationalthinking.mit.edu/Fall24/)

## Pre-requisites
- `julia`

## Installing Pluto Notebooks
```sh
julia> import Pkg
julia> Pkg.instantiate()
julia> ]
(@v1.11) pkg> add Pluto
```

## Running Pluto
Recommended to use `tmux` or something that can make the notebook resiliant from the shell window.
```sh
julia> import Pluto; Pluto.run()
```

## Syllabus
### 🖼️ PART 1 Foundations – Images, Data, Abstraction
- [X] 2024 Module 1.1 **Images as Data and Arrays**
- [ ] 2024 Module 1.2 **Abstraction**
- [ ] 💪 **Homework 1 – Arrays and Images**
- [ ] 2024 Module 1.3 **Automatic Differentiation**
- [ ] 2024 Module 1.4 **Transformations with Images**
- [ ] 2024 Module 1.5 **Transformations II: Composability, Linearity, and Non-Linearity**
- [ ] 💪 **Homework 2 – Convolutions**
- [ ] 2024 Module 1.6 **The Newton Method**
- [ ] 💪 **Homework 3 – Structure and Language**

---

### 🧩 PART 2 Dynamic Programming, Structure, and Code Design
- [ ] 2024 Module 1.7 **Dynamic Programming**
- [ ] 2020 Lecture 3 **Dynamic Programming, Views, and GPUs** *(Grant, optional only for the 15-min GPU deep dive)*
- [ ] 2024 Module 1.8 **Seam Carving**
- [ ] 2020 Lecture 4 **Live Coding Seam Carving** *(Grant, alternative implementation pattern, optional)*
- [ ] 2024 Module 1.9 **Taking Advantage of Structure**
- [ ] 2020 Lecture 5 **Structure and Dispatch** *(quick skim over dispatch)*
- [ ] 💪 **Homework 4 – Dynamic Programming**

---

### 🎲 PART 3 Probability, Simulation, and Randomness
- [ ] 2020 Lecture 6 **Understanding Data**
- [ ] 2020 Lecture 7 **Introspection, COVID Data Visualization**
- [ ] 2024 Module 2.1 **Principal Component Analysis**
- [ ] 2024 Module 2.2 **Sampling and Random Variables**
- [ ] 💪 **Homework 5 – Structure**
- [ ] 2024 Module 2.3 **Modeling with Stochastic Simulation**
- [ ] 2020 Lecture 8 **Probability via Computation** *(Grant, intuition, optional)*
- [ ] 2024 Module 2.4 **Random Variables as Types**
- [ ] 💪 **Homework 6 – Probability Distributions**
- [ ] 2024 Module 2.5 **Random Walks**
- [ ] 2024 Module 2.6 **Random Walks II**

---

### 🧬 PART 4 Epidemics, Networks, and Optimization
- [ ] 2024 Module 2.7 **Discrete and Continuous**
- [ ] 2020 Lecture 9 **Graphs = Matrices and the Expression Problem** *(Grant Sanderson, optional-intuition)*
- [ ] 2020 Lecture 10 **Graphs and Disease Spread** *(recommended)*
- [ ] 💪 **Homework 7 – Epidemic Modeling I**
- [ ] 2024 Module 2.8 **Linear Model, Data Science, and Simulations**
- [ ] 2020 Lecture 11 **Epidemic Modeling and Documenting Code** *(recommended)*
- [ ] 2020 Lecture 12 **Macroscopic Models: Discrete vs Continuous** *(optional)*
- [ ] 2024 Module 2.9 **Optimization**
- [ ] 2020 Lecture 13 **Graphs and Network Dynamics** *(Grant, optional-intuition)*
- [ ] 💪 **Homework 8 – Epidemic Modeling II**
- [ ] 💪 **Homework 9 – Epidemic Modeling III**

---

### 🕶️ PART 5 Ray Tracing and Visual Computing
- [ ] 2020 Lecture 14 **Ray Tracing, Your Own Parallelism, Abstract Arrays**
- [ ] 2020 Lecture 15 **Billiard Model and Event-driven Simulation**
- [ ] 2020 Lecture 16 **Raytracing in 3D**
- [ ] 2020 Lecture 17 **Raytracing Live Coding**
- [ ] 💪 **2020 HW 7 – Ray Tracing 2-D**
- [ ] 2020 Lecture 19 **Floating-Point Arithmetic**
- [ ] 💪 **2020 HW 8 – Ray Tracing 3D** *(challenge, optional)*
- [ ] 🌟 **Capstone – Build Your Own Mini Ray Tracer**

---

### 🌍 PART 6 Climate Modeling, PDEs, and Hysteresis
- [ ] 2024 Module 3.1 **Time Stepping**
- [ ] 2024 Module 3.2 **ODEs and Parametrized Types**
- [ ] 2024 Module 3.3 **Why We Can’t Predict Weather**
- [ ] 2024 Module 3.4 **Our First Climate Model**
- [ ] 2024 Module 3.5 **GitHub and Open Source Software** *(skim very quickly)*
- [ ] 2020 Lecture 20 **Introduction to Climate Modeling, Nonlinearity** *(enrichment, optional)*
- [ ] 2024 Module 3.6 **Snowball Earth and Hysteresis**
- [ ] 2020 Lecture 21 **Nonlinear Climate Dynamics and Snowball Earth** *(optional, richer geophysical narrative)*
- [ ] 2024 Module 3.7 **Advection and Diffusion in 1D**
- [ ] 2020 Lecture 22 **Diffusion Equation and Time and Space Evolution** (Good PDE intuition not in 2024)
- [ ] 💪 **Homework 10 – Climate Modeling I**
- [ ] 2024 Module 3.8 **Resistors, Stencils, and Climate Models**
- [ ] 2024 Module 3.9 **Advection and Diffusion in 2D**
- [ ] 2020 Lecture 18 **Hierarchical Thinking, Greedy Algorithms, Jacobi's Method, and Multigrid**
- [ ] 🌟 **Mini-Project – 1D Multigrid Solver**
- [ ] 2020 Lecture 23 **Heat Transfer by Ocean Currents** (comes up after 3.9)

---

### 📈 PART 7 Climate Economics and Inverse Problems
- [ ] 2024 Module 3.10 **Climate Economics**
- [ ] 2024 Module 3.11 **Solving Inverse Problems**
- [ ] 💪 **2020 HW 10 – Climate Modeling II** *(advanced, optional)*

---

### 🌀 PART 8 Bonus Conceptual Explorations
- [ ] 2020 Lecture 26 **Discrete Fourier Transform**
