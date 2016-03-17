#
# Copyright (C) 2013-2014 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#
include $(TOPDIR)/rules.mk

ARCH:=aarch64
BOARD:=ls104x
BOARDNAME:=NXP Layerscape 104x
FEATURES:=ramdisk targz squashfs 
CPU_TYPE:=cortex-a53
CPU_SUBTYPE:=neon
KERNEL_PATCHVER:=3.18

include $(INCLUDE_DIR)/target.mk

KERNELNAME:=Image.gz dtbs 

$(eval $(call BuildTarget))
