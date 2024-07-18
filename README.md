# llvm-legacy

Old versions of Clang/LLVM, patched so that they can be built using more recent compilers

There is a branch for each LLVM version that is supported.

The patched version 2.7 has been shown to build successfully with:

- gcc 11.4.0

For some reason, the build process causes a change to this file in the source tree:

- llvm-2.7/cmake/modules/LLVMLibDeps.cmake
