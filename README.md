# Symmetric Pipelined FIR Filter — RTL Implementation

A 12-tap symmetric low-pass FIR filter implemented in Verilog with a 3-stage pipeline datapath.  
Verified through RTL simulation in Vivado and a Python reference model.

---
## Repository Structure

```text
├── rtl/
│   ├── symmetricFIR.v    
│   ├── coeff_loader.v    
│   ├── delay_line.v      
│   ├── pre_adder.v       
│   └── fir_pipeline.v    
│
├── sim/
│   └── symmetricFIR_tb.v 
│
├── scripts/
│   └── gen_noisy_sig.py  
│
└── README.md
```

---
