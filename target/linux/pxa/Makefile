#
# Copyright (C) 2006-2011 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#
include $(TOPDIR)/rules.mk

ARCH:=arm
BOARD:=pxa
BOARDNAME:=Marvell/Intel PXA2xx
SUBTARGETS=verdex zipitz2
MAINTAINER:=Imre Kaloz <kaloz@openwrt.org>

LINUX_VERSION:=3.3.8

include $(INCLUDE_DIR)/target.mk

define Target/Description
	Build images for PXA2xx systems, eg. Gumstix, ZipIt Z2
endef

KERNELNAME:="uImage"

$(eval $(call BuildTarget))
