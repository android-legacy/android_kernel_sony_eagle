obj-$(CONFIG_MSM_VIDC_V4L2) += vidc/
obj-$(CONFIG_MSM_WFD) += wfd/
obj-$(CONFIG_DVB_MPQ) += dvb/

ifneq ($(CONFIG_MACH_SONY_EAGLE),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2/
else
obj-$(CONFIG_MSMB_CAMERA) += camera_v2_eagle/
endif
obj-y += vcap/
