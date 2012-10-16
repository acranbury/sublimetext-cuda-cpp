sublimetext-cuda-cpp
====================

CUDA C++ package for Sublime Text 2

Syntax Highlighting
-------------------

Currently supports highlighting of all CUDA C/C++ syntax defined in Appendices [B][1] and [C][2] of the NVIDIA CUDA C Programming Guide.

Snippets
--------

 - __syncthreads(): "__s"+[TAB]
 - Execution Configuration: "<<<"+[TAB] --> `<<<gridDim, blockDim, sharedBytes, streamId>>>()` with tab stops on each of the arguments.
 - All existing snippets from the C++ package included with Sublime Text 2
 
Contributing
------------

If you want to contribute to this package, please make syntax changes in the cuda-c++.JSON-tmLanguage file, NOT in the cuda-c++.tmLanguage file. I use the AAAPackageDev package for Sublime text to make development easier, including converting JSON to plist (XML) format.


[1]: http://docs.nvidia.com/cuda-c-programming-guide/index.html#c-language-extensions
[2]: http://docs.nvidia.com/cuda-c-programming-guide/index.html#mathematical-functions-appendix