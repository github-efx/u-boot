# SPDX-License-Identifier: GPL-2.0+

dtb-$(CONFIG_TARGET_AX25_AE350) += ae350_32.dtb ae350_64.dtb
dtb-$(CONFIG_TARGET_SIFIVE_FU540) += hifive-unleashed-a00.dtb
dtb-$(CONFIG_TARGET_VEXRISCV_SAXON) += saxon.dtb
dtb-$(CONFIG_TARGET_VEXRISCV_SAXON) += saxon_arty_a7.dtb
dtb-$(CONFIG_TARGET_VEXRISCV_SAXON) += saxon_arty_a7_smp.dtb
dtb-$(CONFIG_TARGET_VEXRISCV_SAXON) += saxon_nexys_a7.dtb
dtb-$(CONFIG_TARGET_VEXRISCV_SAXON) += saxon_ulx3s.dtb
dtb-$(CONFIG_TARGET_VEXRISCV_SAXON) += saxon_tang.dtb
dtb-$(CONFIG_TARGET_VEXRISCV_SAXON) += saxon_efinix_ruby.dtb


targets += $(dtb-y)

DTC_FLAGS += -R 4 -p 0x1000

PHONY += dtbs
dtbs: $(addprefix $(obj)/, $(dtb-y))
	@:

clean-files := *.dtb
