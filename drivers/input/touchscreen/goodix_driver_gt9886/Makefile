#obj-$(CONFIG_TOUCHSCREEN_GOODIX_GTX8) += goodix_ts_i2c.o goodix_ts_core.o goodix_cfg_bin.o goodix_gtx8_update.o  goodix_ts_gesture.o goodix_ts_tools.o test_core/

ccflags-y += -mllvm -inline-threshold=15000
ccflags-y += -mllvm -inlinehint-threshold=10000
obj-$(CONFIG_TOUCHSCREEN_GOODIX_GTX8)     		+= goodix_ts_i2c.o
obj-$(CONFIG_TOUCHSCREEN_GOODIX_GTX8)           	+= goodix_ts_core.o
obj-$(CONFIG_TOUCHSCREEN_GOODIX_GTX8)           	+= goodix_cfg_bin.o
obj-$(CONFIG_TOUCHSCREEN_GOODIX_GTX8_UPDATE)    	+= goodix_gtx8_update.o
obj-$(CONFIG_TOUCHSCREEN_GOODIX_GTX8_GESTURE)   	+= goodix_ts_gesture.o
obj-$(CONFIG_TOUCHSCREEN_GOODIX_GTX8_TOOLS)     	+= goodix_ts_tools.o
obj-$(CONFIG_TOUCHSCREEN_GOODIX_GTX8)     		+= test_core/
