
ifeq ($(CONFIG_ARCH_PINEAPPLE),y)
dtbo-y += nxp/pineapple-nfc.dtbo \
          nxp/pineapple-nfc-atp.dtbo \
          nxp/pineapple-nfc-cdp.dtbo \
          nxp/pineapple-nfc-mtp.dtbo \
          nxp/pineapple-nfc-qrd.dtbo
endif

always-y	:= $(dtb-y) $(dtbo-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
