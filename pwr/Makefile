ifeq ($(BT_ROOT),)
BT_ROOT := $(srctree)/techpack/bt
endif

ccflags-y += -I$(BT_ROOT)/include
ifeq ($(CONFIG_FMD_ENABLE), y)
ccflags-y += -I$(BT_ROOT)/../wlan/inc
endif
ifeq ($(CONFIG_BT_HW_SECURE_DISABLE), y)
ccflags-y += -I$(BT_ROOT)/../securemsm/include
endif

obj-$(CONFIG_MSM_BT_POWER)  += btpower.o
