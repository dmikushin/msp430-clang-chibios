# Switch between GCC and LLVM
USE_LLVM ?=

ifeq ($(USE_LLVM), 1)
include Makefile.llvm
else
include Makefile.gcc
endif
