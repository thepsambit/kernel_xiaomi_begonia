#
# Copyright (C) 2015 MediaTek Inc.
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License version 2 as
# published by the Free Software Foundation.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
# GNU General Public License for more details.
#
obj-$(CONFIG_MACH_MT6768) += drcc_v1/
obj-$(CONFIG_MACH_MT6785) += drcc_v1/
obj-$(CONFIG_MACH_MT6768) += spm/
obj-$(CONFIG_MACH_MT6785) += spm/
obj-$(CONFIG_MACH_MT6785) += power_gs_v1/
obj-$(CONFIG_MTK_STATIC_POWER) += leakage_table_v2/
obj-$(CONFIG_MTK_CPU_FREQ) += cpufreq_v1/
obj-$(CONFIG_MACH_MT6768) += dcm_v1/
obj-$(CONFIG_MACH_MT6785) += dcm_v1/
ifneq ($(CONFIG_FPGA_EARLY_PORTING), y)
obj-$(CONFIG_MACH_MT6771) += cpuidle_v3/
obj-$(CONFIG_MACH_MT6771) += pbm_v3/
obj-$(CONFIG_MACH_MT6785) += pbm_v4/
obj-$(CONFIG_MACH_MT6768) += pbm_v4/
obj-$(CONFIG_MACH_MT6768) += mdpm_v1/
obj-$(CONFIG_MACH_MT6785) += mdpm_v2/
obj-$(CONFIG_MACH_MT6771) += spm_v4/
obj-$(CONFIG_MACH_MT6771) += vcorefs_v3/
obj-$(CONFIG_MACH_MT6771) += $(subst ",,$(CONFIG_MTK_PLATFORM))/
obj-$(CONFIG_MACH_MT6768) += $(subst ",,$(CONFIG_MTK_PLATFORM))/
obj-$(CONFIG_MACH_MT6785) += $(subst ",,$(CONFIG_MTK_PLATFORM))/
obj-$(CONFIG_MACH_MT6768) += clkbuf_v1/
obj-$(CONFIG_MACH_MT6771) += clkbuf_v1/
obj-$(CONFIG_MACH_MT6785) += clkbuf_v1/
endif
ifeq ($(CONFIG_MTK_CM_MGR), y)
obj-$(CONFIG_MTK_CM_MGR) += cm_mgr_v1/
endif
obj-$(CONFIG_MTK_SWPM) += swpm_v1/

obj-$(CONFIG_MACH_MT6771) += mcdi/
obj-$(CONFIG_MACH_MT6768) += mcdi/
obj-$(CONFIG_MACH_MT6785) += mcdi/
obj-$(CONFIG_MACH_MT6771) += cpuhotplug/
obj-$(CONFIG_MACH_MT6771) += ppm_v3/
obj-$(CONFIG_MACH_MT6768) += ppm_v3/
obj-$(CONFIG_MACH_MT6768) += cpuhotplug/
obj-$(CONFIG_MACH_MT6768) += cpuidle_v3/
obj-$(CONFIG_MACH_MT6768) += udi_v2/
obj-$(CONFIG_MACH_MT6785) += udi_v2/
obj-$(CONFIG_MACH_MT6785) += cpuhotplug/
obj-$(CONFIG_MTK_PTPOD) += eem_v2/
ifeq ($(CONFIG_MTK_UNIFY_POWER), y)
obj-$(CONFIG_MTK_UNIFY_POWER) += upower_v2/
obj-$(CONFIG_MACH_MT6771) += upower_v2/
endif
obj-$(CONFIG_MACH_MT6785) += cpuidle_v3/
obj-$(CONFIG_MACH_MT6785) += ppm_v3/
obj-$(CONFIG_MTK_QOS_V2) += qos/
