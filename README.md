# Matlab or Julia

<img src="images/pills.jpg" width=250px/>

## !!! warning
This Project is far from complete, if you are interested to know the replacement of a Matlab functionality in Julia, PLEASE FILE AN ISSUE!

## Table of content

The following list is arranged like

![#DD3300](https://via.placeholder.com/15/DD3300/000000?text=+) 
Item Julia lose

* Julia Package 1: descriptions.
* Julia Package 2: descriptions.
* ...

![#0033DD](https://via.placeholder.com/15/0033DD/000000?text=+) 
Item Julia win

![#888888](https://via.placeholder.com/15/888888/000000?text=+)
Item hard to say

## Products and Services in Matlab

According to the [official site](https://www.mathworks.com/products.html), matlab contains the following products and features

### MATLAB
### Parallel Computing

![#888888](https://via.placeholder.com/15/888888/000000?text=+)
Parallel Computing Toolbox

* [builtin multithreading](https://docs.julialang.org/en/v1/base/multi-threading/)
* [MPI.jl](https://github.com/JuliaParallel/MPI.jl)

### Math and Optimization

![#888888](https://via.placeholder.com/15/888888/000000?text=+)
Curve Fitting Toolbox

* [LstFit.jl](https://github.com/JuliaNLSolvers/LsqFit.jl): least square fit

![#888888](https://via.placeholder.com/15/888888/000000?text=+)
Optimization Toolbox

* [Optim.jl](https://github.com/JuliaNLSolvers/Optim.jl)

![#0033DD](https://via.placeholder.com/15/0033DD/000000?text=+) 
Global Optimization Toolbox

* [Evolutionary.jl](Evolutionary.jl): Evolutionary & genetic algorithms
* [JuMP.jl](https://github.com/jump-dev/JuMP.jl) Modeling language for Mathematical Optimization (linear, mixed-integer, conic, semidefinite, nonlinear)

![#888888](https://via.placeholder.com/15/888888/000000?text=+)
Symbolic Math Toolbox

* [SymEngine.jl](https://github.com/symengine/SymEngine.jl)
* [SymbolicUtils.jl](https://github.com/JuliaSymbolics/SymbolicUtils.jl)

![#888888](https://via.placeholder.com/15/888888/000000?text=+)
Mapping Toolbox

![#0033DD](https://via.placeholder.com/15/0033DD/000000?text=+) 
Partial Differential Equation Toolbox

* [DifferentialEquations.jl](https://docs.sciml.ai/stable/): probably the best differential equation solver, check [here](http://www.stochasticlifestyle.com/wp-content/uploads/2019/08/de_solver_software_comparsion.pdf).

### AI, Data Science, and Statistics

![#888888](https://via.placeholder.com/15/888888/000000?text=+)
Statistics and Machine Learning Toolbox

* [Distributions.jl](https://github.com/JuliaStats/Distributions.jl)
* [StatsBase.jl](https://github.com/JuliaStats/StatsBase.jl)
* [Turing.jl](https://github.com/TuringLang/Turing.jl): Bayesian inference with probabilistic programming.
* [Gen.jl](https://github.com/probcomp/Gen.jl): A general-purpose probabilistic programming system with programmable inference


![#0033DD](https://via.placeholder.com/15/0033DD/000000?text=+) 
Deep Learning Toolbox

* [click here](ml.md)

![#888888](https://via.placeholder.com/15/888888/000000?text=+)
Reinforcement Learning Toolbox

* [ReinforcementLearning.jl](https://github.com/JuliaReinforcementLearning/ReinforcementLearning.jl)

![#888888](https://via.placeholder.com/15/888888/000000?text=+)
Text Analytics Toolbox

![#888888](https://via.placeholder.com/15/888888/000000?text=+)
Predictive Maintenance Toolbox

### Code Generation

![#888888](https://via.placeholder.com/15/888888/000000?text=+)
MATLAB Coder

* [Atom/Juno](https://junolab.org/)
* [VScode](https://github.com/julia-vscode/julia-vscode)
* [Jupyter notebook](https://jupyter.org/)


![#888888](https://via.placeholder.com/15/888888/000000?text=+)
Embedded Coder


![#888888](https://via.placeholder.com/15/888888/000000?text=+)
HDL Coder

![#888888](https://via.placeholder.com/15/888888/000000?text=+)
HDL Verifier

![#888888](https://via.placeholder.com/15/888888/000000?text=+)
Filter Design HDL Coder

![#888888](https://via.placeholder.com/15/888888/000000?text=+)
Fixed-Point Designer

![#0033DD](https://via.placeholder.com/15/0033DD/000000?text=+) 
GPU Coder

* [CUDA.jl](https://github.com/JuliaGPU/CUDA.jl)

### Application Deployment [skipped]

### Database Access and Reporting


![#888888](https://via.placeholder.com/15/888888/000000?text=+)
Database Toolbox

* [JuliaDB.jl](https://github.com/JuliaData/JuliaDB.jl): Parallel analytical database in pure Julia

![#888888](https://via.placeholder.com/15/888888/000000?text=+)
MATLAB Report Generator

## Simulink
* System Composer

### Event-Based Modeling

* Stateflow
* SimEvents

### Physical Modeling

* Simscape
* Simscape Driveline
* Simscape Electrical
* Simscape Fluids
* Simscape Multibody

### Real-Time Simulation and Testing

* Simulink Real-Time
* Simulink Desktop Real-Time

### Code Generation

* Simulink Coder
* Embedded Coder
* AUTOSAR Blockset
* Fixed-Point Designer
* Simulink PLC Coder
* Simulink Code Inspector
* DO Qualification Kit (for DO-178)
* IEC Certification Kit (for ISO 26262 and IEC 61508)
* HDL Coder
* HDL Verifier

### Application Deployment

* Simulink Compiler

### Verification, Validation, and Test

* Simulink Requirements
* Simulink Check
* Simulink Coverage
* Simulink Design Verifier
* Simulink Test
* Polyspace Bug Finder
* Polyspace Code Prover

### Simulation Graphics and Reporting

* Simulink 3D Animation
* Simulink Report Generator

## APPLICATION PRODUCTS
### Signal Processing

* Signal Processing Toolbox
* Phased Array System Toolbox
* DSP System Toolbox
* Audio Toolbox
* Wavelet Toolbox

### Image Processing and Computer Vision

* Image Processing Toolbox
    * [Images.jl](https://github.com/JuliaImages/Images.jl)
* Computer Vision Toolbox
    * [click here](plotting.md)

### Control Systems

* Control System Toolbox
* System Identification Toolbox
* Predictive Maintenance Toolbox
* Robust Control Toolbox
* Model Predictive Control Toolbox
* Fuzzy Logic Toolbox
* Simulink Control Design
* Simulink Design Optimization
* Reinforcement Learning Toolbox
* Motor Control Blockset

### Test and Measurement

* Data Acquisition Toolbox
* Instrument Control Toolbox
* Image Acquisition Toolbox
* OPC Toolbox
* Vehicle Network Toolbox
* ThingSpeak

### RF and Mixed Signal

* Antenna Toolbox
* RF Toolbox
* RF Blockset
* Mixed-Signal Blockset
* SerDes Toolbox

### Wireless Communications

* Communications Toolbox
* WLAN Toolbox
* LTE Toolbox
* 5G Toolbox

### Autonomous Systems

* Automated Driving Toolbox
* Robotics System Toolbox
* Navigation Toolbox
* ROS Toolbox
* Sensor Fusion and Tracking Toolbox
* RoadRunner
* RoadRunner Asset Library

### FPGA, ASIC, and SoC Development

* HDL Coder
* HDL Verifier
* Wireless HDL Toolbox
* Vision HDL Toolbox
* Filter Design HDL Coder
* Fixed-Point Designer
* SoC Blockset

### Automotive

* Model-Based Calibration Toolbox
* Powertrain Blockset
* Vehicle Dynamics Blockset
* Automated Driving Toolbox
* IEC Certification Kit (for ISO 26262 and IEC 61508)
* Vehicle Network Toolbox
* AUTOSAR Blockset
* RoadRunner
* RoadRunner Asset Library

### Aerospace

* Aerospace Blockset
* Aerospace Toolbox
* DO Qualification Kit (for DO-178)

### Computational Finance

* Econometrics Toolbox
* Financial Toolbox
* Datafeed Toolbox
* Database Toolbox
* Spreadsheet Link (for Microsoft Excel)
* Financial Instruments Toolbox
* Trading Toolbox
* Risk Management Toolbox

### Computational Biology

* Bioinformatics Toolbox
* SimBiology

### Code Verification

* Polyspace Bug Finder
* Polyspace Bug Finder Access
* Polyspace Bug Finder Server
* Polyspace Code Prover
* Polyspace Code Prover Access
* Polyspace Code Prover Server
* Polyspace Products for Ada
