# SPDX-License-Identifier: GPL-2.0-or-later
#
# Copyright (C) 2018 MediaTek Inc.
#

PLATFORM := $(subst ",,$(CONFIG_MTK_PLATFORM))

ccflags-y += \
	-I$(srctree)/drivers/misc/mediatek/emi/$(PLATFORM) \
	-I$(srctree)/drivers/misc/mediatek/emi/submodule

obj-$(CONFIG_MTK_DEVMPU) += devmpu.o
