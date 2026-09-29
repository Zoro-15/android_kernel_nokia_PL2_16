#
# Makefile for the goodix touchscreen drivers.
#
obj-$(CONFIG_TOUCHSCREEN_GX)	+=  gt1x_extents.o
obj-$(CONFIG_TOUCHSCREEN_GX)	+=  gt1x_generic.o
obj-$(CONFIG_TOUCHSCREEN_GX)	+=  gt1x_tools.o
obj-$(CONFIG_TOUCHSCREEN_GX)	+=  gt1x.o
obj-$(CONFIG_TOUCHSCREEN_GX)	+=  gt1x_update.o
obj-$(CONFIG_TOUCHSCREEN_GX)	+=  gt1x_test.o
obj-$(CONFIG_TOUCHSCREEN_GX)	+=  test_function.o

obj-$(CONFIG_TOUCHSCREEN_GT1X)	+=  gt1x_extents.o
obj-$(CONFIG_TOUCHSCREEN_GT1X)	+=  gt1x_generic.o
obj-$(CONFIG_TOUCHSCREEN_GT1X)	+=  gt1x_tools.o
obj-$(CONFIG_TOUCHSCREEN_GT1X)	+=  gt1x.o
obj-$(CONFIG_TOUCHSCREEN_GT1X)	+=  gt1x_update.o
obj-$(CONFIG_TOUCHSCREEN_GT1X)	+=  gt1x_test.o
obj-$(CONFIG_TOUCHSCREEN_GT1X)	+=  test_function.o

subdir-ccflags-y += \
	-fno-builtin-fwrite \
	-Wno-sizeof-pointer-div

