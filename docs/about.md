## Building The Code

Code must be built before it can be ran. Obtain the code from [Github](https://github.com/coolmule0/LP). This uses [CMAKE](https://cmake.org/download/) to generate the build files. 

### CMAKE

* Set CMake to build from the root directory of the downloaded folder. 
* Add the correct architecture for your GPU using -arch=sm_xx under `CMAKE_CUDA_FLAGS`, replacing xx with the relevant version

    e.g. for a GTX 970, which uses compute 3.5, use -arch=sm_35
    
    Check out [this list](https://en.wikipedia.org/wiki/CUDA#GPUs_supported) for help discovering your compute version
* This should generate the relevant solution/makefile

## Running The Program
