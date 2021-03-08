#
# Makefile for the fingerprint drivers.
#

obj-$(CONFIG_FINGERPRINT_FPC1020) += fpc1020_platform_tee.o fpc_irq.o
obj-$(CONFIG_GOODIX_FINGERPRINT) += gf_spi.o platform.o netlink.o

subdir-ccflags-y := -finline-functions -ftree-vectorize -funroll-loops
