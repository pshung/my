# PDLL

PDLL is a front-end language for pattern matching.  
A pattern contains match and rewrite sections.  
Match section matches the input of the rewrite section.  
Rewrite section indicates the result of transformation.  

# How to compile a .pdll file

PDLL can be written in a file with pdll file extension.  
We use tool mlir-pdll to compile it into pdl dialect. 

# PDLL usage
[BladeDISC](https://bladedisc.oss-cn-hangzhou.aliyuncs.com/docs/bladedisc-intro-for-intel.pdf), PDLL is used to define custom kernels.  

[code](https://github.com/alibaba/BladeDISC/blob/da990f41641affe228ad5122aaa8badd2ccd70bd/tao_compiler/mlir/disc/transforms/disc_pdl_utils.cc#L411)

