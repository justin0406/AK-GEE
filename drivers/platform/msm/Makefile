#
# Makefile for the MSM specific device drivers.
#

ccflags-y += -Isecurity/selinux -Isecurity/selinux/include

obj-$(CONFIG_MSM_SSBI) += ssbi.o
obj-$(CONFIG_USB_BAM) += usb_bam.o
obj-$(CONFIG_SPS) += sps/
obj-$(CONFIG_QPNP_PWM) += qpnp-pwm.o
obj-$(CONFIG_QPNP_POWER_ON) += qpnp-power-on.o
obj-$(CONFIG_QPNP_CLKDIV) += qpnp-clkdiv.o
obj-$(CONFIG_PFT) += pft.o
obj-y += avtimer.o