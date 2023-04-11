# SPDX-License-Identifier: GPL-2.0
ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_SDMMAGPIE) += \
		sdmmagpie-idp-overlay.dtbo \

sdmmagpie-idp-overlay.dtbo-base := sdmmagpie.dtb
else
dtb-$(CONFIG_ARCH_SDMMAGPIE)	+= sdmmagpie-rumi.dtb \
	sdmmagpie-idp.dtb \
	sdmmagpie-atp.dtb \
	sdmmagpie-qrd.dtb \
	sdmmagpiep-idp.dtb \
	sdmmagpiep-atp.dtb \
	sdmmagpiep-qrd.dtb \
	sdmmagpie-external-codec-idp.dtb \
	sdmmagpie-usbc-idp.dtb \
	sdmmagpie-dual-display-idp.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_TRINKET) += \
		trinket-rumi-overlay.dtbo \
		trinket-idp-overlay.dtbo \
		trinket-qrd-overlay.dtbo \
		trinket-external-codec-idp-overlay.dtbo \
		trinket-usbc-external-codec-idp-overlay.dtbo \
		trinket-usbc-idp-overlay.dtbo \
		trinket-dp-idp-overlay.dtbo \
		trinket-facepay-overlay.dtbo \
		trinket-iot-idp-overlay.dtbo \
		trinketp-iot-idp-overlay.dtbo \
		trinket-iot-external-codec-idp-overlay.dtbo \
		trinketp-iot-external-codec-idp-overlay.dtbo \
		trinket-iot-usbc-external-codec-idp-overlay.dtbo \
		trinketp-iot-usbc-external-codec-idp-overlay.dtbo \
		trinket-iot-usbc-idp-overlay.dtbo \
		trinketp-iot-usbc-idp-overlay.dtbo \
		trinket-iot-dp-idp-overlay.dtbo \
		trinketp-iot-dp-idp-overlay.dtbo

trinket-rumi-overlay.dtbo-base := trinket.dtb
trinket-idp-overlay.dtbo-base := trinket.dtb
trinket-qrd-overlay.dtbo-base := trinket.dtb
trinket-external-codec-idp-overlay.dtbo-base := trinket.dtb
trinket-usbc-external-codec-idp-overlay.dtbo-base := trinket.dtb
trinket-usbc-idp-overlay.dtbo-base := trinket.dtb
trinket-dp-idp-overlay.dtbo-base := trinket.dtb
trinket-facepay-overlay.dtbo-base := trinket-iot.dtb
trinket-iot-idp-overlay.dtbo-base := trinket-iot.dtb
trinketp-iot-idp-overlay.dtbo-base := trinketp-iot.dtb
trinket-iot-external-codec-idp-overlay.dtbo-base := trinket-iot.dtb
trinketp-iot-external-codec-idp-overlay.dtbo-base := trinketp-iot.dtb
trinket-iot-usbc-external-codec-idp-overlay.dtbo-base := trinket-iot.dtb
trinketp-iot-usbc-external-codec-idp-overlay.dtbo-base := trinketp-iot.dtb
trinket-iot-usbc-idp-overlay.dtbo-base := trinket-iot.dtb
trinketp-iot-usbc-idp-overlay.dtbo-base := trinketp-iot.dtb
trinket-iot-dp-idp-overlay.dtbo-base := trinket-iot.dtb
trinketp-iot-dp-idp-overlay.dtbo-base := trinketp-iot.dtb
else
dtb-$(CONFIG_ARCH_TRINKET)	+= trinket-rumi.dtb \
	trinket-idp.dtb \
	trinket-qrd.dtb \
	trinket-external-codec-idp.dtb \
	trinket-usbc-external-codec-idp.dtb \
	trinket-usbc-idp.dtb \
	trinket-dp-idp.dtb \
	trinket-iot-idp.dtb \
	trinketp-iot-idp.dtb \
	trinket-iot-external-codec-idp.dtb \
	trinketp-iot-external-codec-idp.dtb \
	trinket-iot-usbc-external-codec-idp.dtb \
	trinketp-iot-usbc-external-codec-idp.dtb \
	trinket-iot-usbc-idp.dtb \
	trinketp-iot-usbc-idp.dtb \
	trinket-iot-dp-idp.dtb \
	trinketp-iot-dp-idp.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_ATOLL) += \
		atoll-idp-overlay.dtbo\
		atoll-atp-overlay.dtbo\
		atoll-qrd-overlay.dtbo\
		atoll-wcd937x-idp-overlay.dtbo\
		atoll-usbc-idp-overlay.dtbo\
		atoll-rumi-overlay.dtbo\
		atollp-idp-overlay.dtbo\
		atollp-atp-overlay.dtbo\
		atollp-qrd-overlay.dtbo\
		atoll-ab-idp-overlay.dtbo\
		atoll-ab-atp-overlay.dtbo\
		atoll-ab-qrd-overlay.dtbo

atoll-idp-overlay.dtbo-base := atoll.dtb
atoll-atp-overlay.dtbo-base := atoll.dtb
atoll-qrd-overlay.dtbo-base := atoll.dtb
atoll-rumi-overlay.dtbo-base := atoll.dtb
atoll-wcd937x-idp-overlay.dtbo-base := atoll.dtb
atoll-usbc-idp-overlay.dtbo-base := atoll.dtb
atollp-idp-overlay.dtbo-base := atollp.dtb
atollp-atp-overlay.dtbo-base := atollp.dtb
atollp-qrd-overlay.dtbo-base := atollp.dtb
atoll-ab-idp-overlay.dtbo-base := atoll-ab.dtb
atoll-ab-atp-overlay.dtbo-base := atoll-ab.dtb
atoll-ab-qrd-overlay.dtbo-base := atoll-ab.dtb
else
dtb-$(CONFIG_ARCH_ATOLL)	+= atoll-idp.dtb\
	atoll-atp.dtb\
	atoll-qrd.dtb\
	atoll-wcd937x-idp.dtb\
	atoll-usbc-idp.dtb\
	atoll-rumi.dtb\
	atollp-idp.dtb\
	atollp-atp.dtb\
	atollp-qrd.dtb\
	atoll-ab-idp.dtb\
	atoll-ab-atp.dtb\
	atoll-ab-qrd.dtb
endif

dtb-$(CONFIG_ARCH_SDXPRAIRIE) += sdxprairie-rumi.dtb \
	sdxprairie-cdp.dtb \
	sdxprairie-cdp-cpe.dtb \
	sdxprairie-cdp-v1.1-cpe.dtb \
	sdxprairie-cdp-256.dtb \
	sdxprairie-dsda-cdp.dtb \
	sdxprairie-v2-dsda-cdp.dtb \
	sdxprairie-v2-cdp.dtb \
	sdxprairie-mtp.dtb \
	sdxprairie-mtp-aqc.dtb \
	sdxprairie-mtp-cpe.dtb \
	sdxprairie-mtp-v1.1.dtb \
	sdxprairie-mtp-v1.1-cpe.dtb \
	sdxprairie-mtp-256.dtb \
	sdxprairie-mtp-le-cpe.dtb \
	sdxprairie-pcie-ep-mtp.dtb \
	sdxprairie-dsda-mtp.dtb \
	sdxprairie-v2-mtp.dtb \
	sdxprairie-v2-mtp-cpe.dtb \
	sdxprairie-v2-pcie-ep-mtp.dtb \
	sdxprairie-v2-mtp-v1.1-cpe.dtb \
	sdxprairie-v2-mtp-v1.1.dtb \
	sdxprairie-v2-mtp-le-cpe.dtb \
	sdxprairie-v2-mtp-au-dsda.dtb \
	sa515m-v2-ttp.dtb \
	sa515m-v2-ttp-usb-ep.dtb \
	sa515m-v2-ttp-pcie-ep.dtb \
	sa515m-v2-ttp-flashless-usb-ep.dtb \
	sa515m-v2-ttp-flashless-pcie-ep.dtb \
	sa515m-v2-ttp-emmc.dtb \
	sa515m-ccard.dtb \
	sa515m-ccard-pcie-ep.dtb \
	sa515m-ccard-usb-ep.dtb \
	sa515m-ccard-eth-ep.dtb \
	sa515m-v2-ccard-flashless-pcie-ep.dtb \
	sa515m-v2-ccard-flashless-usb-ep.dtb \
	sa515m-v2-ccard.dtb \
	sa515m-v2-ccard-pcie-ep.dtb \
	sa515m-v2-ccard-usb-ep.dtb \
	sa515m-v2-ccard-eth-ep.dtb \
	sa515m-v2-ccard-eth-phy-ep.dtb

dtb-$(CONFIG_ARCH_MDM9607) += mdm9607-cdp.dtb \
        mdm9607-mtp.dtb \
	mdm9607-rcm.dtb \

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_SDM660) += \
		sdm660-mtp-external-codec-overlay.dtbo \
		sdm660-mtp-internal-codec-overlay.dtbo \
		sdm660-cdp-external-codec-overlay.dtbo \
		sdm660-cdp-internal-codec-overlay.dtbo \
		sdm660-qrd-external-codec-overlay.dtbo \
		sdm660-rcm-external-codec-overlay.dtbo \
		sdm660-rcm-internal-codec-overlay.dtbo \
		sda660-mtp-external-codec-overlay.dtbo \
		sda660-cdp-external-codec-overlay.dtbo \
		sda660-rcm-external-codec-overlay.dtbo \
		sdm660-usbc-audio-mtp-overlay.dtbo

sdm660-mtp-external-codec-overlay.dtbo-base := sdm660-pm660l.dtb

sdm660-mtp-internal-codec-overlay.dtbo-base := sdm660-pm660l.dtb

sdm660-cdp-external-codec-overlay.dtbo-base := sdm660-pm660l.dtb

sdm660-cdp-internal-codec-overlay.dtbo-base := sdm660-pm660l.dtb

sdm660-qrd-external-codec-overlay.dtbo-base := sdm660-pm660l.dtb

sdm660-rcm-external-codec-overlay.dtbo-base := sdm660-pm660l.dtb

sdm660-rcm-internal-codec-overlay.dtbo-base := sdm660-pm660l.dtb

sdm660-usbc-audio-mtp-overlay.dtbo-base := sdm660-pm660l.dtb

sda660-mtp-external-codec-overlay.dtbo-base := sda660-pm660l.dtb

sda660-cdp-external-codec-overlay.dtbo-base := sda660-pm660l.dtb

sda660-rcm-external-codec-overlay.dtbo-base := sda660-pm660l.dtb
else
dtb-$(CONFIG_ARCH_SDM660) += sdm660-sim.dtb \
	sdm660-internal-codec-cdp.dtb \
	sdm660-internal-codec-mtp.dtb \
	sdm660-internal-codec-rcm.dtb \
	sdm660-cdp.dtb \
	sdm660-mtp.dtb \
	sdm660-qrd.dtb \
	sdm660-rcm.dtb \
	sdm660-pm660a-cdp.dtb \
	sdm660-pm660a-mtp.dtb \
	sdm660-pm660a-qrd.dtb \
	sdm660-pm660a-rcm.dtb \
	sdm660-internal-codec-pm660a-cdp.dtb \
	sdm660-internal-codec-pm660a-mtp.dtb \
	sdm660-internal-codec-pm660a-rcm.dtb \
	sdm660-pm660a-sim.dtb \
	sda660-cdp.dtb \
	sda660-mtp.dtb \
	sda660-rcm.dtb \
	sda660-pm660a-cdp.dtb \
	sda660-pm660a-mtp.dtb \
	sda660-pm660a-rcm.dtb \
	sda660-pm660a-qrd-hdk.dtb \
	sdm660-headset-jacktype-no-cdp.dtb \
	sdm660-headset-jacktype-no-rcm.dtb \
	sdm660-pm660a-headset-jacktype-no-cdp.dtb \
	sdm660-pm660a-headset-jacktype-no-rcm.dtb \
	sdm660-usbc-audio-mtp.dtb \
	sdm660-usbc-audio-rcm.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_SDM429W) += sdm429-wtp-overlay.dtbo\
		sdm429-wdp-overlay.dtbo\
		sdm429-bg-dvt2-wtp-overlay.dtbo\
		sda429-wdp-overlay.dtbo\
		sda429-wtp-overlay.dtbo\
		sda429-bg-dvt2-wtp-overlay.dtbo

sdm429-wtp-overlay.dtbo-base := sdm429.dtb
sdm429-wdp-overlay.dtbo-base := sdm429.dtb
sdm429-bg-dvt2-wtp-overlay.dtbo-base := sdm429.dtb
sda429-wtp-overlay.dtbo-base := sda429.dtb
sda429-wdp-overlay.dtbo-base := sda429.dtb
sda429-bg-dvt2-wtp-overlay.dtbo-base := sda429.dtb
else
dtb-$(CONFIG_ARCH_SDM429W) += sdm429-wtp.dtb\
	sdm429-wdp.dtb\
	sdm429-bg-dvt2-wtp.dtb\
	sda429-wtp.dtb\
	sda429-wdp.dtb\
	sda429-bg-dvt2-wtp.dtb
endif

endif

ifeq ($(CONFIG_ARM64),y)
always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
else
targets += dtbs
targets += $(addprefix ../, $(dtb-y))

$(obj)/../%.dtb: $(src)/%.dts FORCE
	$(call if_changed_dep,dtc)

dtbs: $(addprefix $(obj)/../,$(dtb-y))
endif
clean-files	:= *.dtb *.dtbo
