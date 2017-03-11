# setGPU

A small Python library that automatically sets `CUDA_VISIBLE_DEVICES`
to the most vacant GPU (in terms of memory usage) on multi-GPU systems.

+ Installation: 
`pip install git+https://github.com/li-js/setGPU.git@master`
+ Usage: `import setGPU` before any import that will use a GPU like `torch` or `tensorflow`.

# Dependencies

+ Jongwook Choi's [gpustat](https://github.com/wookayin/gpustat) library. 
It can be installed by 
`pip install gpustat`

# Licensing

This code is in the public domain.
