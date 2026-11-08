# MlbUtilities

## Description
A miscellany of utility executables.
																								 
## This Repository
https://github.com/mlbrock/MlbUtilities

## Related Repositories
* LbmWrapper (in https://github.com/mlbrock/LbmWrapper)
* RvUtilX (in https://github.com/mlbrock/RvUtilX)
* SocketIo (in https://github.com/mlbrock/SocketIo)
* UtilityOld (in https://github.com/mlbrock/UtilityOld)

## External Dependencies
### Git
* Any recent version of git.
### GNU C++ Compiler
* GNU g++ 4.1.2 through gcc 16.1.1 are supported.
### Boost
* Boost 1.32 through Boost 1.90 are supported.
### 29West LBM
* LBM 3.4.1 and above are supported.
### Tibco Redezvous
* Tib/Rendezvous 6.3 and above are supported.

## How-to Build
### Install external dependencies:
* Install git
* Install GNU g++
* Install Boost
* Install 29West LBM include files and libraries
* Install Tibco Rendezvous include files and libraries
### Get the related repositories and build them:
* Clone the related repositories:

    `git clone https://github.com/mlbrock/LbmWrapper`
  
    `git clone https://github.com/mlbrock/RvUtilX`

    `git clone https://github.com/mlbrock/SocketIo`

    `git clone https://github.com/mlbrock/UtilityOld`

* Follow the build instructions in the related repositories README.md files.
### Get the current source distribution:
    git clone https://github.com/mlbrock/MlbUtilities
### Change to the cloned top-level directory:
    cd MlbUtilities
### Clean an existing build (if necessary):
    ./SimpleBuildDriver.sh clean
### Run the build script:
    ./SimpleBuildDriver.sh
### Check for build warnings or errors:
    grep -P '((warning)|(error)):' `ls -1 BuildResults.*|sort -r|head -n 1`

