# Universal Linux Installer - Generator (uli-gen)

This is an attempt to create a universal Linux installation generator for simple programs. 

Basic Requirements for packages to be able to use ULI are - 
 1. The program can be distributed in a folder (i.e. as tar)
 2. The program is portable - i.e. it does not matter where the files of the program are being run from.
 3. The program has simple dependencies that can be resolved using apt, yum or pacman
 4. The program is precompiled (i.e. does not need compilation on target machine). This is not for distributing source codes, only compiled programs. 

## Components

The Universal Linux Installer can perform the following functions - 

### Packager
ULI can create .uli packages that are self-extracting, and self-installing. 
.uli packages can run on any Linux machine. 

If the distributed program has dependencies (for eg. python, ruby), then it is imperative for the target system to have one among the three package managers - apt, yum or pacman. 


