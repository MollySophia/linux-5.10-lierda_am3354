# SPDX-License-Identifier: GPL-2.0
obj-$(CONFIG_VIDEO_TI_VPE) += ti-vpe.o
obj-$(CONFIG_VIDEO_TI_VPDMA) += ti-vpdma.o
obj-$(CONFIG_VIDEO_TI_SC) += ti-sc.o
obj-$(CONFIG_VIDEO_TI_CSC) += ti-csc.o
obj-$(CONFIG_VIDEO_TI_VIP) += ti-vip.o
obj-$(CONFIG_VIDEO_TI_CSI2RX) += ti-csi2rx.o

ti-vpe-y := vpe.o
ti-vpdma-y := vpdma.o
ti-sc-y := sc.o
ti-csc-y := csc.o
ti-vip-y := vip.o

ccflags-$(CONFIG_VIDEO_TI_VPE_DEBUG) += -DDEBUG

obj-$(CONFIG_VIDEO_TI_CAL) += ti-cal.o

ti-cal-y := cal.o
