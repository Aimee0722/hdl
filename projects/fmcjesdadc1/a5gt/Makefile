####################################################################################
####################################################################################
## Copyright 2011(c) Analog Devices, Inc.
## Auto-generated, do not modify!
####################################################################################
####################################################################################

ifeq ($(MMU),)
  MMU := 1
endif

export ALT_NIOS_MMU_ENABLED := $(MMU)

M_DEPS += system_top.v
M_DEPS += system_qsys.tcl
M_DEPS += system_project.tcl
M_DEPS += system_constr.sdc
M_DEPS += ../common/fmcjesdadc1_spi.v
M_DEPS += ../common/fmcjesdadc1_qsys.tcl
M_DEPS += ../../scripts/adi_tquest.tcl
M_DEPS += ../../scripts/adi_env.tcl
M_DEPS += ../../common/altera/sys_gen.tcl
M_DEPS += ../../common/a5gt/a5gt_system_qsys.tcl
M_DEPS += ../../common/a5gt/a5gt_system_assign.tcl
M_DEPS += ../../../library/common/ad_sysref_gen.v
M_DEPS += ../../../library/altera/avl_adxcvr/avl_adxcvr_hw.tcl
M_DEPS += ../../../library/altera/axi_adxcvr/axi_adxcvr.v
M_DEPS += ../../../library/altera/axi_adxcvr/axi_adxcvr_hw.tcl
M_DEPS += ../../../library/altera/axi_adxcvr/axi_adxcvr_up.v
M_DEPS += ../../../library/axi_ad9250/axi_ad9250.v
M_DEPS += ../../../library/axi_ad9250/axi_ad9250_channel.v
M_DEPS += ../../../library/axi_ad9250/axi_ad9250_hw.tcl
M_DEPS += ../../../library/axi_ad9250/axi_ad9250_if.v
M_DEPS += ../../../library/axi_ad9250/axi_ad9250_pnmon.v
M_DEPS += ../../../library/axi_dmac/2d_transfer.v
M_DEPS += ../../../library/axi_dmac/address_generator.v
M_DEPS += ../../../library/axi_dmac/axi_dmac.v
M_DEPS += ../../../library/axi_dmac/axi_dmac_constr.sdc
M_DEPS += ../../../library/axi_dmac/axi_dmac_hw.tcl
M_DEPS += ../../../library/axi_dmac/axi_register_slice.v
M_DEPS += ../../../library/axi_dmac/data_mover.v
M_DEPS += ../../../library/axi_dmac/dest_axi_mm.v
M_DEPS += ../../../library/axi_dmac/dest_axi_stream.v
M_DEPS += ../../../library/axi_dmac/dest_fifo_inf.v
M_DEPS += ../../../library/axi_dmac/inc_id.h
M_DEPS += ../../../library/axi_dmac/request_arb.v
M_DEPS += ../../../library/axi_dmac/request_generator.v
M_DEPS += ../../../library/axi_dmac/resp.h
M_DEPS += ../../../library/axi_dmac/response_generator.v
M_DEPS += ../../../library/axi_dmac/response_handler.v
M_DEPS += ../../../library/axi_dmac/splitter.v
M_DEPS += ../../../library/axi_dmac/src_axi_mm.v
M_DEPS += ../../../library/axi_dmac/src_axi_stream.v
M_DEPS += ../../../library/axi_dmac/src_fifo_inf.v
M_DEPS += ../../../library/common/ad_axi_ip_constr.sdc
M_DEPS += ../../../library/common/ad_datafmt.v
M_DEPS += ../../../library/common/ad_pnmon.v
M_DEPS += ../../../library/common/ad_rst.v
M_DEPS += ../../../library/common/ad_xcvr_rx_if.v
M_DEPS += ../../../library/common/sync_bits.v
M_DEPS += ../../../library/common/sync_gray.v
M_DEPS += ../../../library/common/up_adc_channel.v
M_DEPS += ../../../library/common/up_adc_common.v
M_DEPS += ../../../library/common/up_axi.v
M_DEPS += ../../../library/common/up_clock_mon.v
M_DEPS += ../../../library/common/up_delay_cntrl.v
M_DEPS += ../../../library/common/up_xfer_cntrl.v
M_DEPS += ../../../library/common/up_xfer_status.v
M_DEPS += ../../../library/scripts/adi_env.tcl
M_DEPS += ../../../library/scripts/adi_ip_alt.tcl
M_DEPS += ../../../library/util_axis_fifo/address_gray.v
M_DEPS += ../../../library/util_axis_fifo/address_gray_pipelined.v
M_DEPS += ../../../library/util_axis_fifo/address_sync.v
M_DEPS += ../../../library/util_axis_fifo/util_axis_fifo.v
M_DEPS += ../../../library/util_axis_resize/util_axis_resize.v
M_DEPS += ../../../library/util_cpack/util_cpack.v
M_DEPS += ../../../library/util_cpack/util_cpack_dsf.v
M_DEPS += ../../../library/util_cpack/util_cpack_hw.tcl
M_DEPS += ../../../library/util_cpack/util_cpack_mux.v


M_ALTERA := quartus_sh --64bit -t 


M_FLIST += *.log
M_FLIST += *_INFO.txt
M_FLIST += *_dump.txt
M_FLIST += db
M_FLIST += *.asm.rpt
M_FLIST += *.done
M_FLIST += *.eda.rpt
M_FLIST += *.fit.*
M_FLIST += *.map.*
M_FLIST += *.sta.*
M_FLIST += *.qsf
M_FLIST += *.qpf
M_FLIST += *.qws
M_FLIST += *.sof
M_FLIST += *.cdf
M_FLIST += *.sld
M_FLIST += *.qdf
M_FLIST += hc_output
M_FLIST += system_bd
M_FLIST += hps_isw_handoff
M_FLIST += hps_sdram_*.csv
M_FLIST += *ddr3_*.csv
M_FLIST += incremental_db
M_FLIST += reconfig_mif
M_FLIST += *.sopcinfo
M_FLIST +=  *.jdi
M_FLIST += *.pin
M_FLIST += *_summary.csv
M_FLIST += *.dpf



.PHONY: all clean clean-all
all: fmcjesdadc1_a5gt.sof



clean:clean-all


clean-all:
	rm -rf $(M_FLIST)


fmcjesdadc1_a5gt.sof: $(M_DEPS)
	-rm -rf $(M_FLIST)
	$(M_ALTERA) system_project.tcl  >> fmcjesdadc1_a5gt_quartus.log 2>&1

####################################################################################
####################################################################################
