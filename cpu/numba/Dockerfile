FROM mxnet:latest
MAINTAINER Mayank Srivastava <mayankdiatm@gmail.com>

# install numba (JIT compiler for python)
# current version are llvm-3.8, clang-3.8, llvmlite-0.14.0, numba-0.29
RUN apt-get update && \
    apt-get install -y llvm clang && \
    pip2 install llvmlite==0.14.0 numba && \
    pip3 install llvmlite==0.14.0 numba
