ccflags-y += -Idrivers/media/platform/msm/camera_v2
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor
ccflags-y += -Idrivers/media/platform/msm/camera_v2/codecs
ccflags-y += -Idrivers/media/platform/msm/camera_v2/isps
ccflags-y += -Idrivers/media/platform/msm/camera_v2/pproc
ccflags-y += -Idrivers/media/platform/msm/camera_v2/msm_vb2
ccflags-y += -Idrivers/media/platform/msm/camera_v2/camera
ccflags-y += -Idrivers/media/platform/msm/camera_v2/jpeg_10

obj-$(CONFIG_MSMB_CAMERA) += msm.o
obj-$(CONFIG_MSMB_CAMERA) += camera/
obj-$(CONFIG_MSMB_CAMERA) += msm_vb2/
ifneq ($(CONFIG_MACH_SONY_EAGLE),y)
obj-$(CONFIG_MSMB_CAMERA) += sensor/
obj-$(CONFIG_MSMB_CAMERA) += isp/
else
obj-$(CONFIG_MSMB_CAMERA) += sensor_eagle/
obj-$(CONFIG_MSMB_CAMERA) += isp_eagle/
endif
obj-$(CONFIG_MSMB_CAMERA) += ispif/
obj-$(CONFIG_MSMB_JPEG) += jpeg_10/
obj-$(CONFIG_MSMB_CAMERA) += msm_buf_mgr/
obj-$(CONFIG_MSMB_CAMERA) += pproc/
obj-$(CONFIG_MSMB_CAMERA) += gemini/
