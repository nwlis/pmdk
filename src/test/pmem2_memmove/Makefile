# SPDX-License-Identifier: BSD-3-Clause
# Copyright 2020, Intel Corporation

#
# src/test/pmem2_memmove/Makefile -- build pmem2_memmove test
#
TOP = ../../..
vpath %.c $(TOP)/src/test/unittest
INCS += -I$(TOP)/src/libpmem2

TARGET = pmem2_memmove
OBJS += pmem2_memmove.o\
	memmove_common.o\
	ut_pmem2_utils.o\
	ut_pmem2_config.o

LIBPMEM2=y

include ../Makefile.inc
