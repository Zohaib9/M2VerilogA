# M2VerilogA
Matlab to VerilogA 

A wrapper class which takes an S-parameter or a Z-parameter file as input in '.snp' touchstone format or .mat file in matlab and generates a compact dynamical model as output. The code incorporates binary search to find minimum system order for given error bound. Final model is saved in a verilogA file which can be easily interfaced with commercial simulators such as spectre.
