#-------------------------------------------------------------------------
#
# Makefile--
#    Makefile for storage/GroundDB
#
# IDENTIFICATION
#    src/backend/storage/GroundDB/Makefile
#
#-------------------------------------------------------------------------

subdir = src/backend/storage/GroundDB
top_builddir = ../../../..
include $(top_builddir)/src/Makefile.global

OBJS = \
	mempool_client.o \
	mempool_server.o \
	pat.o \
	rdma_server.o \
	cache.o \
	rdma_manager.o \
	ThreadPool.o

include $(top_srcdir)/src/backend/common.mk
