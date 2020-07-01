# Matlab or Julia

<img src="images/pills.jpg" width=250px/>

## !!! warning
This Project is far from complete, if you are interested to know the replacement of a Matlab functionality in Julia, PLEASE FILE AN ISSUE!

## Table of content

According to the [official site](https://www.mathworks.com/products.html), matlab contains the following products and features

## Matlab products and services
The following list are arranged like
```
* MATLAB FEATURE 1
    * JULIA REPLACEMENT 1: descriptions.
    * JULIA REPLACEMENT 2: descriptions.
    * ...
* MATLAB FEATURE 2
* ...
```

### MATLAB
### Parallel Computing

* Parallel Computing Toolbox
    * [builtin multithreading](https://docs.julialang.org/en/v1/base/multi-threading/)
    * [MPI.jl](https://github.com/JuliaParallel/MPI.jl)
* MATLAB Parallel Server

### Math and Optimization

* Curve Fitting Toolbox
    * [LstFit.jl](https://github.com/JuliaNLSolvers/LsqFit.jl): least square fit
* Optimization Toolbox
    * [Optim.jl](https://github.com/JuliaNLSolvers/Optim.jl)
* Global Optimization Toolbox
    * [Evolutionary.jl](Evolutionary.jl): Evolutionary & genetic algorithms
    * [JuMP.jl](https://github.com/jump-dev/JuMP.jl) Modeling language for Mathematical Optimization (linear, mixed-integer, conic, semidefinite, nonlinear)
* Symbolic Math Toolbox
    * [SymEngine.jl](https://github.com/symengine/SymEngine.jl)
    * [SymbolicUtils.jl](https://github.com/JuliaSymbolics/SymbolicUtils.jl)
* Mapping Toolbox
* Partial Differential Equation Toolbox
    * [DifferentialEquations.jl](https://docs.sciml.ai/stable/)

### AI, Data Science, and Statistics

* Statistics and Machine Learning Toolbox
    * [Distributions.jl](https://github.com/JuliaStats/Distributions.jl)
    * [StatsBase.jl](https://github.com/JuliaStats/StatsBase.jl)
    * [Turing.jl](https://github.com/TuringLang/Turing.jl): Bayesian inference with probabilistic programming.
    * [Gen.jl](https://github.com/probcomp/Gen.jl): A general-purpose probabilistic programming system with programmable inference
* Deep Learning Toolbox
    * [click here](ml.md)
* Reinforcement Learning Toolbox
    * [ReinforcementLearning.jl](https://github.com/JuliaReinforcementLearning/ReinforcementLearning.jl)
* Text Analytics Toolbox
* Predictive Maintenance Toolbox

### Code Generation

* MATLAB Coder
    * [Atom/Juno](https://junolab.org/)
    * [VScode](https://github.com/julia-vscode/julia-vscode)
    * [Jupyter notebook](https://jupyter.org/)
* Embedded Coder
* HDL Coder
* HDL Verifier
* Filter Design HDL Coder
* Fixed-Point Designer
* GPU Coder
    * [CUDA.jl](https://github.com/JuliaGPU/CUDA.jl)

### Application Deployment [skipped]

### Database Access and Reporting

* Database Toolbox
    * [JuliaDB.jl](https://github.com/JuliaData/JuliaDB.jl): Parallel analytical database in pure Julia
* MATLAB Report Generator

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
