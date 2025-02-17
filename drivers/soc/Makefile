# SPDX-License-Identifier: GPL-2.0
#
# Makefile for the Linux Kernel SOC specific device drivers.
#

obj-$(CONFIG_ARCH_ACTIONS)	+= actions/
obj-y				+= apple/
obj-y				+= aspeed/
obj-$(CONFIG_ARCH_AT91)		+= atmel/
obj-y				+= bcm/
obj-$(CONFIG_SOC_CANAAN)	+= canaan/
obj-$(CONFIG_ARCH_DOVE)		+= dove/
obj-$(CONFIG_MACH_DOVE)		+= dove/
obj-y				+= fsl/
obj-y				+= fujitsu/
obj-$(CONFIG_ARCH_GEMINI)	+= gemini/
obj-y				+= imx/
obj-y				+= ixp4xx/
obj-$(CONFIG_SOC_XWAY)		+= lantiq/
obj-$(CONFIG_LITEX_SOC_CONTROLLER) += litex/
obj-y				+= mediatek/
obj-y				+= microchip/
obj-y				+= pxa/
obj-y				+= amlogic/
obj-y				+= qcom/
obj-y				+= renesas/
obj-y				+= rockchip/
obj-$(CONFIG_SOC_SAMSUNG)	+= samsung/
obj-$(CONFIG_SOC_SIFIVE)	+= sifive/
obj-y				+= sunxi/
obj-$(CONFIG_ARCH_TEGRA)	+= tegra/
obj-y				+= ti/
obj-$(CONFIG_ARCH_U8500)	+= ux500/
obj-$(CONFIG_PLAT_VERSATILE)	+= versatile/
obj-y				+= xilinx/

#ifdef OPLUS_FEATURE_MM_FEEDBACK
obj-$(CONFIG_OPLUS_FEATURE_MM_FEEDBACK)	+= oplus/multimedia/
#endif /* OPLUS_FEATURE_MM_FEEDBACK */

#ifdef OPLUS_FEATURE_TP_BASIC
obj-$(CONFIG_OPLUS_DEVICE_IFNO)  +=  oplus/device_info/
#endif /* OPLUS_FEATURE_TP_BASIC */

#ifdef OPLUS_TRIKEY_MAIN
obj-$(CONFIG_OPLUS_TRIKEY_MAIN)  +=  oplus/tri_state_key/
#endif /* OPLUS_TRIKEY_MAIN */

#ifdef OPLUS_FEATURE_BOOT
obj-y += oplus/boot/
#endif /* OPLUS_FEATURE_BOOT */

#ifdef OPLUS_FEATURE_MIDAS_GKI
obj-$(CONFIG_OPLUS_FEATURE_MIDAS_GKI)     += oplus/midas/
#endif

#ifdef OPLUS_FEATURE_WIFI_ROUTERBOOST
obj-$(CONFIG_OPLUS_FEATURE_WIFI_ROUTERBOOST)     += oplus/wifi/oplus_connectivity_routerboost/
#endif

#ifdef OPLUS_FEATURE_WIFI_SLA
obj-$(CONFIG_OPLUS_FEATURE_WIFI_SLA)     += oplus/wifi/oplus_connectivity_sla/
#endif

#ifdef OPLUS_FEATURE_WIFI_CAPCENTER
obj-$(CONFIG_OPLUS_FEATURE_WIFI_CAPCENTER)     += oplus/wifi/oplus_wificapcenter/
#endif

#ifdef OPLUS_FEATURE_WIFI_SMARTANTENNA
obj-$(CONFIG_OPLUS_FEATURE_WIFI_SMARTANTENNA)     += oplus/wifi/oplus_wifi_wsa/
#endif

#ifdef OPLUS_FEATURE_DATA_MODULE
obj-$(CONFIG_OPLUS_FEATURE_DATA_MODULE)     += oplus/network/data_module/
#endif

#ifdef OPLUS_FEATURE_LINKPOWER_MODULE
obj-$(CONFIG_OPLUS_FEATURE_LINKPOWER_MODULE)     += oplus/network/linkpower_module/
#endif

#ifdef OPLUS_FEATURE_APP_MONITOR
obj-$(CONFIG_OPLUS_FEATURE_APP_MONITOR)     += oplus/network/oplus_apps_monitor/
#endif

#ifdef OPLUS_FEATURE_DNS_HOOK
obj-$(CONFIG_OPLUS_FEATURE_DNS_HOOK)     += oplus/network/oplus_dns_hook/
#endif

#ifdef OPLUS_FEATURE_GAME_FIRST
obj-$(CONFIG_OPLUS_FEATURE_GAME_FIRST)     += oplus/network/oplus_game_first/
#endif

#ifdef OPLUS_FEATURE_ESIM
obj-$(CONFIG_OPLUS_FEATURE_ESIM)     += oplus/network/oplus_network_esim/
#endif

#ifdef OPLUS_FEATURE_OEM_QMI
obj-$(CONFIG_OPLUS_FEATURE_OEM_QMI)     += oplus/network/oplus_network_oem_qmi/
#endif

#ifdef OPLUS_FEATURE_SIM_DETECT
obj-$(CONFIG_OPLUS_FEATURE_SIM_DETECT)     += oplus/network/oplus_network_sim_detect/
#endif

#ifdef OPLUS_FEATURE_NETWORK_KERNEL
obj-$(CONFIG_OPLUS_FEATURE_NETWORK_KERNEL)     += oplus/network/oplus_network_tuning/
#endif

#ifdef OPLUS_FEATURE_QR_SCAN
obj-$(CONFIG_OPLUS_FEATURE_QR_SCAN)     += oplus/network/oplus_qr_scan/
#endif

#ifdef OPLUS_FEATURE_RF_CABLE_MONITOR
obj-$(CONFIG_OPLUS_FEATURE_RF_CABLE_MONITOR)     += oplus/network/oplus_rf_cable_monitor/
#endif

#ifdef OPLUS_FEATURE_DATA_EVAL
obj-$(CONFIG_OPLUS_FEATURE_DATA_EVAL)     += oplus/network/oplus_score/
#endif

#ifdef OPLUS_FEATURE_DATA_EVAL
obj-$(CONFIG_OPLUS_FEATURE_DATA_EVAL)     += oplus/network/oplus_score/
#endif

#ifdef OPLUS_FEATURE_ESTABLISH_REPORT
obj-$(CONFIG_OPLUS_FEATURE_ESTABLISH_REPORT)     += oplus/network/oplus_socket_stats_report/
#endif

#ifdef OPLUS_FEATURE_STATS_CALC
obj-$(CONFIG_OPLUS_FEATURE_STATS_CALC)     += oplus/network/oplus_stats_calc/
#endif

#ifdef OPLUS_FEATURE_VIRTUAL_NET
obj-$(CONFIG_OPLUS_FEATURE_VIRTUAL_NET)     += oplus/network/oplus_vnet/
#endif

#ifdef OPLUS_FEATURE_HANS
obj-$(CONFIG_OPLUS_FEATURE_HANS)     += oplus/network/hans/
#endif

#ifdef OPLUS_FEATURE_MDMFEATURE
obj-$(CONFIG_OPLUS_FEATURE_MDMFEATURE)     += oplus/radio/mdmfeature/
#endif

#ifdef OPLUS_FEATURE_RECORD_MDMRST
obj-$(CONFIG_OPLUS_FEATURE_RECORD_MDMRST)     += oplus/radio/mdmrst/
#endif

obj-$(CONFIG_OPLUS_FEATURE_QCOM_WATCHDOG) += oplus/boot/qcom_watchdog/
obj-y += oplus/dfr/
obj-y += oplus/dft/
obj-y     += oplus/storage/
obj-y     += oplus/sensors/

#ifdef OPLUS_SUBSYS_SLEEP_MONITOR
obj-$(CONFIG_OPLUS_SUBSYS_SLEEP_MONITOR)     += oplus/power/subsys_sleep_monitor/
#endif /* OPLUS_SUBSYS_SLEEP_MONITOR */
