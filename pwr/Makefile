ifeq ($(BT_ROOT),)
BT_ROOT := $(srctree)/techpack/bt
endif

ccflags-y += -I$(BT_ROOT)/include

obj-$(CONFIG_MSM_BT_POWER)  += btpower.o
