# Multi-fidelity parameter tuning
Multi-fidelity parameter tuning for Nature Inspired Optimization(NIO) algorithms

The python code is used in the manuscript [Multi-fidelity Meta-optimization for Nature Inspired Optimization Algorithms]() submitted to "Applied soft computing".

The programming environment is: `Python 3.6` or higher.

## Directory Structure
The folders in the package include:
1. **algorithms**: Basic algorithms, including base class `Algorithm` and `[CS, DE, FOA, GWO, KH, PSO, SSA, WWO, WOA]`.

2. **applications**: An engineering application: source term estimation. 

  > [Fast source term estimation using the PGA-NM hybrid method](https://doi.org/10.1016/j.engappai.2017.03.010)

3. **benchmarks**: Test functions, including base class `Benchmark`, basic test functions and `CEC2014 Benchmark Suite`.
  > [Problem Definitions and Evaluation Criteria for the CEC 2014 Special Session and Competition on Single Objective Real-Parameter Numerical Optimization](https://www.ntu.edu.sg/home/EPNSugan/index_files/CEC2014/CEC2014.htm)

4. **demo**: Examples.

5. **parameter_tuning**: Multi-fidelity meta-NIOs and optimized-NIOs.

## Help Information
If you prefer using the command line to run the program, please do not forget to manually add the working directory to `sys.path`.
