# Multithreaded + multi-processing makefile for:
#    Linux pfe22 3.10.0-1160.83.1.1chaos.ch6.x86_64 #1 SMP Tue Jan 24 17:36:15 PST 2023 x86_64 x86_64 x86_64 GNU/Linux
# This makefile was generated automatically on
#    Fri Feb 24 19:42:13 PST 2023
# by the command:
#    ../../../tools/genmake2 '-mods=../code_geos_bulk ../code' -mpi -of=../../../tools/build_options/linux_amd64_ifort+mpi_ice_nas_1
# executed by:
#    afahad@pfe22:/nobackup/afahad/GEOSMIT-Jason/MITgcm_67q/verification/global_ocean.cs32x15/build_geos_bulk
#
# OPTFILE="../../../tools/build_options/linux_amd64_ifort+mpi_ice_nas_1"
#
# BUILDDIR     : Directory where object files are written
# SOURCEDIRS   : Directories containing the source (.F) files
# INCLUDEDIRS  : Directories containing the header-source (.h) files
# EXEDIR       : Directory where executable that is generated is written
# EXECUTABLE   : Full path of executable binary
#
# CPP          : C-preprocessor command
# INCLUDES     : Directories searched for header files
# DEFINES      : Macro definitions for CPP
# MAKEDEPEND   : Dependency generator
# FC           : Fortran compiler command
# FFLAGS       : Configuration/debugging options for FC
# FOPTIM       : Optimization options for FC
# LINK         : Command for link editor program
# LIBS         : Library flags /or/ additional optimization/debugging flags

ROOTDIR     = ../../..
BUILDDIR    = .
SOURCEDIRS  =  ../code_geos_bulk ../code $(ROOTDIR)/pkg/bulk_force $(ROOTDIR)/pkg/debug $(ROOTDIR)/pkg/diagnostics $(ROOTDIR)/pkg/exch2 $(ROOTDIR)/pkg/exf $(ROOTDIR)/pkg/generic_advdiff $(ROOTDIR)/pkg/gmredi $(ROOTDIR)/pkg/mdsio $(ROOTDIR)/pkg/mnc $(ROOTDIR)/pkg/mom_common $(ROOTDIR)/pkg/mom_fluxform $(ROOTDIR)/pkg/mom_vecinv $(ROOTDIR)/pkg/monitor $(ROOTDIR)/pkg/rw $(ROOTDIR)/pkg/seaice $(ROOTDIR)/pkg/thsice $(ROOTDIR)/pkg/timeave $(ROOTDIR)/pkg/cal $(ROOTDIR)/eesupp/src $(ROOTDIR)/model/src
INCLUDEDIRS =  ../code_geos_bulk ../code $(ROOTDIR)/pkg/bulk_force $(ROOTDIR)/pkg/debug $(ROOTDIR)/pkg/diagnostics $(ROOTDIR)/pkg/exch2 $(ROOTDIR)/pkg/exf $(ROOTDIR)/pkg/generic_advdiff $(ROOTDIR)/pkg/gmredi $(ROOTDIR)/pkg/mdsio $(ROOTDIR)/pkg/mnc $(ROOTDIR)/pkg/mom_common $(ROOTDIR)/pkg/mom_fluxform $(ROOTDIR)/pkg/mom_vecinv $(ROOTDIR)/pkg/monitor $(ROOTDIR)/pkg/rw $(ROOTDIR)/pkg/seaice $(ROOTDIR)/pkg/thsice $(ROOTDIR)/pkg/timeave $(ROOTDIR)/pkg/cal $(ROOTDIR)/eesupp/inc $(ROOTDIR)/model/inc
EXEDIR      = .
EXECUTABLE  = $(EXEDIR)/mitgcmuv
TOOLSDIR    = $(ROOTDIR)/tools
OADTOOLS    = 

#eh3  new defines for the adjoint work
AUTODIFF    = $(ROOTDIR)/pkg/autodiff
EXE_AD      = mitgcmuv_ad
EXE_FTL     = mitgcmuv_ftl
EXE_SVD     = mitgcmuv_svd

ENABLED_PACKAGES =  -DALLOW_BULK_FORCE -DALLOW_DEBUG -DALLOW_DIAGNOSTICS -DALLOW_EXCH2 -DALLOW_EXF -DALLOW_GENERIC_ADVDIFF -DALLOW_GMREDI -DALLOW_MDSIO -DALLOW_MNC -DALLOW_MOM_COMMON -DALLOW_MOM_FLUXFORM -DALLOW_MOM_VECINV -DALLOW_MONITOR -DALLOW_RW -DALLOW_SEAICE -DALLOW_THSICE -DALLOW_TIMEAVE -DALLOW_CAL
DISABLED_PACKAGES =  -UALLOW_ADMTLM -UALLOW_AIM_V23 -UALLOW_ATM2D -UALLOW_ATM_COMMON -UALLOW_ATM_COMPON_INTERF -UALLOW_ATM_OCN_COUPLER -UALLOW_ATM_PHYS -UALLOW_AUTODIFF -UALLOW_BBL -UALLOW_BLING -UALLOW_CD_CODE -UALLOW_CFC -UALLOW_CHEAPAML -UALLOW_CHRONOS -UALLOW_COMPON_COMMUNIC -UALLOW_COST -UALLOW_CTRL -UALLOW_DIC -UALLOW_DOWN_SLOPE -UALLOW_EBM -UALLOW_ECCO -UALLOW_EMBED_FILES -UALLOW_FIZHI -UALLOW_FLT -UALLOW_FRAZIL -UALLOW_GCHEM -UALLOW_GGL90 -UALLOW_GRDCHK -UALLOW_GRIDALT -UALLOW_ICEFRONT -UALLOW_KL10 -UALLOW_KPP -UALLOW_LAND -UALLOW_LAYERS -UALLOW_LONGSTEP -UALLOW_MATRIX -UALLOW_MY82 -UALLOW_MYPACKAGE -UALLOW_OBCS -UALLOW_OCN_COMPON_INTERF -UALLOW_OFFLINE -UALLOW_OPENAD -UALLOW_OPPS -UALLOW_PP81 -UALLOW_PROFILES -UALLOW_PTRACERS -UALLOW_RBCS -UALLOW_REGRID -UALLOW_RUNCLOCK -UALLOW_SALT_PLUME -UALLOW_SBO -UALLOW_SHAP_FILT -UALLOW_SHELFICE -UALLOW_SHOWFLOPS -UALLOW_SMOOTH -UALLOW_SPHERE -UALLOW_STREAMICE -UALLOW_ZONAL_FILT

# These files are created by Makefile
SPECIAL_FILES = PACKAGES_CONFIG.h AD_CONFIG.h FC_NAMEMANGLE.h BUILD_INFO.h
EMBEDDED_FILES = 
# Unix ln (link)
LN = ln -s
# Dependency generator
MAKEDEPEND = $(TOOLSDIR)/xmakedepend
# Special preprocessor (KAP on DECs, FPP on Crays)
KPP = 
# Fortran compiler
FC = ifort
# Fortran compiler
F90C = 
# C compiler
CC = icc
# Link editor
LINK = ifort -shared-intel

# Defines for CPP
DEFINES = -DWORDLENGTH=4 -DINTEL_COMMITQQ -DALLOW_USE_MPI -DHAVE_SYSTEM -DHAVE_FDATE -DHAVE_ETIME_FCT -DHAVE_CLOC -DHAVE_SETRLSTK -DHAVE_SIGREG -DHAVE_STAT -DHAVE_NETCDF -DHAVE_FLUSH 
# Includes for CPP
INCLUDES =  -I/nasa/hpe/mpt/2.25_rhel79/include -I/nasa/netcdf/4.4.1.1_mpt/include
# default CPP includes for makedepend
CPPINCLUDES =  -I/nasa/netcdf/4.4.1.1_mpt/include -I/nasa/hdf5/1.8.18_mpt/include -I/nasa/szip/2.1.1/include -I/nasa/hdf4/4.2.12/include -I/nasa/hpe/mpt/2.25_rhel79/include -I/nasa/intel/Compiler/2020.4.304/compilers_and_libraries_2020.4.304/linux/ipp/include -I/nasa/intel/Compiler/2020.4.304/compilers_and_libraries_2020.4.304/linux/mkl/include -I/nasa/intel/Compiler/2020.4.304/compilers_and_libraries_2020.4.304/linux/pstl/include -I/nasa/intel/Compiler/2020.4.304/compilers_and_libraries_2020.4.304/linux/pstl/stdlib -I/nasa/intel/Compiler/2020.4.304/compilers_and_libraries_2020.4.304/linux/tbb/include -I/nasa/intel/Compiler/2020.4.304/compilers_and_libraries_2020.4.304/linux/daal/include -I/usr/lib/gcc/x86_64-redhat-linux/4.8.5/include -I/usr/local/include -I/usr/include
# Flags for KPP
KFLAGS1 = 
KFLAGS2 = 
# Optim./debug for FC
FFLAGS =  -convert big_endian -assume byterecl -fPIC -W0 -WB
FOPTIM = -O2 -ipo -fp-model precise -align -axCORE-AVX2 -xSSE4.2 -traceback -ftz 
# Optim./debug for FC
F90FLAGS =  -convert big_endian -assume byterecl -fPIC -W0 -WB
F90OPTIM = -O2 -ipo -fp-model precise -align -axCORE-AVX2 -xSSE4.2 -traceback -ftz
F90FIXEDFORMAT = -fixed -Tf
# Flags for CC
CFLAGS = -O0 -fPIC
# Files that should not be optimized
NOOPTFILES = seaice_growth.F calc_oce_mxlayer.F fizhi_lsm.F fizhi_clockstuff.F ini_parms.F obcs_init_fixed.F
NOOPTFLAGS = -O0
# Flags and libraries needed for linking
LIBS =  -L/nasa/hpe/mpt/2.25_rhel79/lib -lmpi -L/nasa/netcdf/4.4.1.1_mpt/lib -lnetcdff -lnetcdf
# Name of the makefile
MAKEFILE = Makefile
# Name of the make program
MAKE = make

F77_SRC_FILES =  \
 exf_geos_bulkf.F \
 exf_getforcing.F \
 bulkf_ave.F \
 bulkf_fields_load.F \
 bulkf_flux_adjust.F \
 bulkf_forcing.F \
 bulkf_formula_aim.F \
 bulkf_formula_lanl.F \
 bulkf_formula_lay.F \
 bulkf_init_varia.F \
 bulkf_output.F \
 bulkf_readparms.F \
 bulkf_sh2rh_aim.F \
 chksum_tiled.F \
 debug_call.F \
 debug_cs_corner_uv.F \
 debug_enter.F \
 debug_fld_stats_rl.F \
 debug_fld_stats_rs.F \
 debug_leave.F \
 debug_msg.F \
 debug_stats_rl.F \
 debug_stats_rs.F \
 fill_in_corners_rl.F \
 write_fullarray_rl.F \
 write_fullarray_rs.F \
 diag_calc_psivel.F \
 diag_cg2d.F \
 diag_vegtile_fill.F \
 diagnostics_addtolist.F \
 diagnostics_calc_phivel.F \
 diagnostics_check.F \
 diagnostics_clear.F \
 diagnostics_fill.F \
 diagnostics_fill_field.F \
 diagnostics_fill_rs.F \
 diagnostics_fill_state.F \
 diagnostics_fract_fill.F \
 diagnostics_ini_io.F \
 diagnostics_init_early.F \
 diagnostics_init_fixed.F \
 diagnostics_init_varia.F \
 diagnostics_interp_p2p.F \
 diagnostics_interp_vert.F \
 diagnostics_is_on.F \
 diagnostics_list_check.F \
 diagnostics_main_init.F \
 diagnostics_mnc_out.F \
 diagnostics_out.F \
 diagnostics_read_pickup.F \
 diagnostics_readparms.F \
 diagnostics_scale_fill.F \
 diagnostics_scale_fill_rs.F \
 diagnostics_set_calc.F \
 diagnostics_set_levels.F \
 diagnostics_set_pointers.F \
 diagnostics_setdiag.F \
 diagnostics_status_error.F \
 diagnostics_sum_levels.F \
 diagnostics_summary.F \
 diagnostics_switch_onoff.F \
 diagnostics_utils.F \
 diagnostics_write.F \
 diagnostics_write_adj.F \
 diagnostics_write_pickup.F \
 diagstats_ascii_out.F \
 diagstats_calc.F \
 diagstats_clear.F \
 diagstats_close_io.F \
 diagstats_fill.F \
 diagstats_global.F \
 diagstats_ini_io.F \
 diagstats_local.F \
 diagstats_mnc_out.F \
 diagstats_others_calc.F \
 diagstats_output.F \
 diagstats_set_pointers.F \
 diagstats_set_regions.F \
 diagstats_setdiag.F \
 exch2_3d_r4.F \
 exch2_3d_r8.F \
 exch2_3d_rl.F \
 exch2_3d_rs.F \
 exch2_ad_get_r41.F \
 exch2_ad_get_r42.F \
 exch2_ad_get_r81.F \
 exch2_ad_get_r82.F \
 exch2_ad_get_rl1.F \
 exch2_ad_get_rl2.F \
 exch2_ad_get_rs1.F \
 exch2_ad_get_rs2.F \
 exch2_ad_put_r41.F \
 exch2_ad_put_r42.F \
 exch2_ad_put_r81.F \
 exch2_ad_put_r82.F \
 exch2_ad_put_rl1.F \
 exch2_ad_put_rl2.F \
 exch2_ad_put_rs1.F \
 exch2_ad_put_rs2.F \
 exch2_check_depths.F \
 exch2_get_r41.F \
 exch2_get_r42.F \
 exch2_get_r81.F \
 exch2_get_r82.F \
 exch2_get_rl1.F \
 exch2_get_rl2.F \
 exch2_get_rs1.F \
 exch2_get_rs2.F \
 exch2_get_scal_bounds.F \
 exch2_get_uv_bounds.F \
 exch2_put_r41.F \
 exch2_put_r42.F \
 exch2_put_r81.F \
 exch2_put_r82.F \
 exch2_put_rl1.F \
 exch2_put_rl2.F \
 exch2_put_rs1.F \
 exch2_put_rs2.F \
 exch2_r41_cube.F \
 exch2_r41_cube_ad.F \
 exch2_r42_cube.F \
 exch2_r42_cube_ad.F \
 exch2_r81_cube.F \
 exch2_r81_cube_ad.F \
 exch2_r82_cube.F \
 exch2_r82_cube_ad.F \
 exch2_recv_r41.F \
 exch2_recv_r42.F \
 exch2_recv_r81.F \
 exch2_recv_r82.F \
 exch2_recv_rl1.F \
 exch2_recv_rl2.F \
 exch2_recv_rs1.F \
 exch2_recv_rs2.F \
 exch2_rl1_cube.F \
 exch2_rl1_cube_ad.F \
 exch2_rl2_cube.F \
 exch2_rl2_cube_ad.F \
 exch2_rs1_cube.F \
 exch2_rs1_cube_ad.F \
 exch2_rs2_cube.F \
 exch2_rs2_cube_ad.F \
 exch2_s3d_r4.F \
 exch2_s3d_r8.F \
 exch2_s3d_rl.F \
 exch2_s3d_rs.F \
 exch2_send_r41.F \
 exch2_send_r42.F \
 exch2_send_r81.F \
 exch2_send_r82.F \
 exch2_send_rl1.F \
 exch2_send_rl2.F \
 exch2_send_rs1.F \
 exch2_send_rs2.F \
 exch2_sm_3d_r4.F \
 exch2_sm_3d_r8.F \
 exch2_sm_3d_rl.F \
 exch2_sm_3d_rs.F \
 exch2_uv_3d_r4.F \
 exch2_uv_3d_r8.F \
 exch2_uv_3d_rl.F \
 exch2_uv_3d_rs.F \
 exch2_uv_agrid_3d_r4.F \
 exch2_uv_agrid_3d_r8.F \
 exch2_uv_agrid_3d_rl.F \
 exch2_uv_agrid_3d_rs.F \
 exch2_uv_bgrid_3d_r4.F \
 exch2_uv_bgrid_3d_r8.F \
 exch2_uv_bgrid_3d_rl.F \
 exch2_uv_bgrid_3d_rs.F \
 exch2_uv_cgrid_3d_r4.F \
 exch2_uv_cgrid_3d_r8.F \
 exch2_uv_cgrid_3d_rl.F \
 exch2_uv_cgrid_3d_rs.F \
 exch2_uv_dgrid_3d_r4.F \
 exch2_uv_dgrid_3d_r8.F \
 exch2_uv_dgrid_3d_rl.F \
 exch2_uv_dgrid_3d_rs.F \
 exch2_z_3d_r4.F \
 exch2_z_3d_r8.F \
 exch2_z_3d_rl.F \
 exch2_z_3d_rs.F \
 w2_cumulsum_z_tile.F \
 w2_e2setup.F \
 w2_eeboot.F \
 w2_map_procs.F \
 w2_print_comm_sequence.F \
 w2_print_e2setup.F \
 w2_readparms.F \
 w2_set_cs6_facets.F \
 w2_set_f2f_index.F \
 w2_set_gen_facets.F \
 w2_set_map_cumsum.F \
 w2_set_map_tiles.F \
 w2_set_myown_facets.F \
 w2_set_single_facet.F \
 w2_set_tile2tiles.F \
 exf_ad_dump.F \
 exf_adjoint_snapshots.F \
 exf_adjoint_snapshots__g.F \
 exf_adjoint_snapshots_ad.F \
 exf_bulkformulae.F \
 exf_check.F \
 exf_check_range.F \
 exf_diagnostics_fill.F \
 exf_diagnostics_init.F \
 exf_filter_rl.F \
 exf_getclim.F \
 exf_getffield_start.F \
 exf_getffieldrec.F \
 exf_getffields.F \
 exf_getfield_start.F \
 exf_getsurfacefluxes.F \
 exf_getyearlyfieldname.F \
 exf_init_fixed.F \
 exf_init_fld.F \
 exf_init_interp.F \
 exf_init_varia.F \
 exf_interp.F \
 exf_interp_read.F \
 exf_interp_uv.F \
 exf_interpolate.F \
 exf_mapfields.F \
 exf_monitor.F \
 exf_monitor_ad.F \
 exf_radiation.F \
 exf_readparms.F \
 exf_set_fld.F \
 exf_set_gen.F \
 exf_set_obcs.F \
 exf_set_uv.F \
 exf_summary.F \
 exf_swapffields.F \
 exf_weight_sfx_diags.F \
 exf_wind.F \
 exf_zenithangle.F \
 exf_zenithangle_table.F \
 gad_advection.F \
 gad_advscheme.F \
 gad_biharm_r.F \
 gad_biharm_x.F \
 gad_biharm_y.F \
 gad_c2_adv_r.F \
 gad_c2_adv_x.F \
 gad_c2_adv_y.F \
 gad_c2_impl_r.F \
 gad_c4_adv_r.F \
 gad_c4_adv_x.F \
 gad_c4_adv_y.F \
 gad_calc_rhs.F \
 gad_check.F \
 gad_del2.F \
 gad_diagnostics_init.F \
 gad_diagnostics_state.F \
 gad_diff_r.F \
 gad_diff_x.F \
 gad_diff_y.F \
 gad_dst2u1_adv_r.F \
 gad_dst2u1_adv_x.F \
 gad_dst2u1_adv_y.F \
 gad_dst2u1_impl_r.F \
 gad_dst3_adv_r.F \
 gad_dst3_adv_x.F \
 gad_dst3_adv_y.F \
 gad_dst3fl_adv_r.F \
 gad_dst3fl_adv_x.F \
 gad_dst3fl_adv_y.F \
 gad_dst3fl_impl_r.F \
 gad_exch_som.F \
 gad_fluxlimit_adv_r.F \
 gad_fluxlimit_adv_x.F \
 gad_fluxlimit_adv_y.F \
 gad_fluxlimit_impl_r.F \
 gad_grad_x.F \
 gad_grad_y.F \
 gad_implicit_r.F \
 gad_init_fixed.F \
 gad_init_varia.F \
 gad_os7mp_adv_r.F \
 gad_os7mp_adv_x.F \
 gad_os7mp_adv_y.F \
 gad_osc_hat_r.F \
 gad_osc_hat_x.F \
 gad_osc_hat_y.F \
 gad_osc_mul_r.F \
 gad_osc_mul_x.F \
 gad_osc_mul_y.F \
 gad_plm_fun.F \
 gad_ppm_adv_r.F \
 gad_ppm_adv_x.F \
 gad_ppm_adv_y.F \
 gad_ppm_flx_r.F \
 gad_ppm_flx_x.F \
 gad_ppm_flx_y.F \
 gad_ppm_fun.F \
 gad_ppm_hat_r.F \
 gad_ppm_hat_x.F \
 gad_ppm_hat_y.F \
 gad_ppm_p3e_r.F \
 gad_ppm_p3e_x.F \
 gad_ppm_p3e_y.F \
 gad_pqm_adv_r.F \
 gad_pqm_adv_x.F \
 gad_pqm_adv_y.F \
 gad_pqm_flx_r.F \
 gad_pqm_flx_x.F \
 gad_pqm_flx_y.F \
 gad_pqm_fun.F \
 gad_pqm_hat_r.F \
 gad_pqm_hat_x.F \
 gad_pqm_hat_y.F \
 gad_pqm_p5e_r.F \
 gad_pqm_p5e_x.F \
 gad_pqm_p5e_y.F \
 gad_read_pickup.F \
 gad_som_adv_r.F \
 gad_som_adv_x.F \
 gad_som_adv_y.F \
 gad_som_advect.F \
 gad_som_exchanges.F \
 gad_som_fill_cs_corner.F \
 gad_som_lim_r.F \
 gad_som_prep_cs_corner.F \
 gad_u3_adv_r.F \
 gad_u3_adv_x.F \
 gad_u3_adv_y.F \
 gad_u3c4_impl_r.F \
 gad_write_pickup.F \
 salt_fill.F \
 gmredi_calc_diff.F \
 gmredi_calc_eigs.F \
 gmredi_calc_psi_b.F \
 gmredi_calc_psi_bvp.F \
 gmredi_calc_qgleith.F \
 gmredi_calc_tensor.F \
 gmredi_calc_urms.F \
 gmredi_check.F \
 gmredi_diagnostics_fill.F \
 gmredi_diagnostics_impl.F \
 gmredi_diagnostics_init.F \
 gmredi_do_exch.F \
 gmredi_init_fixed.F \
 gmredi_init_varia.F \
 gmredi_k3d.F \
 gmredi_mnc_init.F \
 gmredi_output.F \
 gmredi_read_pickup.F \
 gmredi_readparms.F \
 gmredi_residual_flow.F \
 gmredi_rtransport.F \
 gmredi_slope_limit.F \
 gmredi_slope_psi.F \
 gmredi_write_pickup.F \
 gmredi_xtransport.F \
 gmredi_ytransport.F \
 submeso_calc_psi.F \
 mdsio_buffertorl.F \
 mdsio_buffertors.F \
 mdsio_check4file.F \
 mdsio_facef_read.F \
 mdsio_gl.F \
 mdsio_gl_slice.F \
 mdsio_pass_r4torl.F \
 mdsio_pass_r4tors.F \
 mdsio_pass_r8torl.F \
 mdsio_pass_r8tors.F \
 mdsio_rd_rec_rl.F \
 mdsio_rd_rec_rs.F \
 mdsio_read_field.F \
 mdsio_read_meta.F \
 mdsio_read_section.F \
 mdsio_read_tape.F \
 mdsio_read_whalos.F \
 mdsio_readvec_loc.F \
 mdsio_rw_field.F \
 mdsio_rw_slice.F \
 mdsio_seg4torl.F \
 mdsio_seg4tors.F \
 mdsio_seg8torl.F \
 mdsio_seg8tors.F \
 mdsio_segxtorx_2d.F \
 mdsio_wr_metafiles.F \
 mdsio_wr_rec_rl.F \
 mdsio_wr_rec_rs.F \
 mdsio_write_field.F \
 mdsio_write_meta.F \
 mdsio_write_section.F \
 mdsio_write_tape.F \
 mdsio_write_whalos.F \
 mdsio_writelocal.F \
 mdsio_writevec_loc.F \
 MNC_CW_READWRITE_I.F \
 MNC_CW_READWRITE_RL.F \
 MNC_CW_READWRITE_RS.F \
 mnc_cw_citer.F \
 mnc_cw_cvars.F \
 mnc_cw_init.F \
 mnc_cw_missingvals.F \
 mnc_cw_model_attr.F \
 mnc_cw_udim.F \
 mnc_cw_write_grid_info.F \
 mnc_cwrapper.F \
 mnc_dim.F \
 mnc_dump.F \
 mnc_file.F \
 mnc_grid.F \
 mnc_init.F \
 mnc_readparms.F \
 mnc_update_time.F \
 mnc_utils.F \
 mnc_var.F \
 mom_calc_3d_strain.F \
 mom_calc_absvort3.F \
 mom_calc_hdiv.F \
 mom_calc_hfacz.F \
 mom_calc_ke.F \
 mom_calc_relvort3.F \
 mom_calc_smag_3d.F \
 mom_calc_strain.F \
 mom_calc_tension.F \
 mom_calc_visc.F \
 mom_diagnostics_init.F \
 mom_hdissip.F \
 mom_init_fixed.F \
 mom_quasihydrostatic.F \
 mom_u_botdrag_coeff.F \
 mom_u_coriolis_nh.F \
 mom_u_implicit_r.F \
 mom_u_metric_nh.F \
 mom_u_rviscflux.F \
 mom_u_sidedrag.F \
 mom_uv_smag_3d.F \
 mom_v_botdrag_coeff.F \
 mom_v_coriolis_nh.F \
 mom_v_implicit_r.F \
 mom_v_metric_nh.F \
 mom_v_rviscflux.F \
 mom_v_sidedrag.F \
 mom_visc_qgl_limit.F \
 mom_visc_qgl_stretch.F \
 mom_w_coriolis_nh.F \
 mom_w_metric_nh.F \
 mom_w_sidedrag.F \
 mom_w_smag_3d.F \
 mom_calc_rtrans.F \
 mom_fluxform.F \
 mom_u_adv_uu.F \
 mom_u_adv_vu.F \
 mom_u_adv_wu.F \
 mom_u_coriolis.F \
 mom_u_del2u.F \
 mom_u_metric_cylinder.F \
 mom_u_metric_sphere.F \
 mom_u_xviscflux.F \
 mom_u_yviscflux.F \
 mom_uv_boundary.F \
 mom_v_adv_uv.F \
 mom_v_adv_vv.F \
 mom_v_adv_wv.F \
 mom_v_coriolis.F \
 mom_v_del2v.F \
 mom_v_metric_cylinder.F \
 mom_v_metric_sphere.F \
 mom_v_xviscflux.F \
 mom_v_yviscflux.F \
 mom_vecinv.F \
 mom_vi_coriolis.F \
 mom_vi_del2uv.F \
 mom_vi_hdissip.F \
 mom_vi_u_coriolis.F \
 mom_vi_u_coriolis_c4.F \
 mom_vi_u_grad_ke.F \
 mom_vi_u_vertshear.F \
 mom_vi_v_coriolis.F \
 mom_vi_v_coriolis_c4.F \
 mom_vi_v_grad_ke.F \
 mom_vi_v_vertshear.F \
 mon_advcfl.F \
 mon_advcflw.F \
 mon_advcflw2.F \
 mon_calc_advcfl.F \
 mon_calc_stats_rl.F \
 mon_calc_stats_rs.F \
 mon_init.F \
 mon_ke.F \
 mon_out.F \
 mon_printstats_rl.F \
 mon_printstats_rs.F \
 mon_set_iounit.F \
 mon_set_pref.F \
 mon_solution.F \
 mon_stats_latbnd_rl.F \
 mon_stats_rl.F \
 mon_stats_rs.F \
 mon_surfcor.F \
 mon_vort3.F \
 mon_writestats_rl.F \
 mon_writestats_rs.F \
 monitor.F \
 monitor_ad.F \
 monitor_g.F \
 get_write_global_fld.F \
 read_fld_xy_rl.F \
 read_fld_xy_rs.F \
 read_fld_xyz_rl.F \
 read_fld_xyz_rs.F \
 read_glvec_rl.F \
 read_glvec_rs.F \
 read_mflds.F \
 read_rec.F \
 rw_get_suffix.F \
 set_write_global_fld.F \
 write_fld_3d_rl.F \
 write_fld_3d_rs.F \
 write_fld_s3d_rl.F \
 write_fld_s3d_rs.F \
 write_fld_xy_rl.F \
 write_fld_xy_rs.F \
 write_fld_xyz_rl.F \
 write_fld_xyz_rs.F \
 write_glvec_rl.F \
 write_glvec_rs.F \
 write_local_rl.F \
 write_local_rs.F \
 write_rec.F \
 advect.F \
 cost_ice_test.F \
 diffus.F \
 dynsolver.F \
 lsr.F \
 ostres.F \
 seaice_ad_dump.F \
 seaice_advdiff.F \
 seaice_advection.F \
 seaice_bottomdrag_coeffs.F \
 seaice_budget_ocean.F \
 seaice_calc_ice_strength.F \
 seaice_calc_lhs.F \
 seaice_calc_residual.F \
 seaice_calc_rhs.F \
 seaice_calc_strainrates.F \
 seaice_calc_stressdiv.F \
 seaice_calc_viscosities.F \
 seaice_check.F \
 seaice_check_pickup.F \
 seaice_cost_accumulate_mean.F \
 seaice_cost_areasst.F \
 seaice_cost_concentration.F \
 seaice_cost_driver.F \
 seaice_cost_export.F \
 seaice_cost_final.F \
 seaice_cost_init_fixed.F \
 seaice_cost_init_varia.F \
 seaice_cost_sensi.F \
 seaice_cost_sss.F \
 seaice_cost_sst.F \
 seaice_cost_weights.F \
 seaice_ctrl_map_ini.F \
 seaice_diagnostics_init.F \
 seaice_diagnostics_state.F \
 seaice_diffusion.F \
 seaice_do_ridging.F \
 seaice_dynsolver.F \
 seaice_evp.F \
 seaice_fake.F \
 seaice_fgmres.F \
 seaice_freedrift.F \
 seaice_get_dynforcing.F \
 seaice_growth.F \
 seaice_growth_adx.F \
 seaice_init_fixed.F \
 seaice_init_varia.F \
 seaice_itd_pickup.F \
 seaice_itd_redist.F \
 seaice_itd_remap.F \
 seaice_itd_sum.F \
 seaice_jacvec.F \
 seaice_jfnk.F \
 seaice_krylov.F \
 seaice_lsr.F \
 seaice_map_thsice.F \
 seaice_mnc_init.F \
 seaice_model.F \
 seaice_mom_advection.F \
 seaice_monitor.F \
 seaice_monitor_ad.F \
 seaice_obcs_output.F \
 seaice_ocean_stress.F \
 seaice_oceandrag_coeffs.F \
 seaice_output.F \
 seaice_preconditioner.F \
 seaice_prepare_ridging.F \
 seaice_read_pickup.F \
 seaice_readparms.F \
 seaice_reg_ridge.F \
 seaice_solve4temp.F \
 seaice_solve4temp_adx.F \
 seaice_summary.F \
 seaice_tracer_phys.F \
 seaice_turnoff_io.F \
 seaice_write_pickup.F \
 thsice_advdiff.F \
 thsice_advection.F \
 thsice_albedo.F \
 thsice_ave.F \
 thsice_balance_frw.F \
 thsice_calc_thickn.F \
 thsice_check.F \
 thsice_check_conserv.F \
 thsice_cost_driver.F \
 thsice_cost_final.F \
 thsice_cost_init_varia.F \
 thsice_cost_test.F \
 thsice_diagnostics_init.F \
 thsice_diagnostics_state.F \
 thsice_diffusion.F \
 thsice_do_advect.F \
 thsice_do_exch.F \
 thsice_extend.F \
 thsice_get_bulkf.F \
 thsice_get_exf.F \
 thsice_get_ocean.F \
 thsice_get_precip.F \
 thsice_get_velocity.F \
 thsice_impl_temp.F \
 thsice_ini_vars.F \
 thsice_init_fixed.F \
 thsice_main.F \
 thsice_map_exf.F \
 thsice_mnc_init.F \
 thsice_monitor.F \
 thsice_output.F \
 thsice_read_pickup.F \
 thsice_readparms.F \
 thsice_reshape_layers.F \
 thsice_salt_plume.F \
 thsice_slab_ocean.F \
 thsice_solve4temp.F \
 thsice_step_fwd.F \
 thsice_step_temp.F \
 thsice_turnoff_io.F \
 thsice_write_pickup.F \
 timeave_cumul_1k1t.F \
 timeave_cumul_1t.F \
 timeave_cumul_1vfc.F \
 timeave_cumul_2v.F \
 timeave_cumul_2vfc.F \
 timeave_cumul_dif_1t.F \
 timeave_cumulate.F \
 timeave_init_fixed.F \
 timeave_norma_2v.F \
 timeave_normalize.F \
 timeave_reset.F \
 timeave_statv_write.F \
 timeave_statvars.F \
 timeave_surf_flux.F \
 cal_addtime.F \
 cal_checkdate.F \
 cal_compdates.F \
 cal_convdate.F \
 cal_copydate.F \
 cal_daysformonth.F \
 cal_dayspermonth.F \
 cal_fulldate.F \
 cal_getdate.F \
 cal_getmonthsrec.F \
 cal_init_fixed.F \
 cal_intdays.F \
 cal_intmonths.F \
 cal_intyears.F \
 cal_isleap.F \
 cal_monthsforyear.F \
 cal_monthsperyear.F \
 cal_numints.F \
 cal_printdate.F \
 cal_printerror.F \
 cal_readparms.F \
 cal_set.F \
 cal_stepsforday.F \
 cal_stepsperday.F \
 cal_subdates.F \
 cal_summary.F \
 cal_time2dump.F \
 cal_timeinterval.F \
 cal_timepassed.F \
 cal_timestamp.F \
 cal_toseconds.F \
 cal_weekday.F \
 all_proc_die.F \
 bar2.F \
 bar_check.F \
 barrier.F \
 check_threads.F \
 comm_stats.F \
 cumulsum_z_tile.F \
 diff_phase_multiple.F \
 different_multiple.F \
 eeboot.F \
 eeboot_minimal.F \
 eedata_example.F \
 eedie.F \
 eeintro_msg.F \
 eeset_parms.F \
 eewrite_eeenv.F \
 exch0_r4.F \
 exch0_r8.F \
 exch0_rl.F \
 exch0_rs.F \
 exch1_bg_r4_cube.F \
 exch1_bg_r8_cube.F \
 exch1_bg_rl_cube.F \
 exch1_bg_rs_cube.F \
 exch1_r4.F \
 exch1_r4_cube.F \
 exch1_r8.F \
 exch1_r8_cube.F \
 exch1_rl.F \
 exch1_rl_ad.F \
 exch1_rl_cube.F \
 exch1_rl_cube_ad.F \
 exch1_rs.F \
 exch1_rs_ad.F \
 exch1_rs_cube.F \
 exch1_rs_cube_ad.F \
 exch1_uv_r4_cube.F \
 exch1_uv_r8_cube.F \
 exch1_uv_rl_cube.F \
 exch1_uv_rs_cube.F \
 exch1_z_r4_cube.F \
 exch1_z_r8_cube.F \
 exch1_z_rl_cube.F \
 exch1_z_rs_cube.F \
 exch_3d_r4.F \
 exch_3d_r8.F \
 exch_3d_rl.F \
 exch_3d_rs.F \
 exch_cycle_ebl.F \
 exch_init.F \
 exch_r4_recv_get_x.F \
 exch_r4_recv_get_y.F \
 exch_r4_send_put_x.F \
 exch_r4_send_put_y.F \
 exch_r8_recv_get_x.F \
 exch_r8_recv_get_y.F \
 exch_r8_send_put_x.F \
 exch_r8_send_put_y.F \
 exch_rl_recv_get_x.F \
 exch_rl_recv_get_y.F \
 exch_rl_send_put_x.F \
 exch_rl_send_put_y.F \
 exch_rs_recv_get_x.F \
 exch_rs_recv_get_y.F \
 exch_rs_send_put_x.F \
 exch_rs_send_put_y.F \
 exch_s3d_r4.F \
 exch_s3d_r8.F \
 exch_s3d_rl.F \
 exch_s3d_rs.F \
 exch_sm_3d_r4.F \
 exch_sm_3d_r8.F \
 exch_sm_3d_rl.F \
 exch_sm_3d_rs.F \
 exch_uv_3d_r4.F \
 exch_uv_3d_r8.F \
 exch_uv_3d_rl.F \
 exch_uv_3d_rs.F \
 exch_uv_agrid_3d_r4.F \
 exch_uv_agrid_3d_r8.F \
 exch_uv_agrid_3d_rl.F \
 exch_uv_agrid_3d_rs.F \
 exch_uv_bgrid_3d_r4.F \
 exch_uv_bgrid_3d_r8.F \
 exch_uv_bgrid_3d_rl.F \
 exch_uv_bgrid_3d_rs.F \
 exch_uv_dgrid_3d_r4.F \
 exch_uv_dgrid_3d_r8.F \
 exch_uv_dgrid_3d_rl.F \
 exch_uv_dgrid_3d_rs.F \
 exch_uv_xy_r4.F \
 exch_uv_xy_r8.F \
 exch_uv_xy_rl.F \
 exch_uv_xy_rs.F \
 exch_uv_xyz_r4.F \
 exch_uv_xyz_r8.F \
 exch_uv_xyz_rl.F \
 exch_uv_xyz_rs.F \
 exch_xy_r4.F \
 exch_xy_r8.F \
 exch_xy_rl.F \
 exch_xy_rs.F \
 exch_xyz_r4.F \
 exch_xyz_r8.F \
 exch_xyz_rl.F \
 exch_xyz_rs.F \
 exch_z_3d_r4.F \
 exch_z_3d_r8.F \
 exch_z_3d_rl.F \
 exch_z_3d_rs.F \
 fill_cs_corner_ag_rl.F \
 fill_cs_corner_tr_rl.F \
 fill_cs_corner_uv_rl.F \
 fill_cs_corner_uv_rs.F \
 fool_the_compiler.F \
 gather_2d_r4.F \
 gather_2d_r8.F \
 gather_2d_wh_r4.F \
 gather_2d_wh_r8.F \
 gather_vec_r4.F \
 gather_vec_r8.F \
 gather_xz.F \
 gather_yz.F \
 get_periodic_interval.F \
 global_max.F \
 global_sum.F \
 global_sum_singlecpu.F \
 global_sum_tile.F \
 global_vec_sum.F \
 gsum.F \
 ini_communication_patterns.F \
 ini_procs.F \
 ini_threading_environment.F \
 lef_zero.F \
 main.F \
 master_cpu_io.F \
 master_cpu_thread.F \
 mds_byteswapi4.F \
 mds_byteswapr4.F \
 mds_byteswapr8.F \
 mds_flush.F \
 mds_reclen.F \
 mdsfindunit.F \
 memsync.F \
 nml_change_syntax.F \
 nml_set_terminator.F \
 open_copy_data_file.F \
 print.F \
 reset_halo.F \
 scatter_2d_r4.F \
 scatter_2d_r8.F \
 scatter_2d_wh_r4.F \
 scatter_2d_wh_r8.F \
 scatter_vec_r4.F \
 scatter_vec_r8.F \
 scatter_xz.F \
 scatter_yz.F \
 stop_if_error.F \
 timers.F \
 utils.F \
 write_utils.F \
 adams_bashforth2.F \
 adams_bashforth3.F \
 add_walls2masks.F \
 apply_forcing.F \
 calc_3d_diffusivity.F \
 calc_adv_flow.F \
 calc_div_ghat.F \
 calc_eddy_stress.F \
 calc_grad_phi_fv.F \
 calc_grad_phi_hyd.F \
 calc_grad_phi_surf.F \
 calc_grid_angles.F \
 calc_gw.F \
 calc_ivdc.F \
 calc_oce_mxlayer.F \
 calc_phi_hyd.F \
 calc_r_star.F \
 calc_surf_dr.F \
 calc_viscosity.F \
 calc_wsurf_tr.F \
 cg2d.F \
 cg2d_ex0.F \
 cg2d_nsa.F \
 cg2d_sr.F \
 cg3d.F \
 cg3d_ex0.F \
 check_pickup.F \
 config_check.F \
 config_summary.F \
 convective_adjustment.F \
 convective_adjustment_ini.F \
 convective_weights.F \
 convectively_mixtracer.F \
 correction_step.F \
 cycle_ab_tracer.F \
 cycle_tracer.F \
 diags_oceanic_surf_flux.F \
 diags_phi_hyd.F \
 diags_phi_rlow.F \
 diags_rho.F \
 do_atmospheric_phys.F \
 do_fields_blocking_exchanges.F \
 do_oceanic_phys.F \
 do_stagger_fields_exchanges.F \
 do_statevars_diags.F \
 do_statevars_tave.F \
 do_the_model_io.F \
 do_write_pickup.F \
 dynamics.F \
 external_fields_load.F \
 external_forcing.F \
 external_forcing_surf.F \
 find_alpha.F \
 find_hyd_press_1d.F \
 find_rho.F \
 forcing_surf_relax.F \
 forward_step.F \
 freesurf_rescale_g.F \
 freeze_surface.F \
 grad_sigma.F \
 gsw_teos10.F \
 impldiff.F \
 ini_cartesian_grid.F \
 ini_cg2d.F \
 ini_cg3d.F \
 ini_cori.F \
 ini_curvilinear_grid.F \
 ini_cylinder_grid.F \
 ini_depths.F \
 ini_dynvars.F \
 ini_eos.F \
 ini_ffields.F \
 ini_fields.F \
 ini_forcing.F \
 ini_global_domain.F \
 ini_grid.F \
 ini_linear_phisurf.F \
 ini_local_grid.F \
 ini_masks_etc.F \
 ini_mixing.F \
 ini_mnc_vars.F \
 ini_model_io.F \
 ini_nh_fields.F \
 ini_nh_vars.F \
 ini_nlfs_vars.F \
 ini_p_ground.F \
 ini_parms.F \
 ini_pressure.F \
 ini_psurf.F \
 ini_salt.F \
 ini_sigma_hfac.F \
 ini_spherical_polar_grid.F \
 ini_theta.F \
 ini_vel.F \
 ini_vertical_grid.F \
 initialise_fixed.F \
 initialise_varia.F \
 integr_continuity.F \
 integrate_for_w.F \
 load_fields_driver.F \
 load_grid_spacing.F \
 load_ref_files.F \
 main_do_loop.F \
 momentum_correction_step.F \
 packages_boot.F \
 packages_check.F \
 packages_error_msg.F \
 packages_init_fixed.F \
 packages_init_variables.F \
 packages_print_msg.F \
 packages_readparms.F \
 packages_unused_msg.F \
 packages_write_pickup.F \
 plot_field.F \
 port_rand.F \
 post_cg3d.F \
 pre_cg3d.F \
 pressure_for_eos.F \
 read_pickup.F \
 remove_mean.F \
 reset_nlfs_vars.F \
 rotate_spherical_polar_grid.F \
 rotate_uv2en.F \
 salt_integrate.F \
 seawater.F \
 set_defaults.F \
 set_grid_factors.F \
 set_parms.F \
 set_ref_state.F \
 solve_for_pressure.F \
 solve_pentadiagonal.F \
 solve_tridiagonal.F \
 solve_uv_tridiago.F \
 state_summary.F \
 swfrac.F \
 taueddy_init_varia.F \
 taueddy_tendency_apply.F \
 temp_integrate.F \
 the_main_loop.F \
 the_model_main.F \
 thermodynamics.F \
 timestep.F \
 timestep_tracer.F \
 timestep_wvel.F \
 tracers_correction_step.F \
 tracers_iigw_correction.F \
 turnoff_model_io.F \
 update_cg2d.F \
 update_etah.F \
 update_etaws.F \
 update_masks_etc.F \
 update_r_star.F \
 update_sigma.F \
 update_surf_dr.F \
 write_grid.F \
 write_pickup.F \
 write_state.F
NON_AD_F77_SRC_FILES =  \
 exf_geos_bulkf.F \
 bulkf_ave.F \
 bulkf_fields_load.F \
 bulkf_flux_adjust.F \
 bulkf_forcing.F \
 bulkf_formula_aim.F \
 bulkf_formula_lanl.F \
 bulkf_formula_lay.F \
 bulkf_init_varia.F \
 bulkf_output.F \
 bulkf_readparms.F \
 bulkf_sh2rh_aim.F \
 chksum_tiled.F \
 debug_call.F \
 debug_cs_corner_uv.F \
 debug_enter.F \
 debug_fld_stats_rl.F \
 debug_fld_stats_rs.F \
 debug_leave.F \
 debug_msg.F \
 debug_stats_rl.F \
 debug_stats_rs.F \
 fill_in_corners_rl.F \
 write_fullarray_rl.F \
 write_fullarray_rs.F \
 diag_calc_psivel.F \
 diag_cg2d.F \
 diag_vegtile_fill.F \
 diagnostics_addtolist.F \
 diagnostics_calc_phivel.F \
 diagnostics_check.F \
 diagnostics_clear.F \
 diagnostics_fill.F \
 diagnostics_fill_field.F \
 diagnostics_fill_rs.F \
 diagnostics_fill_state.F \
 diagnostics_fract_fill.F \
 diagnostics_ini_io.F \
 diagnostics_init_early.F \
 diagnostics_init_fixed.F \
 diagnostics_init_varia.F \
 diagnostics_interp_p2p.F \
 diagnostics_interp_vert.F \
 diagnostics_list_check.F \
 diagnostics_main_init.F \
 diagnostics_mnc_out.F \
 diagnostics_out.F \
 diagnostics_read_pickup.F \
 diagnostics_readparms.F \
 diagnostics_scale_fill.F \
 diagnostics_scale_fill_rs.F \
 diagnostics_set_calc.F \
 diagnostics_set_levels.F \
 diagnostics_set_pointers.F \
 diagnostics_setdiag.F \
 diagnostics_status_error.F \
 diagnostics_sum_levels.F \
 diagnostics_summary.F \
 diagnostics_switch_onoff.F \
 diagnostics_utils.F \
 diagnostics_write.F \
 diagnostics_write_adj.F \
 diagnostics_write_pickup.F \
 diagstats_ascii_out.F \
 diagstats_calc.F \
 diagstats_clear.F \
 diagstats_close_io.F \
 diagstats_fill.F \
 diagstats_global.F \
 diagstats_ini_io.F \
 diagstats_local.F \
 diagstats_mnc_out.F \
 diagstats_others_calc.F \
 diagstats_output.F \
 diagstats_set_pointers.F \
 diagstats_set_regions.F \
 diagstats_setdiag.F \
 exch2_3d_r4.F \
 exch2_3d_r8.F \
 exch2_ad_get_r41.F \
 exch2_ad_get_r42.F \
 exch2_ad_get_r81.F \
 exch2_ad_get_r82.F \
 exch2_ad_get_rl1.F \
 exch2_ad_get_rl2.F \
 exch2_ad_get_rs1.F \
 exch2_ad_get_rs2.F \
 exch2_ad_put_r41.F \
 exch2_ad_put_r42.F \
 exch2_ad_put_r81.F \
 exch2_ad_put_r82.F \
 exch2_ad_put_rl1.F \
 exch2_ad_put_rl2.F \
 exch2_ad_put_rs1.F \
 exch2_ad_put_rs2.F \
 exch2_check_depths.F \
 exch2_get_r41.F \
 exch2_get_r42.F \
 exch2_get_r81.F \
 exch2_get_r82.F \
 exch2_get_rl1.F \
 exch2_get_rl2.F \
 exch2_get_rs1.F \
 exch2_get_rs2.F \
 exch2_get_scal_bounds.F \
 exch2_get_uv_bounds.F \
 exch2_put_r41.F \
 exch2_put_r42.F \
 exch2_put_r81.F \
 exch2_put_r82.F \
 exch2_put_rl1.F \
 exch2_put_rl2.F \
 exch2_put_rs1.F \
 exch2_put_rs2.F \
 exch2_r41_cube.F \
 exch2_r41_cube_ad.F \
 exch2_r42_cube.F \
 exch2_r42_cube_ad.F \
 exch2_r81_cube.F \
 exch2_r81_cube_ad.F \
 exch2_r82_cube.F \
 exch2_r82_cube_ad.F \
 exch2_recv_r41.F \
 exch2_recv_r42.F \
 exch2_recv_r81.F \
 exch2_recv_r82.F \
 exch2_recv_rl1.F \
 exch2_recv_rl2.F \
 exch2_recv_rs1.F \
 exch2_recv_rs2.F \
 exch2_rl1_cube.F \
 exch2_rl1_cube_ad.F \
 exch2_rl2_cube.F \
 exch2_rl2_cube_ad.F \
 exch2_rs1_cube.F \
 exch2_rs1_cube_ad.F \
 exch2_rs2_cube.F \
 exch2_rs2_cube_ad.F \
 exch2_s3d_r4.F \
 exch2_s3d_r8.F \
 exch2_s3d_rl.F \
 exch2_s3d_rs.F \
 exch2_send_r41.F \
 exch2_send_r42.F \
 exch2_send_r81.F \
 exch2_send_r82.F \
 exch2_send_rl1.F \
 exch2_send_rl2.F \
 exch2_send_rs1.F \
 exch2_send_rs2.F \
 exch2_sm_3d_r4.F \
 exch2_sm_3d_r8.F \
 exch2_sm_3d_rs.F \
 exch2_uv_3d_r4.F \
 exch2_uv_3d_r8.F \
 exch2_uv_agrid_3d_r4.F \
 exch2_uv_agrid_3d_r8.F \
 exch2_uv_bgrid_3d_r4.F \
 exch2_uv_bgrid_3d_r8.F \
 exch2_uv_bgrid_3d_rl.F \
 exch2_uv_bgrid_3d_rs.F \
 exch2_uv_cgrid_3d_r4.F \
 exch2_uv_cgrid_3d_r8.F \
 exch2_uv_cgrid_3d_rl.F \
 exch2_uv_cgrid_3d_rs.F \
 exch2_uv_dgrid_3d_r4.F \
 exch2_uv_dgrid_3d_r8.F \
 exch2_z_3d_r4.F \
 exch2_z_3d_r8.F \
 exch2_z_3d_rl.F \
 exch2_z_3d_rs.F \
 w2_cumulsum_z_tile.F \
 w2_e2setup.F \
 w2_eeboot.F \
 w2_map_procs.F \
 w2_print_comm_sequence.F \
 w2_print_e2setup.F \
 w2_readparms.F \
 w2_set_cs6_facets.F \
 w2_set_f2f_index.F \
 w2_set_gen_facets.F \
 w2_set_map_cumsum.F \
 w2_set_map_tiles.F \
 w2_set_myown_facets.F \
 w2_set_single_facet.F \
 w2_set_tile2tiles.F \
 exf_ad_dump.F \
 exf_adjoint_snapshots.F \
 exf_adjoint_snapshots__g.F \
 exf_adjoint_snapshots_ad.F \
 exf_check.F \
 exf_check_range.F \
 exf_diagnostics_fill.F \
 exf_diagnostics_init.F \
 exf_getffield_start.F \
 exf_getfield_start.F \
 exf_init_fixed.F \
 exf_init_interp.F \
 exf_interp_read.F \
 exf_monitor.F \
 exf_monitor_ad.F \
 exf_readparms.F \
 exf_summary.F \
 exf_weight_sfx_diags.F \
 exf_zenithangle_table.F \
 gad_advscheme.F \
 gad_check.F \
 gad_diagnostics_init.F \
 gad_diagnostics_state.F \
 gad_init_fixed.F \
 gad_osc_hat_r.F \
 gad_osc_hat_x.F \
 gad_osc_hat_y.F \
 gad_osc_mul_r.F \
 gad_osc_mul_x.F \
 gad_osc_mul_y.F \
 gad_plm_fun.F \
 gad_ppm_adv_r.F \
 gad_ppm_adv_x.F \
 gad_ppm_adv_y.F \
 gad_ppm_flx_r.F \
 gad_ppm_flx_x.F \
 gad_ppm_flx_y.F \
 gad_ppm_fun.F \
 gad_ppm_hat_r.F \
 gad_ppm_hat_x.F \
 gad_ppm_hat_y.F \
 gad_ppm_p3e_r.F \
 gad_ppm_p3e_x.F \
 gad_ppm_p3e_y.F \
 gad_pqm_adv_r.F \
 gad_pqm_adv_x.F \
 gad_pqm_adv_y.F \
 gad_pqm_flx_r.F \
 gad_pqm_flx_x.F \
 gad_pqm_flx_y.F \
 gad_pqm_fun.F \
 gad_pqm_hat_r.F \
 gad_pqm_hat_x.F \
 gad_pqm_hat_y.F \
 gad_pqm_p5e_r.F \
 gad_pqm_p5e_x.F \
 gad_pqm_p5e_y.F \
 gad_write_pickup.F \
 salt_fill.F \
 gmredi_calc_eigs.F \
 gmredi_calc_psi_bvp.F \
 gmredi_calc_qgleith.F \
 gmredi_calc_urms.F \
 gmredi_check.F \
 gmredi_diagnostics_fill.F \
 gmredi_diagnostics_impl.F \
 gmredi_diagnostics_init.F \
 gmredi_init_fixed.F \
 gmredi_k3d.F \
 gmredi_mnc_init.F \
 gmredi_output.F \
 gmredi_read_pickup.F \
 gmredi_readparms.F \
 gmredi_write_pickup.F \
 submeso_calc_psi.F \
 mdsio_buffertorl.F \
 mdsio_buffertors.F \
 mdsio_check4file.F \
 mdsio_facef_read.F \
 mdsio_gl.F \
 mdsio_gl_slice.F \
 mdsio_pass_r4torl.F \
 mdsio_pass_r4tors.F \
 mdsio_pass_r8torl.F \
 mdsio_pass_r8tors.F \
 mdsio_rd_rec_rl.F \
 mdsio_rd_rec_rs.F \
 mdsio_read_field.F \
 mdsio_read_meta.F \
 mdsio_read_section.F \
 mdsio_read_tape.F \
 mdsio_read_whalos.F \
 mdsio_readvec_loc.F \
 mdsio_rw_field.F \
 mdsio_rw_slice.F \
 mdsio_seg4torl.F \
 mdsio_seg4tors.F \
 mdsio_seg8torl.F \
 mdsio_seg8tors.F \
 mdsio_segxtorx_2d.F \
 mdsio_wr_metafiles.F \
 mdsio_wr_rec_rl.F \
 mdsio_wr_rec_rs.F \
 mdsio_write_field.F \
 mdsio_write_meta.F \
 mdsio_write_section.F \
 mdsio_write_tape.F \
 mdsio_write_whalos.F \
 mdsio_writelocal.F \
 mdsio_writevec_loc.F \
 MNC_CW_READWRITE_I.F \
 MNC_CW_READWRITE_RL.F \
 MNC_CW_READWRITE_RS.F \
 mnc_cw_citer.F \
 mnc_cw_cvars.F \
 mnc_cw_init.F \
 mnc_cw_missingvals.F \
 mnc_cw_model_attr.F \
 mnc_cw_udim.F \
 mnc_cw_write_grid_info.F \
 mnc_cwrapper.F \
 mnc_dim.F \
 mnc_dump.F \
 mnc_file.F \
 mnc_grid.F \
 mnc_init.F \
 mnc_readparms.F \
 mnc_update_time.F \
 mnc_utils.F \
 mnc_var.F \
 mom_calc_3d_strain.F \
 mom_calc_smag_3d.F \
 mom_diagnostics_init.F \
 mom_init_fixed.F \
 mom_u_implicit_r.F \
 mom_uv_smag_3d.F \
 mom_v_implicit_r.F \
 mom_visc_qgl_limit.F \
 mom_visc_qgl_stretch.F \
 mom_w_coriolis_nh.F \
 mom_w_metric_nh.F \
 mom_w_sidedrag.F \
 mom_w_smag_3d.F \
 mom_uv_boundary.F \
 mon_advcfl.F \
 mon_advcflw.F \
 mon_advcflw2.F \
 mon_calc_advcfl.F \
 mon_calc_stats_rl.F \
 mon_calc_stats_rs.F \
 mon_init.F \
 mon_ke.F \
 mon_out.F \
 mon_printstats_rl.F \
 mon_printstats_rs.F \
 mon_set_iounit.F \
 mon_set_pref.F \
 mon_solution.F \
 mon_stats_latbnd_rl.F \
 mon_stats_rl.F \
 mon_stats_rs.F \
 mon_surfcor.F \
 mon_vort3.F \
 mon_writestats_rl.F \
 mon_writestats_rs.F \
 monitor.F \
 monitor_ad.F \
 monitor_g.F \
 get_write_global_fld.F \
 read_glvec_rl.F \
 read_glvec_rs.F \
 read_mflds.F \
 rw_get_suffix.F \
 set_write_global_fld.F \
 write_fld_3d_rl.F \
 write_fld_3d_rs.F \
 write_fld_s3d_rl.F \
 write_fld_s3d_rs.F \
 write_fld_xy_rl.F \
 write_fld_xy_rs.F \
 write_fld_xyz_rl.F \
 write_fld_xyz_rs.F \
 write_glvec_rl.F \
 write_glvec_rs.F \
 write_local_rl.F \
 write_local_rs.F \
 write_rec.F \
 seaice_ad_dump.F \
 seaice_calc_lhs.F \
 seaice_calc_residual.F \
 seaice_calc_rhs.F \
 seaice_check.F \
 seaice_check_pickup.F \
 seaice_cost_init_fixed.F \
 seaice_cost_weights.F \
 seaice_diagnostics_init.F \
 seaice_do_ridging.F \
 seaice_fgmres.F \
 seaice_init_fixed.F \
 seaice_itd_pickup.F \
 seaice_itd_redist.F \
 seaice_itd_remap.F \
 seaice_itd_sum.F \
 seaice_jacvec.F \
 seaice_jfnk.F \
 seaice_krylov.F \
 seaice_mnc_init.F \
 seaice_mom_advection.F \
 seaice_monitor.F \
 seaice_monitor_ad.F \
 seaice_obcs_output.F \
 seaice_output.F \
 seaice_preconditioner.F \
 seaice_prepare_ridging.F \
 seaice_readparms.F \
 seaice_summary.F \
 seaice_turnoff_io.F \
 seaice_write_pickup.F \
 thsice_check.F \
 thsice_check_conserv.F \
 thsice_diagnostics_init.F \
 thsice_diagnostics_state.F \
 thsice_get_bulkf.F \
 thsice_impl_temp.F \
 thsice_init_fixed.F \
 thsice_mnc_init.F \
 thsice_monitor.F \
 thsice_output.F \
 thsice_read_pickup.F \
 thsice_readparms.F \
 thsice_reshape_layers.F \
 thsice_salt_plume.F \
 thsice_slab_ocean.F \
 thsice_turnoff_io.F \
 thsice_write_pickup.F \
 timeave_init_fixed.F \
 cal_daysformonth.F \
 cal_dayspermonth.F \
 cal_init_fixed.F \
 cal_monthsforyear.F \
 cal_monthsperyear.F \
 cal_readparms.F \
 cal_set.F \
 cal_stepsforday.F \
 cal_stepsperday.F \
 cal_summary.F \
 cal_weekday.F \
 all_proc_die.F \
 bar2.F \
 bar_check.F \
 barrier.F \
 check_threads.F \
 comm_stats.F \
 cumulsum_z_tile.F \
 diff_phase_multiple.F \
 eeboot.F \
 eeboot_minimal.F \
 eedata_example.F \
 eedie.F \
 eeintro_msg.F \
 eeset_parms.F \
 eewrite_eeenv.F \
 exch0_r4.F \
 exch0_r8.F \
 exch0_rl.F \
 exch0_rs.F \
 exch1_bg_r4_cube.F \
 exch1_bg_r8_cube.F \
 exch1_bg_rl_cube.F \
 exch1_bg_rs_cube.F \
 exch1_r4.F \
 exch1_r4_cube.F \
 exch1_r8.F \
 exch1_r8_cube.F \
 exch1_rl.F \
 exch1_rl_ad.F \
 exch1_rl_cube.F \
 exch1_rl_cube_ad.F \
 exch1_rs.F \
 exch1_rs_ad.F \
 exch1_rs_cube.F \
 exch1_rs_cube_ad.F \
 exch1_uv_r4_cube.F \
 exch1_uv_r8_cube.F \
 exch1_uv_rl_cube.F \
 exch1_uv_rs_cube.F \
 exch1_z_r4_cube.F \
 exch1_z_r8_cube.F \
 exch1_z_rl_cube.F \
 exch1_z_rs_cube.F \
 exch_3d_r4.F \
 exch_3d_r8.F \
 exch_cycle_ebl.F \
 exch_init.F \
 exch_r4_recv_get_x.F \
 exch_r4_recv_get_y.F \
 exch_r4_send_put_x.F \
 exch_r4_send_put_y.F \
 exch_r8_recv_get_x.F \
 exch_r8_recv_get_y.F \
 exch_r8_send_put_x.F \
 exch_r8_send_put_y.F \
 exch_rl_recv_get_x.F \
 exch_rl_recv_get_y.F \
 exch_rl_send_put_x.F \
 exch_rl_send_put_y.F \
 exch_rs_recv_get_x.F \
 exch_rs_recv_get_y.F \
 exch_rs_send_put_x.F \
 exch_rs_send_put_y.F \
 exch_s3d_r4.F \
 exch_s3d_r8.F \
 exch_s3d_rl.F \
 exch_s3d_rs.F \
 exch_sm_3d_r4.F \
 exch_sm_3d_r8.F \
 exch_sm_3d_rs.F \
 exch_uv_3d_r4.F \
 exch_uv_3d_r8.F \
 exch_uv_agrid_3d_r4.F \
 exch_uv_agrid_3d_r8.F \
 exch_uv_bgrid_3d_r4.F \
 exch_uv_bgrid_3d_r8.F \
 exch_uv_bgrid_3d_rl.F \
 exch_uv_bgrid_3d_rs.F \
 exch_uv_dgrid_3d_r4.F \
 exch_uv_dgrid_3d_r8.F \
 exch_uv_xy_r4.F \
 exch_uv_xy_r8.F \
 exch_uv_xyz_r4.F \
 exch_uv_xyz_r8.F \
 exch_xy_r4.F \
 exch_xy_r8.F \
 exch_xyz_r4.F \
 exch_xyz_r8.F \
 exch_z_3d_r4.F \
 exch_z_3d_r8.F \
 exch_z_3d_rl.F \
 exch_z_3d_rs.F \
 fool_the_compiler.F \
 gather_2d_r4.F \
 gather_2d_r8.F \
 gather_2d_wh_r4.F \
 gather_2d_wh_r8.F \
 gather_vec_r4.F \
 gather_vec_r8.F \
 gather_xz.F \
 gather_yz.F \
 global_max.F \
 global_sum.F \
 global_sum_singlecpu.F \
 global_sum_tile.F \
 global_vec_sum.F \
 gsum.F \
 ini_communication_patterns.F \
 ini_procs.F \
 ini_threading_environment.F \
 main.F \
 master_cpu_io.F \
 master_cpu_thread.F \
 mds_byteswapi4.F \
 mds_byteswapr4.F \
 mds_byteswapr8.F \
 mds_flush.F \
 mds_reclen.F \
 mdsfindunit.F \
 memsync.F \
 nml_change_syntax.F \
 nml_set_terminator.F \
 open_copy_data_file.F \
 print.F \
 reset_halo.F \
 scatter_2d_r4.F \
 scatter_2d_r8.F \
 scatter_2d_wh_r4.F \
 scatter_2d_wh_r8.F \
 scatter_vec_r4.F \
 scatter_vec_r8.F \
 scatter_xz.F \
 scatter_yz.F \
 stop_if_error.F \
 timers.F \
 utils.F \
 write_utils.F \
 add_walls2masks.F \
 calc_eddy_stress.F \
 calc_grid_angles.F \
 calc_gw.F \
 calc_oce_mxlayer.F \
 cg2d.F \
 cg2d_ex0.F \
 cg2d_sr.F \
 cg3d.F \
 cg3d_ex0.F \
 check_pickup.F \
 config_check.F \
 config_summary.F \
 diags_oceanic_surf_flux.F \
 do_statevars_diags.F \
 do_statevars_tave.F \
 do_the_model_io.F \
 do_write_pickup.F \
 external_forcing.F \
 find_hyd_press_1d.F \
 gsw_teos10.F \
 ini_cartesian_grid.F \
 ini_cg3d.F \
 ini_cori.F \
 ini_curvilinear_grid.F \
 ini_cylinder_grid.F \
 ini_eos.F \
 ini_global_domain.F \
 ini_grid.F \
 ini_linear_phisurf.F \
 ini_local_grid.F \
 ini_masks_etc.F \
 ini_mnc_vars.F \
 ini_model_io.F \
 ini_nh_vars.F \
 ini_parms.F \
 ini_sigma_hfac.F \
 ini_spherical_polar_grid.F \
 ini_vertical_grid.F \
 initialise_fixed.F \
 load_ref_files.F \
 packages_boot.F \
 packages_check.F \
 packages_error_msg.F \
 packages_init_fixed.F \
 packages_print_msg.F \
 packages_readparms.F \
 packages_unused_msg.F \
 packages_write_pickup.F \
 plot_field.F \
 port_rand.F \
 post_cg3d.F \
 pre_cg3d.F \
 rotate_spherical_polar_grid.F \
 set_defaults.F \
 set_grid_factors.F \
 set_parms.F \
 set_ref_state.F \
 solve_uv_tridiago.F \
 the_model_main.F \
 timestep_wvel.F \
 tracers_iigw_correction.F \
 turnoff_model_io.F \
 write_grid.F \
 write_pickup.F \
 write_state.F
C_SRC_FILES =  \
 mnc_create_dir.c \
 mnc_cw_fsize.c \
 gsl_ieee_env.c \
 ptwrapper.c \
 setdir.c \
 setrlstk.c \
 sigreg.c \
 tim.c \
 timer_stats.c
F90_SRC_FILES =  \
 LINADJ.F90 \
 PHI.F90 \
 PSI.F90 \
 ZCSUB.F90 \
 helfsurface.F90
H_SRC_FILES =  \
 EXF_OPTIONS.h \
 MAPL_CONST.h \
 CPP_OPTIONS.h \
 DIAGNOSTICS_SIZE.h \
 DIAG_OPTIONS.h \
 SEAICE_OPTIONS.h \
 SIZE.h \
 BULKF.h \
 BULKF_CONSERV.h \
 BULKF_INT.h \
 BULKF_PARAMS.h \
 BULKF_TAVE.h \
 BULK_FORCE_OPTIONS.h \
 DEBUG_OPTIONS.h \
 DIAGNOSTICS.h \
 DIAGNOSTICS_CALC.h \
 DIAGSTATS_REGIONS.h \
 W2_EXCH2_BUFFER.h \
 W2_EXCH2_PARAMS.h \
 W2_EXCH2_SIZE.h \
 W2_EXCH2_TOPOLOGY.h \
 W2_OPTIONS.h \
 EXF_CONSTANTS.h \
 EXF_FIELDS.h \
 EXF_INTERP_PARAM.h \
 EXF_INTERP_SIZE.h \
 EXF_PARAM.h \
 exf_ad_check_lev1_dir.h \
 exf_ad_check_lev2_dir.h \
 exf_ad_check_lev3_dir.h \
 exf_ad_check_lev4_dir.h \
 GAD.h \
 GAD_FLUX_LIMITER.h \
 GAD_OPTIONS.h \
 GAD_SOM_VARS.h \
 gad_ad_check_lev1_dir.h \
 gad_ad_check_lev2_dir.h \
 gad_ad_check_lev3_dir.h \
 gad_ad_check_lev4_dir.h \
 GMREDI.h \
 GMREDI_OPTIONS.h \
 GMREDI_TAVE.h \
 MDSIO_BUFF_3D.h \
 MDSIO_BUFF_WH.h \
 MDSIO_OPTIONS.h \
 MNC_BUFF.h \
 MNC_COMMON.h \
 MNC_ID_HEADER.h \
 MNC_OPTIONS.h \
 MNC_PARAMS.h \
 MNC_SIZE.h \
 MOM_COMMON_OPTIONS.h \
 MOM_VISC.h \
 MOM_FLUXFORM.h \
 MOM_FLUXFORM_OPTIONS.h \
 MOM_VECINV_OPTIONS.h \
 MONITOR.h \
 MONITOR_OPTIONS.h \
 RW_MFLDS.h \
 RW_OPTIONS.h \
 SEAICE.h \
 SEAICE_COST.h \
 SEAICE_PARAMS.h \
 SEAICE_SIZE.h \
 SEAICE_TAVE.h \
 SEAICE_TRACER.h \
 seaice_ad_check_lev1_dir.h \
 seaice_ad_check_lev2_dir.h \
 seaice_ad_check_lev3_dir.h \
 seaice_ad_check_lev4_dir.h \
 THSICE_COST.h \
 THSICE_DEBUG.h \
 THSICE_OPTIONS.h \
 THSICE_PARAMS.h \
 THSICE_SIZE.h \
 THSICE_TAVE.h \
 THSICE_VARS.h \
 thsice_ad_check_lev1_dir.h \
 thsice_ad_check_lev2_dir.h \
 thsice_ad_check_lev3_dir.h \
 thsice_ad_check_lev4_dir.h \
 thsice_test_addfluid.h \
 TIMEAVE_OPTIONS.h \
 TIMEAVE_STATV.h \
 CAL_OPTIONS.h \
 cal.h \
 BAR2.h \
 BARRIER.h \
 CPP_EEMACROS.h \
 CPP_EEOPTIONS.h \
 CUMULSUM.h \
 DEF_IN_MAKEFILE.h \
 EEBUFF_SCPU.h \
 EEPARAMS.h \
 EESUPPORT.h \
 EXCH.h \
 GLOBAL_MAX.h \
 GLOBAL_SUM.h \
 MAIN_PDIRECTIVES1.h \
 MAIN_PDIRECTIVES2.h \
 MPI_INFO.h \
 SIGREG.h \
 CG2D.h \
 CG3D.h \
 DXC_MACROS.h \
 DXF_MACROS.h \
 DXG_MACROS.h \
 DXV_MACROS.h \
 DYC_MACROS.h \
 DYF_MACROS.h \
 DYG_MACROS.h \
 DYNVARS.h \
 DYU_MACROS.h \
 EOS.h \
 FCORI_MACROS.h \
 FFIELDS.h \
 GRID.h \
 GRID_MACROS.h \
 HFACC_MACROS.h \
 HFACS_MACROS.h \
 HFACW_MACROS.h \
 MASKS_MACROS.h \
 MASKW_MACROS.h \
 NH_VARS.h \
 PARAMS.h \
 RAS_MACROS.h \
 RAW_MACROS.h \
 RA_MACROS.h \
 RECIP_DXC_MACROS.h \
 RECIP_DXF_MACROS.h \
 RECIP_DXG_MACROS.h \
 RECIP_DXV_MACROS.h \
 RECIP_DYC_MACROS.h \
 RECIP_DYF_MACROS.h \
 RECIP_DYG_MACROS.h \
 RECIP_DYU_MACROS.h \
 RECIP_HFACC_MACROS.h \
 RECIP_HFACS_MACROS.h \
 RECIP_HFACW_MACROS.h \
 RESTART.h \
 SET_GRID.h \
 SOLVE_FOR_PRESSURE.h \
 SOLVE_FOR_PRESSURE3D.h \
 SURFACE.h \
 TANPHIATU_MACROS.h \
 TANPHIATV_MACROS.h \
 THE_MODEL_COMMON_BLOCKS.h \
 XC_MACROS.h \
 YC_MACROS.h
AD_FLOW_FILES =  \
 debug_ad.flow \
 diagnostics_ad.flow \
 exch2.flow \
 exf_ad.flow \
 gmredi_ad.flow \
 mdsio_ad.flow \
 mnc_ad.flow \
 monitor_ad.flow \
 rw_ad.flow \
 seaice.flow \
 thsice_ad.flow \
 eesupp.flow \
 exch1_ad.flow

F77_PP_SRC_FILES = $(F77_SRC_FILES:.F=.f)
F90_PP_SRC_FILES = $(F90_SRC_FILES:.F90=.f90)
OBJFILES= $(F77_SRC_FILES:.F=.o) $(C_SRC_FILES:.c=.o) $(F90_SRC_FILES:.F90=.o)
FLOWFILES =  $(AD_FLOW_FILES:.flow=.flowdir)

.SUFFIXES:
.SUFFIXES: .o .f .p .F .c .ff90 .f90 .FF90 .F90 .flowdir .flow

all: fwd_exe_target
fwd_exe_target:
	@echo Update AD_CONFIG.h and make $(EXECUTABLE)
	@$(TOOLSDIR)/convert_cpp_cmd2defines "Forward version" -bAD_CONFIG_H -UALLOW_ADJOINT_RUN -UALLOW_TANGENTLINEAR_RUN > ad_config.template
	@cmp ad_config.template AD_CONFIG.h || cat ad_config.template > AD_CONFIG.h
	@-rm -f ad_config.template
	$(MAKE) -f $(MAKEFILE) $(EXECUTABLE)

$(EXECUTABLE): $(SPECIAL_FILES) $(F77_SRC_FILES) $(C_SRC_FILES) $(H_SRC_FILES) $(F90_SRC_FILES) $(OBJFILES) $(EMBEDDED_FILES)
	@echo Creating $@ ...
	$(LINK) -o $@ $(FFLAGS) $(FOPTIM) $(OBJFILES) $(LIBS)

depend:
	@$(MAKE) -f $(MAKEFILE) links
	$(MAKEDEPEND) -f $(MAKEFILE) -o .f $(DEFINES) $(INCLUDES) $(CPPINCLUDES) $(F77_SRC_FILES)
	$(TOOLSDIR)/f90mkdepend >> $(MAKEFILE)
	-rm -f makedepend.out

lib: libmitgcmuv.a

libmitgcmuv.a: $(SPECIAL_FILES) $(OBJFILES)
	ar rcv libmitgcmuv.a $(OBJFILES)
	ar d   libmitgcmuv.a main.o

obj: $(OBJFILES)

links: $(F77_SRC_FILES) $(C_SRC_FILES) $(H_SRC_FILES) $(F90_SRC_FILES) $(SPECIAL_FILES)

small_f: $(F77_PP_SRC_FILES) $(F90_PP_SRC_FILES)

# remove most of the files that "make" generates
clean:
	-rm -rf *.p *.f90 *.mod  work.{pc,pcl} *.template
	-rm -rf *.o
	-rm -rf *.f *.flowdir
	-rm -rf *.ff90 $(AD_CLEAN) ad_input*

# remove most of the files that "make" and "make depend" generate
Clean:
	@$(MAKE) -f $(MAKEFILE) clean
	@$(MAKE) -f $(MAKEFILE) cleanlinks
	-rm -f $(SPECIAL_FILES) f90mkdepend.log Makefile.old
	-rm -f taf_command taf_output taf_ad.log taf_ad_flow.log taf_ftl.log

# remove also the executable, files that "genmake2" generates (except Makefile)
#         and output from a run (plus log files from testreport)
CLEAN:
	@$(MAKE) -f $(MAKEFILE) Clean
	-rm -f $(EXECUTABLE) $(EXE_AD) $(EXE_FTL) *.bak
	-rm -f genmake.log genmake_state genmake_*optfile
	-rm -f SIZE.h.mpi genmake.tr_log make.tr_log
	-rm -rf mpi_headers mnc_test_*
	-find $(EXEDIR) -name "*.meta" -exec rm {} \;
	-find $(EXEDIR) -name "*.data" -exec rm {} \;
	-find $(EXEDIR) -name "fort.*" -exec rm {} \;
	-rm -f *.txt STDOUT.* STDERR.* *diagnostics.log *.[0-9][0-9][0-9][0-9].log
	-rm -f datetime costfinal divided.ctrl snapshot* output_adm.txt.diva_*
	-rm -f *_MIT_CE_000.opt0000 costfunction*0000
	-rm -f oad_cp.[0-9][0-9][0-9].?????

makefile:
	$(TOOLSDIR)/genmake2  "-mods=../code_geos_bulk ../code" "-mpi" "-of=../../../tools/build_options/linux_amd64_ifort+mpi_ice_nas_1"
cleanlinks:
	-find . -type l -exec rm {} \;

# Special targets (SPECIAL_FILES) which are created by make
PACKAGES_CONFIG.h:
	@echo Creating $@ ...
	@$(TOOLSDIR)/convert_cpp_cmd2defines -bPACKAGES_CONFIG_H "Disabled packages:" $(DISABLED_PACKAGES) " " "Enabled packages:" $(ENABLED_PACKAGES) > $@
AD_CONFIG.h:
	@echo Creating $@ ...
	@$(TOOLSDIR)/convert_cpp_cmd2defines "Default version" -bAD_CONFIG_H -UALLOW_ADJOINT_RUN -UALLOW_TANGENTLINEAR_RUN > $@
FC_NAMEMANGLE.h:
	@echo Creating $@ ...
	echo "#define FC_NAMEMANGLE(X)  X ## _" > $@

BUILD_INFO.h:
	@echo Creating $@ ...
	-echo "#define THISVER 'checkpoint67p'" > $@
	-echo "#define THISUSER 'afahad'" >> $@
	-echo "#define THISDATE 'Fri Feb 24 19:42:13 PST 2023'" >> $@
	-echo "#define THISHOST 'pfe22'" >> $@

# The normal chain of rules is (  .F - .f - .o  )

## This nullifies any default implicit rules concerning these two file types:
## %.o : %.F

# C preprocessing and replacing the _d in constants:
CPPCMD = cat $< |  /lib/cpp -traditional -P $(DEFINES) $(INCLUDES) | $(TOOLSDIR)/set64bitConst.sh

.F.f:
	$(CPPCMD)  > $@
.f.o:
	$(FC) $(FFLAGS) $(FOPTIM) -c $<
.F.o:
	$(FC) $(FFLAGS) $(FOPTIM) -c $<
.F90.f90:
	$(CPPCMD)  > $@
.FF90.ff90:
	$(CPPCMD)  > $@
.f90.o:
	$(F90C) $(F90FLAGS) $(F90OPTIM) -c $<
.ff90.o:
	cp $< $(basename  $<).f90
	$(F90C) $(F90FLAGS) $(F90OPTIM) -c $(F90FIXEDFORMAT) $(basename  $<).f90
.c.o:
	$(CC) $(CFLAGS) $(DEFINES) $(INCLUDES) -c $<
.flow.flowdir:
	$(CPPCMD) > $@

# Special exceptions that use the ( .F - .p - .f - .o ) rule-chain
.F.p:
	$(CPPCMD) > $@
.p.f:
	$(KPP) $(KFLAGS1)$@ $(KFLAGS2) $<


TAMC           = tamc
TAF            = staf

TAF_EXTRA      = 
TAMC_EXTRA     = 
LOCAL_MPI_HEADERS    = 

AD_TAMC_FLAGS        = -reverse -admark ad -i4 -r4 -l tamc_ad.log -toplevel 'the_main_loop' -input 'xx_theta_dummy xx_salt_dummy xx_tr1_dummy xx_hflux_dummy xx_sflux_dummy xx_tauu_dummy xx_tauv_dummy xx_atemp_dummy xx_aqh_dummy xx_precip_dummy xx_swflux_dummy xx_swdown_dummy xx_lwflux_dummy xx_lwdown_dummy xx_evap_dummy xx_snowprecip_dummy xx_apressure_dummy xx_runoff_dummy xx_uwind_dummy xx_vwind_dummy xx_obcsn_dummy xx_obcss_dummy xx_obcsw_dummy xx_obcse_dummy xx_sst_dummy xx_sss_dummy xx_depth_dummy xx_diffkr_dummy xx_kapgm_dummy xx_kapredi_dummy xx_bottomdrag_dummy xx_efluxy_dummy xx_efluxp_dummy xx_edtaux_dummy xx_edtauy_dummy xx_uvel_dummy xx_vvel_dummy xx_etan_dummy xx_gen2d_dummy xx_gen3d_dummy xx_genarr2d_dummy xx_genarr3d_dummy xx_gentim2d_dummy xx_siarea_dummy xx_siheff_dummy xx_sihsnow_dummy xx_shifwflx_dummy xx_relaxsst_dummy xx_relaxsss_dummy xx_atemp_mean_dummy xx_aqh_mean_dummy xx_precip_mean_dummy xx_swdown_mean_dummy xx_uwind_mean_dummy xx_vwind_mean_dummy' -output 'fc'
AD_TAF_FLAGS         = -server fastopt.net -f77 -reverse -i4 -r4 -intrinsic system,flush -l taf_ad.log -toplevel 'the_main_loop' -input 'xx_theta_dummy xx_salt_dummy xx_tr1_dummy xx_hflux_dummy xx_sflux_dummy xx_tauu_dummy xx_tauv_dummy xx_atemp_dummy xx_aqh_dummy xx_precip_dummy xx_swflux_dummy xx_swdown_dummy xx_lwflux_dummy xx_lwdown_dummy xx_evap_dummy xx_snowprecip_dummy xx_apressure_dummy xx_runoff_dummy xx_uwind_dummy xx_vwind_dummy xx_obcsn_dummy xx_obcss_dummy xx_obcsw_dummy xx_obcse_dummy xx_sst_dummy xx_sss_dummy xx_depth_dummy xx_diffkr_dummy xx_kapgm_dummy xx_kapredi_dummy xx_bottomdrag_dummy xx_efluxy_dummy xx_efluxp_dummy xx_edtaux_dummy xx_edtauy_dummy xx_uvel_dummy xx_vvel_dummy xx_etan_dummy xx_gen2d_dummy xx_gen3d_dummy xx_genarr2d_dummy xx_genarr3d_dummy xx_gentim2d_dummy xx_siarea_dummy xx_siheff_dummy xx_sihsnow_dummy xx_shifwflx_dummy xx_relaxsst_dummy xx_relaxsss_dummy xx_atemp_mean_dummy xx_aqh_mean_dummy xx_precip_mean_dummy xx_swdown_mean_dummy xx_uwind_mean_dummy xx_vwind_mean_dummy' -output 'fc'
FTL_TAMC_FLAGS       = -forward -ftlmark g_ -i4 -r4 -l tamc_ftl.log -toplevel 'the_main_loop' -input 'xx_theta_dummy xx_salt_dummy xx_tr1_dummy xx_hflux_dummy xx_sflux_dummy xx_tauu_dummy xx_tauv_dummy xx_atemp_dummy xx_aqh_dummy xx_precip_dummy xx_swflux_dummy xx_swdown_dummy xx_lwflux_dummy xx_lwdown_dummy xx_evap_dummy xx_snowprecip_dummy xx_apressure_dummy xx_runoff_dummy xx_uwind_dummy xx_vwind_dummy xx_obcsn_dummy xx_obcss_dummy xx_obcsw_dummy xx_obcse_dummy xx_sst_dummy xx_sss_dummy xx_depth_dummy xx_diffkr_dummy xx_kapgm_dummy xx_kapredi_dummy xx_bottomdrag_dummy xx_efluxy_dummy xx_efluxp_dummy xx_edtaux_dummy xx_edtauy_dummy xx_uvel_dummy xx_vvel_dummy xx_etan_dummy xx_gen2d_dummy xx_gen3d_dummy xx_genarr2d_dummy xx_genarr3d_dummy xx_gentim2d_dummy xx_siarea_dummy xx_siheff_dummy xx_sihsnow_dummy xx_shifwflx_dummy xx_relaxsst_dummy xx_relaxsss_dummy xx_atemp_mean_dummy xx_aqh_mean_dummy xx_precip_mean_dummy xx_swdown_mean_dummy xx_uwind_mean_dummy xx_vwind_mean_dummy' -output 'fc'
FTL_TAF_FLAGS        = -server fastopt.net -f77 -forward -i4 -r4 -intrinsic system,flush -l taf_ftl.log -toplevel 'the_main_loop' -input 'xx_theta_dummy xx_salt_dummy xx_tr1_dummy xx_hflux_dummy xx_sflux_dummy xx_tauu_dummy xx_tauv_dummy xx_atemp_dummy xx_aqh_dummy xx_precip_dummy xx_swflux_dummy xx_swdown_dummy xx_lwflux_dummy xx_lwdown_dummy xx_evap_dummy xx_snowprecip_dummy xx_apressure_dummy xx_runoff_dummy xx_uwind_dummy xx_vwind_dummy xx_obcsn_dummy xx_obcss_dummy xx_obcsw_dummy xx_obcse_dummy xx_sst_dummy xx_sss_dummy xx_depth_dummy xx_diffkr_dummy xx_kapgm_dummy xx_kapredi_dummy xx_bottomdrag_dummy xx_efluxy_dummy xx_efluxp_dummy xx_edtaux_dummy xx_edtauy_dummy xx_uvel_dummy xx_vvel_dummy xx_etan_dummy xx_gen2d_dummy xx_gen3d_dummy xx_genarr2d_dummy xx_genarr3d_dummy xx_gentim2d_dummy xx_siarea_dummy xx_siheff_dummy xx_sihsnow_dummy xx_shifwflx_dummy xx_relaxsst_dummy xx_relaxsss_dummy xx_atemp_mean_dummy xx_aqh_mean_dummy xx_precip_mean_dummy xx_swdown_mean_dummy xx_uwind_mean_dummy xx_vwind_mean_dummy' -output 'fc'
SVD_TAMC_FLAGS       = -reverse -forward -pure -i4 -r4 -l tamc_svd.log -toplevel 'the_main_loop' -input 'xx_theta_dummy xx_salt_dummy xx_tr1_dummy xx_hflux_dummy xx_sflux_dummy xx_tauu_dummy xx_tauv_dummy xx_atemp_dummy xx_aqh_dummy xx_precip_dummy xx_swflux_dummy xx_swdown_dummy xx_lwflux_dummy xx_lwdown_dummy xx_evap_dummy xx_snowprecip_dummy xx_apressure_dummy xx_runoff_dummy xx_uwind_dummy xx_vwind_dummy xx_obcsn_dummy xx_obcss_dummy xx_obcsw_dummy xx_obcse_dummy xx_sst_dummy xx_sss_dummy xx_depth_dummy xx_diffkr_dummy xx_kapgm_dummy xx_kapredi_dummy xx_bottomdrag_dummy xx_efluxy_dummy xx_efluxp_dummy xx_edtaux_dummy xx_edtauy_dummy xx_uvel_dummy xx_vvel_dummy xx_etan_dummy xx_gen2d_dummy xx_gen3d_dummy xx_genarr2d_dummy xx_genarr3d_dummy xx_gentim2d_dummy xx_siarea_dummy xx_siheff_dummy xx_sihsnow_dummy xx_shifwflx_dummy xx_relaxsst_dummy xx_relaxsss_dummy xx_atemp_mean_dummy xx_aqh_mean_dummy xx_precip_mean_dummy xx_swdown_mean_dummy xx_uwind_mean_dummy xx_vwind_mean_dummy' -output 'fc'
SVD_TAF_FLAGS        = -server fastopt.net -f77 -reverse -forward -pure -i4 -r4 -intrinsic system,flush -l taf_svd.log -toplevel 'the_main_loop' -input 'xx_theta_dummy xx_salt_dummy xx_tr1_dummy xx_hflux_dummy xx_sflux_dummy xx_tauu_dummy xx_tauv_dummy xx_atemp_dummy xx_aqh_dummy xx_precip_dummy xx_swflux_dummy xx_swdown_dummy xx_lwflux_dummy xx_lwdown_dummy xx_evap_dummy xx_snowprecip_dummy xx_apressure_dummy xx_runoff_dummy xx_uwind_dummy xx_vwind_dummy xx_obcsn_dummy xx_obcss_dummy xx_obcsw_dummy xx_obcse_dummy xx_sst_dummy xx_sss_dummy xx_depth_dummy xx_diffkr_dummy xx_kapgm_dummy xx_kapredi_dummy xx_bottomdrag_dummy xx_efluxy_dummy xx_efluxp_dummy xx_edtaux_dummy xx_edtauy_dummy xx_uvel_dummy xx_vvel_dummy xx_etan_dummy xx_gen2d_dummy xx_gen3d_dummy xx_genarr2d_dummy xx_genarr3d_dummy xx_gentim2d_dummy xx_siarea_dummy xx_siheff_dummy xx_sihsnow_dummy xx_shifwflx_dummy xx_relaxsst_dummy xx_relaxsss_dummy xx_atemp_mean_dummy xx_aqh_mean_dummy xx_precip_mean_dummy xx_swdown_mean_dummy xx_uwind_mean_dummy xx_vwind_mean_dummy' -output 'fc'

AD_FILES =  \
 diagnostics_is_on.f \
 exch2_3d_rl.f \
 exch2_3d_rs.f \
 exch2_sm_3d_rl.f \
 exch2_uv_3d_rs.f \
 exch2_uv_3d_rl.f \
 exch2_uv_agrid_3d_rs.f \
 exch2_uv_agrid_3d_rl.f \
 exch2_uv_dgrid_3d_rs.f \
 exch2_uv_dgrid_3d_rl.f \
 exf_init_varia.f \
 exf_init_fld.f \
 exf_bulkformulae.f \
 exf_filter_rl.f \
 exf_getclim.f \
 exf_getffields.f \
 exf_getffieldrec.f \
 exf_getforcing.f \
 exf_getsurfacefluxes.f \
 exf_getyearlyfieldname.f \
 exf_interp.f \
 exf_interp_uv.f \
 exf_interpolate.f \
 exf_mapfields.f \
 exf_radiation.f \
 exf_set_fld.f \
 exf_set_gen.f \
 exf_set_obcs.f \
 exf_set_uv.f \
 exf_swapffields.f \
 exf_wind.f \
 exf_zenithangle.f \
 gad_advection.f \
 gad_biharm_r.f \
 gad_biharm_x.f \
 gad_biharm_y.f \
 gad_c2_adv_r.f \
 gad_c2_impl_r.f \
 gad_c2_adv_x.f \
 gad_c2_adv_y.f \
 gad_c4_adv_r.f \
 gad_c4_adv_x.f \
 gad_c4_adv_y.f \
 gad_calc_rhs.f \
 gad_del2.f \
 gad_diff_r.f \
 gad_diff_x.f \
 gad_diff_y.f \
 gad_dst2u1_adv_r.f \
 gad_dst2u1_impl_r.f \
 gad_dst2u1_adv_x.f \
 gad_dst2u1_adv_y.f \
 gad_dst3_adv_x.f \
 gad_dst3_adv_y.f \
 gad_dst3_adv_r.f \
 gad_dst3fl_adv_x.f \
 gad_dst3fl_adv_y.f \
 gad_dst3fl_adv_r.f \
 gad_dst3fl_impl_r.f \
 gad_fluxlimit_adv_r.f \
 gad_fluxlimit_impl_r.f \
 gad_fluxlimit_adv_x.f \
 gad_fluxlimit_adv_y.f \
 gad_grad_x.f \
 gad_grad_y.f \
 gad_implicit_r.f \
 gad_init_varia.f \
 gad_os7mp_adv_x.f \
 gad_os7mp_adv_y.f \
 gad_os7mp_adv_r.f \
 gad_read_pickup.f \
 gad_u3_adv_r.f \
 gad_u3c4_impl_r.f \
 gad_u3_adv_x.f \
 gad_u3_adv_y.f \
 gad_som_advect.f \
 gad_som_adv_r.f \
 gad_som_adv_x.f \
 gad_som_adv_y.f \
 gad_som_fill_cs_corner.f \
 gad_som_lim_r.f \
 gad_som_prep_cs_corner.f \
 gad_som_exchanges.f \
 gad_exch_som.f \
 gmredi_calc_diff.f \
 gmredi_calc_psi_b.f \
 gmredi_calc_tensor.f \
 gmredi_do_exch.f \
 gmredi_init_varia.f \
 gmredi_residual_flow.f \
 gmredi_rtransport.f \
 gmredi_slope_limit.f \
 gmredi_slope_psi.f \
 gmredi_xtransport.f \
 gmredi_ytransport.f \
 mom_calc_absvort3.f \
 mom_calc_hdiv.f \
 mom_calc_hfacz.f \
 mom_calc_ke.f \
 mom_calc_relvort3.f \
 mom_calc_strain.f \
 mom_calc_tension.f \
 mom_calc_visc.f \
 mom_hdissip.f \
 mom_quasihydrostatic.f \
 mom_u_botdrag_coeff.f \
 mom_u_coriolis_nh.f \
 mom_u_metric_nh.f \
 mom_u_rviscflux.f \
 mom_u_sidedrag.f \
 mom_v_botdrag_coeff.f \
 mom_v_coriolis_nh.f \
 mom_v_metric_nh.f \
 mom_v_rviscflux.f \
 mom_v_sidedrag.f \
 mom_calc_rtrans.f \
 mom_fluxform.f \
 mom_u_adv_uu.f \
 mom_u_adv_vu.f \
 mom_u_adv_wu.f \
 mom_u_coriolis.f \
 mom_u_del2u.f \
 mom_u_metric_cylinder.f \
 mom_u_metric_sphere.f \
 mom_u_xviscflux.f \
 mom_u_yviscflux.f \
 mom_v_adv_uv.f \
 mom_v_adv_vv.f \
 mom_v_adv_wv.f \
 mom_v_coriolis.f \
 mom_v_del2v.f \
 mom_v_metric_cylinder.f \
 mom_v_metric_sphere.f \
 mom_v_xviscflux.f \
 mom_v_yviscflux.f \
 mom_vecinv.f \
 mom_vi_coriolis.f \
 mom_vi_del2uv.f \
 mom_vi_hdissip.f \
 mom_vi_u_coriolis.f \
 mom_vi_u_coriolis_c4.f \
 mom_vi_u_grad_ke.f \
 mom_vi_u_vertshear.f \
 mom_vi_v_coriolis.f \
 mom_vi_v_coriolis_c4.f \
 mom_vi_v_grad_ke.f \
 mom_vi_v_vertshear.f \
 read_fld_xyz_rs.f \
 read_fld_xyz_rl.f \
 read_fld_xy_rs.f \
 read_fld_xy_rl.f \
 read_rec.f \
 advect.f \
 diffus.f \
 dynsolver.f \
 lsr.f \
 ostres.f \
 seaice_advection.f \
 seaice_advdiff.f \
 seaice_budget_ocean.f \
 seaice_diagnostics_state.f \
 seaice_diffusion.f \
 seaice_get_dynforcing.f \
 seaice_fake.f \
 seaice_growth.f \
 seaice_growth_adx.f \
 seaice_init_varia.f \
 seaice_model.f \
 seaice_read_pickup.f \
 seaice_solve4temp.f \
 seaice_solve4temp_adx.f \
 seaice_tracer_phys.f \
 seaice_cost_accumulate_mean.f \
 seaice_cost_areasst.f \
 seaice_cost_concentration.f \
 seaice_cost_driver.f \
 seaice_cost_export.f \
 seaice_cost_final.f \
 seaice_cost_init_varia.f \
 seaice_cost_sensi.f \
 seaice_cost_sss.f \
 seaice_cost_sst.f \
 seaice_ctrl_map_ini.f \
 cost_ice_test.f \
 seaice_calc_strainrates.f \
 seaice_calc_viscosities.f \
 seaice_dynsolver.f \
 seaice_evp.f \
 seaice_lsr.f \
 seaice_freedrift.f \
 seaice_ocean_stress.f \
 seaice_oceandrag_coeffs.f \
 seaice_map_thsice.f \
 seaice_calc_ice_strength.f \
 seaice_reg_ridge.f \
 seaice_bottomdrag_coeffs.f \
 seaice_calc_stressdiv.f \
 thsice_advdiff.f \
 thsice_advection.f \
 thsice_albedo.f \
 thsice_ave.f \
 thsice_balance_frw.f \
 thsice_calc_thickn.f \
 thsice_cost_driver.f \
 thsice_cost_final.f \
 thsice_cost_init_varia.f \
 thsice_cost_test.f \
 thsice_diffusion.f \
 thsice_do_advect.f \
 thsice_do_exch.f \
 thsice_extend.f \
 thsice_get_exf.f \
 thsice_get_ocean.f \
 thsice_get_precip.f \
 thsice_get_velocity.f \
 thsice_ini_vars.f \
 thsice_main.f \
 thsice_map_exf.f \
 thsice_solve4temp.f \
 thsice_step_fwd.f \
 thsice_step_temp.f \
 timeave_cumul_1k1t.f \
 timeave_cumul_1t.f \
 timeave_cumul_1vfc.f \
 timeave_cumul_2v.f \
 timeave_cumul_2vfc.f \
 timeave_cumulate.f \
 timeave_cumul_dif_1t.f \
 timeave_norma_2v.f \
 timeave_normalize.f \
 timeave_reset.f \
 timeave_statvars.f \
 timeave_statv_write.f \
 timeave_surf_flux.f \
 cal_addtime.f \
 cal_checkdate.f \
 cal_compdates.f \
 cal_convdate.f \
 cal_copydate.f \
 cal_fulldate.f \
 cal_getdate.f \
 cal_getmonthsrec.f \
 cal_intdays.f \
 cal_intmonths.f \
 cal_intyears.f \
 cal_isleap.f \
 cal_numints.f \
 cal_printdate.f \
 cal_printerror.f \
 cal_subdates.f \
 cal_time2dump.f \
 cal_timeinterval.f \
 cal_timepassed.f \
 cal_timestamp.f \
 cal_toseconds.f \
 different_multiple.f \
 fill_cs_corner_ag_rl.f \
 fill_cs_corner_tr_rl.f \
 fill_cs_corner_uv_rs.f \
 fill_cs_corner_uv_rl.f \
 get_periodic_interval.f \
 lef_zero.f \
 exch_sm_3d_rl.f \
 exch_3d_rs.f \
 exch_3d_rl.f \
 exch_xy_rl.f \
 exch_xy_rs.f \
 exch_xyz_rl.f \
 exch_xyz_rs.f \
 exch_uv_3d_rs.f \
 exch_uv_3d_rl.f \
 exch_uv_xy_rs.f \
 exch_uv_xy_rl.f \
 exch_uv_xyz_rs.f \
 exch_uv_xyz_rl.f \
 exch_uv_agrid_3d_rs.f \
 exch_uv_agrid_3d_rl.f \
 exch_uv_dgrid_3d_rs.f \
 exch_uv_dgrid_3d_rl.f \
 adams_bashforth2.f \
 adams_bashforth3.f \
 apply_forcing.f \
 calc_3d_diffusivity.f \
 calc_adv_flow.f \
 calc_div_ghat.f \
 calc_grad_phi_fv.f \
 calc_grad_phi_hyd.f \
 calc_grad_phi_surf.f \
 calc_ivdc.f \
 calc_phi_hyd.f \
 calc_r_star.f \
 calc_surf_dr.f \
 calc_viscosity.f \
 calc_wsurf_tr.f \
 cg2d_nsa.f \
 convective_adjustment.f \
 convective_adjustment_ini.f \
 convective_weights.f \
 convectively_mixtracer.f \
 correction_step.f \
 cycle_ab_tracer.f \
 cycle_tracer.f \
 diags_phi_hyd.f \
 diags_phi_rlow.f \
 diags_rho.f \
 do_atmospheric_phys.f \
 do_fields_blocking_exchanges.f \
 do_oceanic_phys.f \
 do_stagger_fields_exchanges.f \
 dynamics.f \
 external_fields_load.f \
 external_forcing_surf.f \
 forcing_surf_relax.f \
 find_alpha.f \
 find_rho.f \
 forward_step.f \
 freesurf_rescale_g.f \
 freeze_surface.f \
 grad_sigma.f \
 impldiff.f \
 ini_cg2d.f \
 ini_depths.f \
 ini_ffields.f \
 ini_fields.f \
 ini_forcing.f \
 ini_mixing.f \
 ini_nh_fields.f \
 ini_nlfs_vars.f \
 ini_p_ground.f \
 ini_pressure.f \
 ini_psurf.f \
 ini_salt.f \
 ini_theta.f \
 ini_dynvars.f \
 ini_vel.f \
 initialise_varia.f \
 integrate_for_w.f \
 integr_continuity.f \
 load_fields_driver.f \
 load_grid_spacing.f \
 main_do_loop.f \
 momentum_correction_step.f \
 packages_init_variables.f \
 pressure_for_eos.f \
 read_pickup.f \
 remove_mean.f \
 reset_nlfs_vars.f \
 rotate_uv2en.f \
 salt_integrate.f \
 temp_integrate.f \
 seawater.f \
 solve_for_pressure.f \
 state_summary.f \
 solve_pentadiagonal.f \
 solve_tridiagonal.f \
 taueddy_init_varia.f \
 taueddy_tendency_apply.f \
 timestep.f \
 the_main_loop.f \
 thermodynamics.f \
 timestep_tracer.f \
 tracers_correction_step.f \
 update_cg2d.f \
 update_etah.f \
 update_etaws.f \
 update_masks_etc.f \
 update_r_star.f \
 update_sigma.f \
 update_surf_dr.f \
 swfrac.f

# ... AD ...
adall: ad_exe_target
adtaf: ad_taf_output.f
adtamc: ad_tamc_output.f

ad_exe_target:
	@echo Update AD_CONFIG.h and make $(EXE_AD)
	@$(TOOLSDIR)/convert_cpp_cmd2defines "Adjoint version" -bAD_CONFIG_H -DALLOW_ADJOINT_RUN -UALLOW_TANGENTLINEAR_RUN > ad_config.template
	@cmp ad_config.template AD_CONFIG.h || cat ad_config.template > AD_CONFIG.h
	@-rm -f ad_config.template
	$(MAKE) -f $(MAKEFILE) $(EXE_AD)

ad_input_code.f: $(AD_FILES) $(AD_FLOW_FILES)
	@$(TOOLSDIR)/convert_cpp_cmd2defines "Adjoint version" -bAD_CONFIG_H -DALLOW_ADJOINT_RUN -UALLOW_TANGENTLINEAR_RUN > ad_config.template
	cmp ad_config.template AD_CONFIG.h || cat ad_config.template > AD_CONFIG.h
	@-rm -f ad_config.template
	@$(MAKE) -f $(MAKEFILE) $(F77_PP_SRC_FILES)
	@$(MAKE) -f $(MAKEFILE) $(FLOWFILES)
	cat $(FLOWFILES) $(AD_FILES) | sed -f $(TOOLSDIR)/remove_comments_sed > ad_input_code.f

adtafonly:
	$(TAF) $(AD_TAF_FLAGS) $(TAF_EXTRA) ad_input_code.f
	ls -l ad_input_code_ad.f
	cat ad_input_code_ad.f | sed -f $(TOOLSDIR)/adjoint_sed > ad_taf_output.f

# ... send 1 file to TAF ...
ad_taf_output.f: ad_input_code.f
	@-rm -f ad_input_code_ad.f ; echo ''
	$(TAF) $(AD_TAF_FLAGS) $(TAF_EXTRA) ad_input_code.f
	ls -l ad_input_code_ad.f
	cat ad_input_code_ad.f | sed -f $(TOOLSDIR)/adjoint_sed > ad_taf_output.f

$(EXE_AD): $(SPECIAL_FILES) $(H_SRC_FILES) ad_taf_output.o $(NON_AD_F77_SRC_FILES:.F=.o) $(F90_SRC_FILES:.F90=.o) $(C_SRC_FILES:.c=.o) $(EMBEDDED_FILES)
	$(LINK) -o ${EXE_AD} $(FFLAGS) $(FOPTIM) ad_taf_output.o $(NON_AD_F77_SRC_FILES:.F=.o) $(F90_SRC_FILES:.F90=.o) $(C_SRC_FILES:.c=.o) $(LIBS)

adobj: ad_taf_output.o $(NON_AD_F77_SRC_FILES:.F=.o) $(F90_SRC_FILES:.F90=.o) $(C_SRC_FILES:.c=.o)

adonlyfwd:
	patch < $(TOOLSDIR)/ad_taf_output.f.onlyfwd.diff

adtrick:
	patch < $(TOOLSDIR)/ad_taf_output.f.adtrick.diff

ad_tamc_output.f: ad_input_code.f
	$(TAMC) $(AD_TAMC_FLAGS) $(TAMC_EXTRA) ad_input_code.f
	cat ad_input_code_ad.f | sed -f $(TOOLSDIR)/adjoint_sed > ad_tamc_output.f

ad_tamc: ad_tamc_output.o $(OBJFILES)
	$(LINK) -o mitgcmuv_ad $(FFLAGS) $(FOPTIM) $(OBJFILES) ad_tamc_output.o $(LIBS)

# ... FTL ...
ftlall: ftl_exe_target
ftltaf: ftl_taf_output.f
ftltamc: ftl_tamc_output.f

ftl_exe_target:
	@echo Update AD_CONFIG.h and make $(EXE_FTL)
	@$(TOOLSDIR)/convert_cpp_cmd2defines "TangLin version" -bAD_CONFIG_H -UALLOW_ADJOINT_RUN -DALLOW_TANGENTLINEAR_RUN > ad_config.template
	@cmp ad_config.template AD_CONFIG.h || cat ad_config.template > AD_CONFIG.h
	@-rm -f ad_config.template
	$(MAKE) -f $(MAKEFILE) $(EXE_FTL)

ftl_input_code.f: $(AD_FILES)
	@$(TOOLSDIR)/convert_cpp_cmd2defines "TangLin version" -bAD_CONFIG_H -UALLOW_ADJOINT_RUN -DALLOW_TANGENTLINEAR_RUN > ad_config.template
	cmp ad_config.template AD_CONFIG.h || cat ad_config.template > AD_CONFIG.h
	@-rm -f ad_config.template
	@$(MAKE) -f $(MAKEFILE) $(F77_PP_SRC_FILES)
	@$(MAKE) -f $(MAKEFILE) $(AD_FLOW_FILES)
	cat $(AD_FLOW_FILES) $(AD_FILES) | sed -f $(TOOLSDIR)/remove_comments_sed > ftl_input_code.f

ftltafonly:
	$(TAF) $(FTL_TAF_FLAGS) $(TAF_EXTRA) ftl_input_code.f
	ls -l ftl_input_code_tl.f
	cat ftl_input_code_tl.f | sed -f $(TOOLSDIR)/adjoint_sed > ftl_taf_output.f

# ... send 1 file to TAF ...
ftl_taf_output.f: ftl_input_code.f
	@-rm -f ftl_input_code_tl.f ; echo ''
	$(TAF) $(FTL_TAF_FLAGS) $(TAF_EXTRA) ftl_input_code.f
	ls -l ftl_input_code_tl.f
	cat ftl_input_code_tl.f | sed -f $(TOOLSDIR)/adjoint_sed > ftl_taf_output.f

$(EXE_FTL): $(SPECIAL_FILES) $(H_SRC_FILES) ftl_taf_output.o $(NON_AD_F77_SRC_FILES:.F=.o) $(F90_SRC_FILES:.F90=.o) $(C_SRC_FILES:.c=.o) $(EMBEDDED_FILES)
	$(LINK) -o ${EXE_FTL} $(FFLAGS) $(FOPTIM) ftl_taf_output.o $(NON_AD_F77_SRC_FILES:.F=.o) $(F90_SRC_FILES:.F90=.o) $(C_SRC_FILES:.c=.o) $(LIBS)

ftl_tamc_output.f: ftl_input_code.f
	$(TAMC) $(FTL_TAMC_FLAGS) $(TAMC_EXTRA) ftl_input_code.f
	cat ftl_input_code_ftl.f | sed -f $(TOOLSDIR)/adjoint_sed > ftl_tamc_output.f

ftl_tamc: ftl_tamc_output.o $(OBJFILES)
	$(LINK) -o mitgcmuv_ftl $(FFLAGS) $(FOPTIM) $(OBJFILES) ftl_tamc_output.o $(LIBS)

# ... SVD ...
svdtaf: ad_taf_output.f ftl_taf_output.f
	@echo "--->>> Only ran TAF to generate SVD code!    <<<---"
	@echo "--->>> Do make svdall afterwards to compile. <<<---"
svdall: svd_touch svd_taf

svd_taf: $(OBJFILES)
	$(LINK) -o mitgcmuv_svd $(FFLAGS) $(FOPTIM) $(OBJFILES) ad_taf_output.o ftl_taf_output.o $(LIBS)

	@echo "--->>> Only COMPILE svd code! <<<---"
	@echo "--->>> Assumes you previously <<<---"
	@echo "--->>> did make svdtaf        <<<---"

svd_touch:
	@echo "--->>> Only COMPILE svd code! <<<---"
	@echo "--->>> Assumes you previously <<<---"
	@echo "--->>> did make svdtaf        <<<---"
	touch ad_taf_output.f ftl_taf_output.f
	$(FC) $(FFLAGS) $(FOPTIM) -c ad_taf_output.f
	$(FC) $(FFLAGS) $(FOPTIM) -c ftl_taf_output.f
	@$(TOOLSDIR)/convert_cpp_cmd2defines "SVD version" -bAD_CONFIG_H -UALLOW_ADJOINT_RUN -DALLOW_TANGENTLINEAR_RUN > ad_config.template
	cmp ad_config.template AD_CONFIG.h || cat ad_config.template > AD_CONFIG.h
	@-rm -f ad_config.template

seaice_growth.o: seaice_growth.f
	$(FC) $(FFLAGS) $(NOOPTFLAGS) -c $<
calc_oce_mxlayer.o: calc_oce_mxlayer.f
	$(FC) $(FFLAGS) $(NOOPTFLAGS) -c $<
fizhi_lsm.o: fizhi_lsm.f
	$(FC) $(FFLAGS) $(NOOPTFLAGS) -c $<
fizhi_clockstuff.o: fizhi_clockstuff.f
	$(FC) $(FFLAGS) $(NOOPTFLAGS) -c $<
ini_parms.o: ini_parms.f
	$(FC) $(FFLAGS) $(NOOPTFLAGS) -c $<
obcs_init_fixed.o: obcs_init_fixed.f
	$(FC) $(FFLAGS) $(NOOPTFLAGS) -c $<
# This section creates symbolic links


#  These files are linked from ../code_geos_bulk ( aka ../code_geos_bulk )
 EXF_OPTIONS.h MAPL_CONST.h exf_geos_bulkf.F exf_getforcing.F LINADJ.F90 PHI.F90 PSI.F90 ZCSUB.F90 helfsurface.F90 :
	if [ ! -L $@ ]; then $(LN) ../code_geos_bulk/$@ $@; fi

#  These files are linked from ../code ( aka ../code )
 CPP_OPTIONS.h DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h SEAICE_OPTIONS.h SIZE.h :
	if [ ! -L $@ ]; then $(LN) ../code/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/bulk_force ( aka ../../../pkg/bulk_force )
 BULKF.h BULKF_CONSERV.h BULKF_INT.h BULKF_PARAMS.h BULKF_TAVE.h BULK_FORCE_OPTIONS.h bulkf_ave.F bulkf_fields_load.F bulkf_flux_adjust.F bulkf_forcing.F bulkf_formula_aim.F bulkf_formula_lanl.F bulkf_formula_lay.F bulkf_init_varia.F bulkf_output.F bulkf_readparms.F bulkf_sh2rh_aim.F :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/bulk_force/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/debug ( aka ../../../pkg/debug )
 DEBUG_OPTIONS.h chksum_tiled.F debug_call.F debug_cs_corner_uv.F debug_enter.F debug_fld_stats_rl.F debug_fld_stats_rs.F debug_leave.F debug_msg.F debug_stats_rl.F debug_stats_rs.F fill_in_corners_rl.F write_fullarray_rl.F write_fullarray_rs.F debug_ad.flow :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/debug/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/diagnostics ( aka ../../../pkg/diagnostics )
 DIAGNOSTICS.h DIAGNOSTICS_CALC.h DIAGSTATS_REGIONS.h diag_calc_psivel.F diag_cg2d.F diag_vegtile_fill.F diagnostics_addtolist.F diagnostics_calc_phivel.F diagnostics_check.F diagnostics_clear.F diagnostics_fill.F diagnostics_fill_field.F diagnostics_fill_rs.F diagnostics_fill_state.F diagnostics_fract_fill.F diagnostics_ini_io.F diagnostics_init_early.F diagnostics_init_fixed.F diagnostics_init_varia.F diagnostics_interp_p2p.F diagnostics_interp_vert.F diagnostics_is_on.F diagnostics_list_check.F diagnostics_main_init.F diagnostics_mnc_out.F diagnostics_out.F diagnostics_read_pickup.F diagnostics_readparms.F diagnostics_scale_fill.F diagnostics_scale_fill_rs.F diagnostics_set_calc.F diagnostics_set_levels.F diagnostics_set_pointers.F diagnostics_setdiag.F diagnostics_status_error.F diagnostics_sum_levels.F diagnostics_summary.F diagnostics_switch_onoff.F diagnostics_utils.F diagnostics_write.F diagnostics_write_adj.F diagnostics_write_pickup.F diagstats_ascii_out.F diagstats_calc.F diagstats_clear.F diagstats_close_io.F diagstats_fill.F diagstats_global.F diagstats_ini_io.F diagstats_local.F diagstats_mnc_out.F diagstats_others_calc.F diagstats_output.F diagstats_set_pointers.F diagstats_set_regions.F diagstats_setdiag.F diagnostics_ad.flow :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/diagnostics/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/exch2 ( aka ../../../pkg/exch2 )
 W2_EXCH2_BUFFER.h W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h exch2_3d_r4.F exch2_3d_r8.F exch2_3d_rl.F exch2_3d_rs.F exch2_ad_get_r41.F exch2_ad_get_r42.F exch2_ad_get_r81.F exch2_ad_get_r82.F exch2_ad_get_rl1.F exch2_ad_get_rl2.F exch2_ad_get_rs1.F exch2_ad_get_rs2.F exch2_ad_put_r41.F exch2_ad_put_r42.F exch2_ad_put_r81.F exch2_ad_put_r82.F exch2_ad_put_rl1.F exch2_ad_put_rl2.F exch2_ad_put_rs1.F exch2_ad_put_rs2.F exch2_check_depths.F exch2_get_r41.F exch2_get_r42.F exch2_get_r81.F exch2_get_r82.F exch2_get_rl1.F exch2_get_rl2.F exch2_get_rs1.F exch2_get_rs2.F exch2_get_scal_bounds.F exch2_get_uv_bounds.F exch2_put_r41.F exch2_put_r42.F exch2_put_r81.F exch2_put_r82.F exch2_put_rl1.F exch2_put_rl2.F exch2_put_rs1.F exch2_put_rs2.F exch2_r41_cube.F exch2_r41_cube_ad.F exch2_r42_cube.F exch2_r42_cube_ad.F exch2_r81_cube.F exch2_r81_cube_ad.F exch2_r82_cube.F exch2_r82_cube_ad.F exch2_recv_r41.F exch2_recv_r42.F exch2_recv_r81.F exch2_recv_r82.F exch2_recv_rl1.F exch2_recv_rl2.F exch2_recv_rs1.F exch2_recv_rs2.F exch2_rl1_cube.F exch2_rl1_cube_ad.F exch2_rl2_cube.F exch2_rl2_cube_ad.F exch2_rs1_cube.F exch2_rs1_cube_ad.F exch2_rs2_cube.F exch2_rs2_cube_ad.F exch2_s3d_r4.F exch2_s3d_r8.F exch2_s3d_rl.F exch2_s3d_rs.F exch2_send_r41.F exch2_send_r42.F exch2_send_r81.F exch2_send_r82.F exch2_send_rl1.F exch2_send_rl2.F exch2_send_rs1.F exch2_send_rs2.F exch2_sm_3d_r4.F exch2_sm_3d_r8.F exch2_sm_3d_rl.F exch2_sm_3d_rs.F exch2_uv_3d_r4.F exch2_uv_3d_r8.F exch2_uv_3d_rl.F exch2_uv_3d_rs.F exch2_uv_agrid_3d_r4.F exch2_uv_agrid_3d_r8.F exch2_uv_agrid_3d_rl.F exch2_uv_agrid_3d_rs.F exch2_uv_bgrid_3d_r4.F exch2_uv_bgrid_3d_r8.F exch2_uv_bgrid_3d_rl.F exch2_uv_bgrid_3d_rs.F exch2_uv_cgrid_3d_r4.F exch2_uv_cgrid_3d_r8.F exch2_uv_cgrid_3d_rl.F exch2_uv_cgrid_3d_rs.F exch2_uv_dgrid_3d_r4.F exch2_uv_dgrid_3d_r8.F exch2_uv_dgrid_3d_rl.F exch2_uv_dgrid_3d_rs.F exch2_z_3d_r4.F exch2_z_3d_r8.F exch2_z_3d_rl.F exch2_z_3d_rs.F w2_cumulsum_z_tile.F w2_e2setup.F w2_eeboot.F w2_map_procs.F w2_print_comm_sequence.F w2_print_e2setup.F w2_readparms.F w2_set_cs6_facets.F w2_set_f2f_index.F w2_set_gen_facets.F w2_set_map_cumsum.F w2_set_map_tiles.F w2_set_myown_facets.F w2_set_single_facet.F w2_set_tile2tiles.F exch2.flow :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/exch2/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/exf ( aka ../../../pkg/exf )
 EXF_CONSTANTS.h EXF_FIELDS.h EXF_INTERP_PARAM.h EXF_INTERP_SIZE.h EXF_PARAM.h exf_ad_check_lev1_dir.h exf_ad_check_lev2_dir.h exf_ad_check_lev3_dir.h exf_ad_check_lev4_dir.h exf_ad_dump.F exf_adjoint_snapshots.F exf_adjoint_snapshots__g.F exf_adjoint_snapshots_ad.F exf_bulkformulae.F exf_check.F exf_check_range.F exf_diagnostics_fill.F exf_diagnostics_init.F exf_filter_rl.F exf_getclim.F exf_getffield_start.F exf_getffieldrec.F exf_getffields.F exf_getfield_start.F exf_getsurfacefluxes.F exf_getyearlyfieldname.F exf_init_fixed.F exf_init_fld.F exf_init_interp.F exf_init_varia.F exf_interp.F exf_interp_read.F exf_interp_uv.F exf_interpolate.F exf_mapfields.F exf_monitor.F exf_monitor_ad.F exf_radiation.F exf_readparms.F exf_set_fld.F exf_set_gen.F exf_set_obcs.F exf_set_uv.F exf_summary.F exf_swapffields.F exf_weight_sfx_diags.F exf_wind.F exf_zenithangle.F exf_zenithangle_table.F exf_ad.flow :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/exf/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/generic_advdiff ( aka ../../../pkg/generic_advdiff )
 GAD.h GAD_FLUX_LIMITER.h GAD_OPTIONS.h GAD_SOM_VARS.h gad_ad_check_lev1_dir.h gad_ad_check_lev2_dir.h gad_ad_check_lev3_dir.h gad_ad_check_lev4_dir.h gad_advection.F gad_advscheme.F gad_biharm_r.F gad_biharm_x.F gad_biharm_y.F gad_c2_adv_r.F gad_c2_adv_x.F gad_c2_adv_y.F gad_c2_impl_r.F gad_c4_adv_r.F gad_c4_adv_x.F gad_c4_adv_y.F gad_calc_rhs.F gad_check.F gad_del2.F gad_diagnostics_init.F gad_diagnostics_state.F gad_diff_r.F gad_diff_x.F gad_diff_y.F gad_dst2u1_adv_r.F gad_dst2u1_adv_x.F gad_dst2u1_adv_y.F gad_dst2u1_impl_r.F gad_dst3_adv_r.F gad_dst3_adv_x.F gad_dst3_adv_y.F gad_dst3fl_adv_r.F gad_dst3fl_adv_x.F gad_dst3fl_adv_y.F gad_dst3fl_impl_r.F gad_exch_som.F gad_fluxlimit_adv_r.F gad_fluxlimit_adv_x.F gad_fluxlimit_adv_y.F gad_fluxlimit_impl_r.F gad_grad_x.F gad_grad_y.F gad_implicit_r.F gad_init_fixed.F gad_init_varia.F gad_os7mp_adv_r.F gad_os7mp_adv_x.F gad_os7mp_adv_y.F gad_osc_hat_r.F gad_osc_hat_x.F gad_osc_hat_y.F gad_osc_mul_r.F gad_osc_mul_x.F gad_osc_mul_y.F gad_plm_fun.F gad_ppm_adv_r.F gad_ppm_adv_x.F gad_ppm_adv_y.F gad_ppm_flx_r.F gad_ppm_flx_x.F gad_ppm_flx_y.F gad_ppm_fun.F gad_ppm_hat_r.F gad_ppm_hat_x.F gad_ppm_hat_y.F gad_ppm_p3e_r.F gad_ppm_p3e_x.F gad_ppm_p3e_y.F gad_pqm_adv_r.F gad_pqm_adv_x.F gad_pqm_adv_y.F gad_pqm_flx_r.F gad_pqm_flx_x.F gad_pqm_flx_y.F gad_pqm_fun.F gad_pqm_hat_r.F gad_pqm_hat_x.F gad_pqm_hat_y.F gad_pqm_p5e_r.F gad_pqm_p5e_x.F gad_pqm_p5e_y.F gad_read_pickup.F gad_som_adv_r.F gad_som_adv_x.F gad_som_adv_y.F gad_som_advect.F gad_som_exchanges.F gad_som_fill_cs_corner.F gad_som_lim_r.F gad_som_prep_cs_corner.F gad_u3_adv_r.F gad_u3_adv_x.F gad_u3_adv_y.F gad_u3c4_impl_r.F gad_write_pickup.F salt_fill.F :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/generic_advdiff/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/gmredi ( aka ../../../pkg/gmredi )
 GMREDI.h GMREDI_OPTIONS.h GMREDI_TAVE.h gmredi_calc_diff.F gmredi_calc_eigs.F gmredi_calc_psi_b.F gmredi_calc_psi_bvp.F gmredi_calc_qgleith.F gmredi_calc_tensor.F gmredi_calc_urms.F gmredi_check.F gmredi_diagnostics_fill.F gmredi_diagnostics_impl.F gmredi_diagnostics_init.F gmredi_do_exch.F gmredi_init_fixed.F gmredi_init_varia.F gmredi_k3d.F gmredi_mnc_init.F gmredi_output.F gmredi_read_pickup.F gmredi_readparms.F gmredi_residual_flow.F gmredi_rtransport.F gmredi_slope_limit.F gmredi_slope_psi.F gmredi_write_pickup.F gmredi_xtransport.F gmredi_ytransport.F submeso_calc_psi.F gmredi_ad.flow :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/gmredi/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/mdsio ( aka ../../../pkg/mdsio )
 MDSIO_BUFF_3D.h MDSIO_BUFF_WH.h MDSIO_OPTIONS.h mdsio_buffertorl.F mdsio_buffertors.F mdsio_check4file.F mdsio_facef_read.F mdsio_gl.F mdsio_gl_slice.F mdsio_pass_r4torl.F mdsio_pass_r4tors.F mdsio_pass_r8torl.F mdsio_pass_r8tors.F mdsio_rd_rec_rl.F mdsio_rd_rec_rs.F mdsio_read_field.F mdsio_read_meta.F mdsio_read_section.F mdsio_read_tape.F mdsio_read_whalos.F mdsio_readvec_loc.F mdsio_rw_field.F mdsio_rw_slice.F mdsio_seg4torl.F mdsio_seg4tors.F mdsio_seg8torl.F mdsio_seg8tors.F mdsio_segxtorx_2d.F mdsio_wr_metafiles.F mdsio_wr_rec_rl.F mdsio_wr_rec_rs.F mdsio_write_field.F mdsio_write_meta.F mdsio_write_section.F mdsio_write_tape.F mdsio_write_whalos.F mdsio_writelocal.F mdsio_writevec_loc.F mdsio_ad.flow :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/mdsio/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/mnc ( aka ../../../pkg/mnc )
 MNC_BUFF.h MNC_COMMON.h MNC_CW_READWRITE_I.F MNC_CW_READWRITE_RL.F MNC_CW_READWRITE_RS.F MNC_ID_HEADER.h MNC_OPTIONS.h MNC_PARAMS.h MNC_SIZE.h mnc_create_dir.c mnc_cw_citer.F mnc_cw_cvars.F mnc_cw_fsize.c mnc_cw_init.F mnc_cw_missingvals.F mnc_cw_model_attr.F mnc_cw_udim.F mnc_cw_write_grid_info.F mnc_cwrapper.F mnc_dim.F mnc_dump.F mnc_file.F mnc_grid.F mnc_init.F mnc_readparms.F mnc_update_time.F mnc_utils.F mnc_var.F mnc_ad.flow :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/mnc/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/mom_common ( aka ../../../pkg/mom_common )
 MOM_COMMON_OPTIONS.h MOM_VISC.h mom_calc_3d_strain.F mom_calc_absvort3.F mom_calc_hdiv.F mom_calc_hfacz.F mom_calc_ke.F mom_calc_relvort3.F mom_calc_smag_3d.F mom_calc_strain.F mom_calc_tension.F mom_calc_visc.F mom_diagnostics_init.F mom_hdissip.F mom_init_fixed.F mom_quasihydrostatic.F mom_u_botdrag_coeff.F mom_u_coriolis_nh.F mom_u_implicit_r.F mom_u_metric_nh.F mom_u_rviscflux.F mom_u_sidedrag.F mom_uv_smag_3d.F mom_v_botdrag_coeff.F mom_v_coriolis_nh.F mom_v_implicit_r.F mom_v_metric_nh.F mom_v_rviscflux.F mom_v_sidedrag.F mom_visc_qgl_limit.F mom_visc_qgl_stretch.F mom_w_coriolis_nh.F mom_w_metric_nh.F mom_w_sidedrag.F mom_w_smag_3d.F :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/mom_common/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/mom_fluxform ( aka ../../../pkg/mom_fluxform )
 MOM_FLUXFORM.h MOM_FLUXFORM_OPTIONS.h mom_calc_rtrans.F mom_fluxform.F mom_u_adv_uu.F mom_u_adv_vu.F mom_u_adv_wu.F mom_u_coriolis.F mom_u_del2u.F mom_u_metric_cylinder.F mom_u_metric_sphere.F mom_u_xviscflux.F mom_u_yviscflux.F mom_uv_boundary.F mom_v_adv_uv.F mom_v_adv_vv.F mom_v_adv_wv.F mom_v_coriolis.F mom_v_del2v.F mom_v_metric_cylinder.F mom_v_metric_sphere.F mom_v_xviscflux.F mom_v_yviscflux.F :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/mom_fluxform/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/mom_vecinv ( aka ../../../pkg/mom_vecinv )
 MOM_VECINV_OPTIONS.h mom_vecinv.F mom_vi_coriolis.F mom_vi_del2uv.F mom_vi_hdissip.F mom_vi_u_coriolis.F mom_vi_u_coriolis_c4.F mom_vi_u_grad_ke.F mom_vi_u_vertshear.F mom_vi_v_coriolis.F mom_vi_v_coriolis_c4.F mom_vi_v_grad_ke.F mom_vi_v_vertshear.F :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/mom_vecinv/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/monitor ( aka ../../../pkg/monitor )
 MONITOR.h MONITOR_OPTIONS.h mon_advcfl.F mon_advcflw.F mon_advcflw2.F mon_calc_advcfl.F mon_calc_stats_rl.F mon_calc_stats_rs.F mon_init.F mon_ke.F mon_out.F mon_printstats_rl.F mon_printstats_rs.F mon_set_iounit.F mon_set_pref.F mon_solution.F mon_stats_latbnd_rl.F mon_stats_rl.F mon_stats_rs.F mon_surfcor.F mon_vort3.F mon_writestats_rl.F mon_writestats_rs.F monitor.F monitor_ad.F monitor_g.F monitor_ad.flow :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/monitor/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/rw ( aka ../../../pkg/rw )
 RW_MFLDS.h RW_OPTIONS.h get_write_global_fld.F read_fld_xy_rl.F read_fld_xy_rs.F read_fld_xyz_rl.F read_fld_xyz_rs.F read_glvec_rl.F read_glvec_rs.F read_mflds.F read_rec.F rw_get_suffix.F set_write_global_fld.F write_fld_3d_rl.F write_fld_3d_rs.F write_fld_s3d_rl.F write_fld_s3d_rs.F write_fld_xy_rl.F write_fld_xy_rs.F write_fld_xyz_rl.F write_fld_xyz_rs.F write_glvec_rl.F write_glvec_rs.F write_local_rl.F write_local_rs.F write_rec.F rw_ad.flow :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/rw/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/seaice ( aka ../../../pkg/seaice )
 SEAICE.h SEAICE_COST.h SEAICE_PARAMS.h SEAICE_SIZE.h SEAICE_TAVE.h SEAICE_TRACER.h advect.F cost_ice_test.F diffus.F dynsolver.F lsr.F ostres.F seaice_ad_check_lev1_dir.h seaice_ad_check_lev2_dir.h seaice_ad_check_lev3_dir.h seaice_ad_check_lev4_dir.h seaice_ad_dump.F seaice_advdiff.F seaice_advection.F seaice_bottomdrag_coeffs.F seaice_budget_ocean.F seaice_calc_ice_strength.F seaice_calc_lhs.F seaice_calc_residual.F seaice_calc_rhs.F seaice_calc_strainrates.F seaice_calc_stressdiv.F seaice_calc_viscosities.F seaice_check.F seaice_check_pickup.F seaice_cost_accumulate_mean.F seaice_cost_areasst.F seaice_cost_concentration.F seaice_cost_driver.F seaice_cost_export.F seaice_cost_final.F seaice_cost_init_fixed.F seaice_cost_init_varia.F seaice_cost_sensi.F seaice_cost_sss.F seaice_cost_sst.F seaice_cost_weights.F seaice_ctrl_map_ini.F seaice_diagnostics_init.F seaice_diagnostics_state.F seaice_diffusion.F seaice_do_ridging.F seaice_dynsolver.F seaice_evp.F seaice_fake.F seaice_fgmres.F seaice_freedrift.F seaice_get_dynforcing.F seaice_growth.F seaice_growth_adx.F seaice_init_fixed.F seaice_init_varia.F seaice_itd_pickup.F seaice_itd_redist.F seaice_itd_remap.F seaice_itd_sum.F seaice_jacvec.F seaice_jfnk.F seaice_krylov.F seaice_lsr.F seaice_map_thsice.F seaice_mnc_init.F seaice_model.F seaice_mom_advection.F seaice_monitor.F seaice_monitor_ad.F seaice_obcs_output.F seaice_ocean_stress.F seaice_oceandrag_coeffs.F seaice_output.F seaice_preconditioner.F seaice_prepare_ridging.F seaice_read_pickup.F seaice_readparms.F seaice_reg_ridge.F seaice_solve4temp.F seaice_solve4temp_adx.F seaice_summary.F seaice_tracer_phys.F seaice_turnoff_io.F seaice_write_pickup.F seaice.flow :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/seaice/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/thsice ( aka ../../../pkg/thsice )
 THSICE_COST.h THSICE_DEBUG.h THSICE_OPTIONS.h THSICE_PARAMS.h THSICE_SIZE.h THSICE_TAVE.h THSICE_VARS.h thsice_ad_check_lev1_dir.h thsice_ad_check_lev2_dir.h thsice_ad_check_lev3_dir.h thsice_ad_check_lev4_dir.h thsice_advdiff.F thsice_advection.F thsice_albedo.F thsice_ave.F thsice_balance_frw.F thsice_calc_thickn.F thsice_check.F thsice_check_conserv.F thsice_cost_driver.F thsice_cost_final.F thsice_cost_init_varia.F thsice_cost_test.F thsice_diagnostics_init.F thsice_diagnostics_state.F thsice_diffusion.F thsice_do_advect.F thsice_do_exch.F thsice_extend.F thsice_get_bulkf.F thsice_get_exf.F thsice_get_ocean.F thsice_get_precip.F thsice_get_velocity.F thsice_impl_temp.F thsice_ini_vars.F thsice_init_fixed.F thsice_main.F thsice_map_exf.F thsice_mnc_init.F thsice_monitor.F thsice_output.F thsice_read_pickup.F thsice_readparms.F thsice_reshape_layers.F thsice_salt_plume.F thsice_slab_ocean.F thsice_solve4temp.F thsice_step_fwd.F thsice_step_temp.F thsice_test_addfluid.h thsice_turnoff_io.F thsice_write_pickup.F thsice_ad.flow :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/thsice/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/timeave ( aka ../../../pkg/timeave )
 TIMEAVE_OPTIONS.h TIMEAVE_STATV.h timeave_cumul_1k1t.F timeave_cumul_1t.F timeave_cumul_1vfc.F timeave_cumul_2v.F timeave_cumul_2vfc.F timeave_cumul_dif_1t.F timeave_cumulate.F timeave_init_fixed.F timeave_norma_2v.F timeave_normalize.F timeave_reset.F timeave_statv_write.F timeave_statvars.F timeave_surf_flux.F :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/timeave/$@ $@; fi

#  These files are linked from $(ROOTDIR)/pkg/cal ( aka ../../../pkg/cal )
 CAL_OPTIONS.h cal.h cal_addtime.F cal_checkdate.F cal_compdates.F cal_convdate.F cal_copydate.F cal_daysformonth.F cal_dayspermonth.F cal_fulldate.F cal_getdate.F cal_getmonthsrec.F cal_init_fixed.F cal_intdays.F cal_intmonths.F cal_intyears.F cal_isleap.F cal_monthsforyear.F cal_monthsperyear.F cal_numints.F cal_printdate.F cal_printerror.F cal_readparms.F cal_set.F cal_stepsforday.F cal_stepsperday.F cal_subdates.F cal_summary.F cal_time2dump.F cal_timeinterval.F cal_timepassed.F cal_timestamp.F cal_toseconds.F cal_weekday.F :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/pkg/cal/$@ $@; fi

#  These files are linked from $(ROOTDIR)/eesupp/src ( aka ../../../eesupp/src )
 all_proc_die.F bar2.F bar_check.F barrier.F check_threads.F comm_stats.F cumulsum_z_tile.F diff_phase_multiple.F different_multiple.F eeboot.F eeboot_minimal.F eedata_example.F eedie.F eeintro_msg.F eeset_parms.F eewrite_eeenv.F exch0_r4.F exch0_r8.F exch0_rl.F exch0_rs.F exch1_bg_r4_cube.F exch1_bg_r8_cube.F exch1_bg_rl_cube.F exch1_bg_rs_cube.F exch1_r4.F exch1_r4_cube.F exch1_r8.F exch1_r8_cube.F exch1_rl.F exch1_rl_ad.F exch1_rl_cube.F exch1_rl_cube_ad.F exch1_rs.F exch1_rs_ad.F exch1_rs_cube.F exch1_rs_cube_ad.F exch1_uv_r4_cube.F exch1_uv_r8_cube.F exch1_uv_rl_cube.F exch1_uv_rs_cube.F exch1_z_r4_cube.F exch1_z_r8_cube.F exch1_z_rl_cube.F exch1_z_rs_cube.F exch_3d_r4.F exch_3d_r8.F exch_3d_rl.F exch_3d_rs.F exch_cycle_ebl.F exch_init.F exch_r4_recv_get_x.F exch_r4_recv_get_y.F exch_r4_send_put_x.F exch_r4_send_put_y.F exch_r8_recv_get_x.F exch_r8_recv_get_y.F exch_r8_send_put_x.F exch_r8_send_put_y.F exch_rl_recv_get_x.F exch_rl_recv_get_y.F exch_rl_send_put_x.F exch_rl_send_put_y.F exch_rs_recv_get_x.F exch_rs_recv_get_y.F exch_rs_send_put_x.F exch_rs_send_put_y.F exch_s3d_r4.F exch_s3d_r8.F exch_s3d_rl.F exch_s3d_rs.F exch_sm_3d_r4.F exch_sm_3d_r8.F exch_sm_3d_rl.F exch_sm_3d_rs.F exch_uv_3d_r4.F exch_uv_3d_r8.F exch_uv_3d_rl.F exch_uv_3d_rs.F exch_uv_agrid_3d_r4.F exch_uv_agrid_3d_r8.F exch_uv_agrid_3d_rl.F exch_uv_agrid_3d_rs.F exch_uv_bgrid_3d_r4.F exch_uv_bgrid_3d_r8.F exch_uv_bgrid_3d_rl.F exch_uv_bgrid_3d_rs.F exch_uv_dgrid_3d_r4.F exch_uv_dgrid_3d_r8.F exch_uv_dgrid_3d_rl.F exch_uv_dgrid_3d_rs.F exch_uv_xy_r4.F exch_uv_xy_r8.F exch_uv_xy_rl.F exch_uv_xy_rs.F exch_uv_xyz_r4.F exch_uv_xyz_r8.F exch_uv_xyz_rl.F exch_uv_xyz_rs.F exch_xy_r4.F exch_xy_r8.F exch_xy_rl.F exch_xy_rs.F exch_xyz_r4.F exch_xyz_r8.F exch_xyz_rl.F exch_xyz_rs.F exch_z_3d_r4.F exch_z_3d_r8.F exch_z_3d_rl.F exch_z_3d_rs.F fill_cs_corner_ag_rl.F fill_cs_corner_tr_rl.F fill_cs_corner_uv_rl.F fill_cs_corner_uv_rs.F fool_the_compiler.F gather_2d_r4.F gather_2d_r8.F gather_2d_wh_r4.F gather_2d_wh_r8.F gather_vec_r4.F gather_vec_r8.F gather_xz.F gather_yz.F get_periodic_interval.F global_max.F global_sum.F global_sum_singlecpu.F global_sum_tile.F global_vec_sum.F gsl_ieee_env.c gsum.F ini_communication_patterns.F ini_procs.F ini_threading_environment.F lef_zero.F main.F master_cpu_io.F master_cpu_thread.F mds_byteswapi4.F mds_byteswapr4.F mds_byteswapr8.F mds_flush.F mds_reclen.F mdsfindunit.F memsync.F nml_change_syntax.F nml_set_terminator.F open_copy_data_file.F print.F ptwrapper.c reset_halo.F scatter_2d_r4.F scatter_2d_r8.F scatter_2d_wh_r4.F scatter_2d_wh_r8.F scatter_vec_r4.F scatter_vec_r8.F scatter_xz.F scatter_yz.F setdir.c setrlstk.c sigreg.c stop_if_error.F tim.c timer_stats.c timers.F utils.F write_utils.F eesupp.flow exch1_ad.flow :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/eesupp/src/$@ $@; fi

#  These files are linked from $(ROOTDIR)/model/src ( aka ../../../model/src )
 adams_bashforth2.F adams_bashforth3.F add_walls2masks.F apply_forcing.F calc_3d_diffusivity.F calc_adv_flow.F calc_div_ghat.F calc_eddy_stress.F calc_grad_phi_fv.F calc_grad_phi_hyd.F calc_grad_phi_surf.F calc_grid_angles.F calc_gw.F calc_ivdc.F calc_oce_mxlayer.F calc_phi_hyd.F calc_r_star.F calc_surf_dr.F calc_viscosity.F calc_wsurf_tr.F cg2d.F cg2d_ex0.F cg2d_nsa.F cg2d_sr.F cg3d.F cg3d_ex0.F check_pickup.F config_check.F config_summary.F convective_adjustment.F convective_adjustment_ini.F convective_weights.F convectively_mixtracer.F correction_step.F cycle_ab_tracer.F cycle_tracer.F diags_oceanic_surf_flux.F diags_phi_hyd.F diags_phi_rlow.F diags_rho.F do_atmospheric_phys.F do_fields_blocking_exchanges.F do_oceanic_phys.F do_stagger_fields_exchanges.F do_statevars_diags.F do_statevars_tave.F do_the_model_io.F do_write_pickup.F dynamics.F external_fields_load.F external_forcing.F external_forcing_surf.F find_alpha.F find_hyd_press_1d.F find_rho.F forcing_surf_relax.F forward_step.F freesurf_rescale_g.F freeze_surface.F grad_sigma.F gsw_teos10.F impldiff.F ini_cartesian_grid.F ini_cg2d.F ini_cg3d.F ini_cori.F ini_curvilinear_grid.F ini_cylinder_grid.F ini_depths.F ini_dynvars.F ini_eos.F ini_ffields.F ini_fields.F ini_forcing.F ini_global_domain.F ini_grid.F ini_linear_phisurf.F ini_local_grid.F ini_masks_etc.F ini_mixing.F ini_mnc_vars.F ini_model_io.F ini_nh_fields.F ini_nh_vars.F ini_nlfs_vars.F ini_p_ground.F ini_parms.F ini_pressure.F ini_psurf.F ini_salt.F ini_sigma_hfac.F ini_spherical_polar_grid.F ini_theta.F ini_vel.F ini_vertical_grid.F initialise_fixed.F initialise_varia.F integr_continuity.F integrate_for_w.F load_fields_driver.F load_grid_spacing.F load_ref_files.F main_do_loop.F momentum_correction_step.F packages_boot.F packages_check.F packages_error_msg.F packages_init_fixed.F packages_init_variables.F packages_print_msg.F packages_readparms.F packages_unused_msg.F packages_write_pickup.F plot_field.F port_rand.F post_cg3d.F pre_cg3d.F pressure_for_eos.F read_pickup.F remove_mean.F reset_nlfs_vars.F rotate_spherical_polar_grid.F rotate_uv2en.F salt_integrate.F seawater.F set_defaults.F set_grid_factors.F set_parms.F set_ref_state.F solve_for_pressure.F solve_pentadiagonal.F solve_tridiagonal.F solve_uv_tridiago.F state_summary.F swfrac.F taueddy_init_varia.F taueddy_tendency_apply.F temp_integrate.F the_main_loop.F the_model_main.F thermodynamics.F timestep.F timestep_tracer.F timestep_wvel.F tracers_correction_step.F tracers_iigw_correction.F turnoff_model_io.F update_cg2d.F update_etah.F update_etaws.F update_masks_etc.F update_r_star.F update_sigma.F update_surf_dr.F write_grid.F write_pickup.F write_state.F :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/model/src/$@ $@; fi

#  These files are linked from $(ROOTDIR)/eesupp/inc ( aka ../../../eesupp/inc )
 BAR2.h BARRIER.h CPP_EEMACROS.h CPP_EEOPTIONS.h CUMULSUM.h DEF_IN_MAKEFILE.h EEBUFF_SCPU.h EEPARAMS.h EESUPPORT.h EXCH.h GLOBAL_MAX.h GLOBAL_SUM.h MAIN_PDIRECTIVES1.h MAIN_PDIRECTIVES2.h MPI_INFO.h SIGREG.h :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/eesupp/inc/$@ $@; fi

#  These files are linked from $(ROOTDIR)/model/inc ( aka ../../../model/inc )
 CG2D.h CG3D.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h EOS.h FCORI_MACROS.h FFIELDS.h GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h NH_VARS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h RESTART.h SET_GRID.h SOLVE_FOR_PRESSURE.h SOLVE_FOR_PRESSURE3D.h SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h THE_MODEL_COMMON_BLOCKS.h XC_MACROS.h YC_MACROS.h :
	if [ ! -L $@ ]; then $(LN) $(ROOTDIR)/model/inc/$@ $@; fi


# DO NOT DELETE


MNC_CW_READWRITE_I.f: /nasa/netcdf/4.4.1.1_mpt/include/netcdf.inc
MNC_CW_READWRITE_I.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
MNC_CW_READWRITE_I.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h MNC_BUFF.h
MNC_CW_READWRITE_I.f: MNC_COMMON.h MNC_ID_HEADER.h MNC_OPTIONS.h MNC_PARAMS.h
MNC_CW_READWRITE_I.f: MNC_SIZE.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
MNC_CW_READWRITE_RL.f: /nasa/netcdf/4.4.1.1_mpt/include/netcdf.inc
MNC_CW_READWRITE_RL.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
MNC_CW_READWRITE_RL.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h MNC_BUFF.h
MNC_CW_READWRITE_RL.f: MNC_COMMON.h MNC_ID_HEADER.h MNC_OPTIONS.h MNC_PARAMS.h
MNC_CW_READWRITE_RL.f: MNC_SIZE.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
MNC_CW_READWRITE_RS.f: /nasa/netcdf/4.4.1.1_mpt/include/netcdf.inc
MNC_CW_READWRITE_RS.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
MNC_CW_READWRITE_RS.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h MNC_BUFF.h
MNC_CW_READWRITE_RS.f: MNC_COMMON.h MNC_ID_HEADER.h MNC_OPTIONS.h MNC_PARAMS.h
MNC_CW_READWRITE_RS.f: MNC_SIZE.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
adams_bashforth2.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
adams_bashforth2.f: CPP_OPTIONS.h EEPARAMS.h PARAMS.h SIZE.h
adams_bashforth3.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
adams_bashforth3.f: CPP_OPTIONS.h EEPARAMS.h PARAMS.h SIZE.h
add_walls2masks.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
add_walls2masks.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
add_walls2masks.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
add_walls2masks.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
add_walls2masks.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
add_walls2masks.f: MASKW_MACROS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
add_walls2masks.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
add_walls2masks.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
add_walls2masks.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
add_walls2masks.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
add_walls2masks.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
add_walls2masks.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
advect.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
advect.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
advect.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
advect.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
advect.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
advect.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
advect.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
advect.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
advect.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
advect.f: RECIP_HFACW_MACROS.h SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h
advect.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
all_proc_die.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
all_proc_die.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
all_proc_die.f: EEPARAMS.h EESUPPORT.h SIZE.h
apply_forcing.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
apply_forcing.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
apply_forcing.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
apply_forcing.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h FFIELDS.h GRID.h
apply_forcing.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
apply_forcing.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
apply_forcing.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
apply_forcing.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
apply_forcing.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
apply_forcing.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
apply_forcing.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
apply_forcing.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
bar2.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h /usr/include/stdc-predef.h
bar2.f: BAR2.h CPP_EEMACROS.h CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h SIZE.h
bar_check.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
bar_check.f: EEPARAMS.h SIZE.h
barrier.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h /usr/include/stdc-predef.h
barrier.f: BARRIER.h CPP_EEMACROS.h CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h
barrier.f: SIZE.h
bulkf_ave.f: /usr/include/stdc-predef.h BULKF.h BULKF_INT.h BULKF_TAVE.h
bulkf_ave.f: BULK_FORCE_OPTIONS.h CPP_EEMACROS.h CPP_EEOPTIONS.h CPP_OPTIONS.h
bulkf_ave.f: EEPARAMS.h FFIELDS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
bulkf_fields_load.f: /usr/include/stdc-predef.h BULKF.h BULKF_PARAMS.h
bulkf_fields_load.f: BULK_FORCE_OPTIONS.h CPP_EEMACROS.h CPP_EEOPTIONS.h
bulkf_fields_load.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
bulkf_fields_load.f: SIZE.h
bulkf_flux_adjust.f: /usr/include/stdc-predef.h BULKF.h BULKF_PARAMS.h
bulkf_flux_adjust.f: BULK_FORCE_OPTIONS.h CPP_EEMACROS.h CPP_EEOPTIONS.h
bulkf_flux_adjust.f: CPP_OPTIONS.h EEPARAMS.h FFIELDS.h PACKAGES_CONFIG.h
bulkf_flux_adjust.f: SIZE.h
bulkf_forcing.f: /usr/include/stdc-predef.h BULKF.h BULKF_INT.h BULKF_PARAMS.h
bulkf_forcing.f: BULKF_TAVE.h BULK_FORCE_OPTIONS.h CPP_EEMACROS.h
bulkf_forcing.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
bulkf_forcing.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
bulkf_forcing.f: DYG_MACROS.h DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
bulkf_forcing.f: FFIELDS.h GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
bulkf_forcing.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
bulkf_forcing.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
bulkf_forcing.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
bulkf_forcing.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
bulkf_forcing.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
bulkf_forcing.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
bulkf_forcing.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
bulkf_forcing.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
bulkf_formula_aim.f: /usr/include/stdc-predef.h BULKF_PARAMS.h
bulkf_formula_aim.f: BULK_FORCE_OPTIONS.h CPP_EEMACROS.h CPP_EEOPTIONS.h
bulkf_formula_aim.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
bulkf_formula_aim.f: SIZE.h
bulkf_formula_lanl.f: /usr/include/stdc-predef.h BULKF_PARAMS.h
bulkf_formula_lanl.f: BULK_FORCE_OPTIONS.h CPP_EEMACROS.h CPP_EEOPTIONS.h
bulkf_formula_lanl.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
bulkf_formula_lanl.f: SIZE.h
bulkf_formula_lay.f: /usr/include/stdc-predef.h BULKF_PARAMS.h
bulkf_formula_lay.f: BULK_FORCE_OPTIONS.h CPP_EEMACROS.h CPP_EEOPTIONS.h
bulkf_formula_lay.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
bulkf_formula_lay.f: SIZE.h
bulkf_init_varia.f: /usr/include/stdc-predef.h BULKF.h BULKF_PARAMS.h
bulkf_init_varia.f: BULKF_TAVE.h BULK_FORCE_OPTIONS.h CPP_EEMACROS.h
bulkf_init_varia.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
bulkf_init_varia.f: SIZE.h
bulkf_output.f: /usr/include/stdc-predef.h BULKF.h BULKF_PARAMS.h BULKF_TAVE.h
bulkf_output.f: BULK_FORCE_OPTIONS.h CPP_EEMACROS.h CPP_EEOPTIONS.h
bulkf_output.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
bulkf_readparms.f: /usr/include/stdc-predef.h BULKF.h BULKF_PARAMS.h
bulkf_readparms.f: BULK_FORCE_OPTIONS.h CPP_EEMACROS.h CPP_EEOPTIONS.h
bulkf_readparms.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
bulkf_sh2rh_aim.f: /usr/include/stdc-predef.h BULK_FORCE_OPTIONS.h
bulkf_sh2rh_aim.f: CPP_EEMACROS.h CPP_EEOPTIONS.h CPP_OPTIONS.h
bulkf_sh2rh_aim.f: PACKAGES_CONFIG.h
cal_addtime.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_addtime.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
cal_addtime.f: cal.h
cal_checkdate.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_checkdate.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
cal_checkdate.f: cal.h
cal_compdates.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_compdates.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
cal_convdate.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_convdate.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
cal_convdate.f: cal.h
cal_copydate.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_copydate.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
cal_daysformonth.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_daysformonth.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
cal_dayspermonth.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_dayspermonth.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
cal_fulldate.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_fulldate.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
cal_fulldate.f: cal.h
cal_getdate.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_getdate.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
cal_getdate.f: cal.h
cal_getmonthsrec.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_getmonthsrec.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
cal_init_fixed.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_init_fixed.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
cal_init_fixed.f: PARAMS.h SIZE.h
cal_intdays.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_intdays.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
cal_intmonths.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_intmonths.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
cal_intyears.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_intyears.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
cal_isleap.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_isleap.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h cal.h
cal_monthsforyear.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_monthsforyear.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
cal_monthsperyear.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_monthsperyear.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
cal_numints.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_numints.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
cal_printdate.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_printdate.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
cal_printerror.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_printerror.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
cal_printerror.f: PARAMS.h SIZE.h
cal_readparms.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_readparms.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
cal_readparms.f: PARAMS.h SIZE.h cal.h
cal_set.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_set.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
cal_stepsforday.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_stepsforday.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
cal_stepsperday.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_stepsperday.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
cal_subdates.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_subdates.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
cal_subdates.f: cal.h
cal_summary.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_summary.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
cal_summary.f: cal.h
cal_time2dump.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_time2dump.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
cal_timeinterval.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_timeinterval.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
cal_timeinterval.f: cal.h
cal_timepassed.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_timepassed.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
cal_timepassed.f: cal.h
cal_timestamp.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_timestamp.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
cal_toseconds.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_toseconds.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
cal_toseconds.f: cal.h
cal_weekday.f: /usr/include/stdc-predef.h CAL_OPTIONS.h CPP_EEMACROS.h
cal_weekday.f: CPP_EEOPTIONS.h CPP_OPTIONS.h PACKAGES_CONFIG.h cal.h
calc_3d_diffusivity.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
calc_3d_diffusivity.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
calc_3d_diffusivity.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
calc_3d_diffusivity.f: DYG_MACROS.h DYNVARS.h DYU_MACROS.h EEPARAMS.h
calc_3d_diffusivity.f: FCORI_MACROS.h GAD.h GRID.h GRID_MACROS.h
calc_3d_diffusivity.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
calc_3d_diffusivity.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
calc_3d_diffusivity.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
calc_3d_diffusivity.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
calc_3d_diffusivity.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
calc_3d_diffusivity.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
calc_3d_diffusivity.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
calc_3d_diffusivity.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
calc_3d_diffusivity.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
calc_3d_diffusivity.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
calc_adv_flow.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
calc_adv_flow.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
calc_adv_flow.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
calc_adv_flow.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
calc_adv_flow.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
calc_adv_flow.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
calc_adv_flow.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
calc_adv_flow.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
calc_adv_flow.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
calc_adv_flow.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
calc_adv_flow.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
calc_adv_flow.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
calc_div_ghat.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
calc_div_ghat.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
calc_div_ghat.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
calc_div_ghat.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
calc_div_ghat.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
calc_div_ghat.f: MASKW_MACROS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
calc_div_ghat.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
calc_div_ghat.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
calc_div_ghat.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
calc_div_ghat.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
calc_div_ghat.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
calc_eddy_stress.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
calc_eddy_stress.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
calc_eddy_stress.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
calc_eddy_stress.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h FFIELDS.h GMREDI.h
calc_eddy_stress.f: GMREDI_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
calc_eddy_stress.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
calc_eddy_stress.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
calc_eddy_stress.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
calc_eddy_stress.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
calc_eddy_stress.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
calc_eddy_stress.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
calc_eddy_stress.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
calc_eddy_stress.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
calc_eddy_stress.f: YC_MACROS.h
calc_grad_phi_fv.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
calc_grad_phi_fv.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
calc_grad_phi_fv.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
calc_grad_phi_fv.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
calc_grad_phi_fv.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
calc_grad_phi_fv.f: MASKS_MACROS.h MASKW_MACROS.h PARAMS.h RAS_MACROS.h
calc_grad_phi_fv.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
calc_grad_phi_fv.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
calc_grad_phi_fv.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
calc_grad_phi_fv.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
calc_grad_phi_fv.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
calc_grad_phi_fv.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
calc_grad_phi_fv.f: YC_MACROS.h
calc_grad_phi_hyd.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
calc_grad_phi_hyd.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
calc_grad_phi_hyd.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
calc_grad_phi_hyd.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
calc_grad_phi_hyd.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
calc_grad_phi_hyd.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PARAMS.h
calc_grad_phi_hyd.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
calc_grad_phi_hyd.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
calc_grad_phi_hyd.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
calc_grad_phi_hyd.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
calc_grad_phi_hyd.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
calc_grad_phi_hyd.f: SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
calc_grad_phi_hyd.f: XC_MACROS.h YC_MACROS.h
calc_grad_phi_surf.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
calc_grad_phi_surf.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
calc_grad_phi_surf.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
calc_grad_phi_surf.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
calc_grad_phi_surf.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
calc_grad_phi_surf.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PARAMS.h
calc_grad_phi_surf.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
calc_grad_phi_surf.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
calc_grad_phi_surf.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
calc_grad_phi_surf.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
calc_grad_phi_surf.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
calc_grad_phi_surf.f: SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
calc_grad_phi_surf.f: XC_MACROS.h YC_MACROS.h
calc_grid_angles.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
calc_grid_angles.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
calc_grid_angles.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
calc_grid_angles.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
calc_grid_angles.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
calc_grid_angles.f: MASKS_MACROS.h MASKW_MACROS.h PARAMS.h RAS_MACROS.h
calc_grid_angles.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
calc_grid_angles.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
calc_grid_angles.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
calc_grid_angles.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
calc_grid_angles.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
calc_grid_angles.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
calc_grid_angles.f: YC_MACROS.h
calc_gw.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
calc_gw.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
calc_gw.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
calc_gw.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
calc_gw.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
calc_gw.f: MOM_COMMON_OPTIONS.h MOM_VISC.h NH_VARS.h PACKAGES_CONFIG.h
calc_gw.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
calc_gw.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
calc_gw.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
calc_gw.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
calc_gw.f: RECIP_HFACW_MACROS.h RESTART.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
calc_gw.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
calc_ivdc.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
calc_ivdc.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
calc_ivdc.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
calc_ivdc.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
calc_ivdc.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
calc_ivdc.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
calc_ivdc.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
calc_ivdc.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
calc_ivdc.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
calc_ivdc.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
calc_ivdc.f: XC_MACROS.h YC_MACROS.h
calc_oce_mxlayer.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
calc_oce_mxlayer.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
calc_oce_mxlayer.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
calc_oce_mxlayer.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GMREDI.h
calc_oce_mxlayer.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
calc_oce_mxlayer.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
calc_oce_mxlayer.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
calc_oce_mxlayer.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
calc_oce_mxlayer.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
calc_oce_mxlayer.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
calc_oce_mxlayer.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
calc_oce_mxlayer.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
calc_oce_mxlayer.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
calc_phi_hyd.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
calc_phi_hyd.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
calc_phi_hyd.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
calc_phi_hyd.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
calc_phi_hyd.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
calc_phi_hyd.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
calc_phi_hyd.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
calc_phi_hyd.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
calc_phi_hyd.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
calc_phi_hyd.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
calc_phi_hyd.f: SIZE.h SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
calc_phi_hyd.f: XC_MACROS.h YC_MACROS.h
calc_r_star.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
calc_r_star.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
calc_r_star.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
calc_r_star.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
calc_r_star.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
calc_r_star.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
calc_r_star.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
calc_r_star.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
calc_r_star.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
calc_r_star.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
calc_r_star.f: SIZE.h SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
calc_r_star.f: W2_OPTIONS.h XC_MACROS.h YC_MACROS.h
calc_surf_dr.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
calc_surf_dr.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
calc_surf_dr.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
calc_surf_dr.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
calc_surf_dr.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
calc_surf_dr.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
calc_surf_dr.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
calc_surf_dr.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
calc_surf_dr.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
calc_surf_dr.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
calc_surf_dr.f: SIZE.h SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
calc_surf_dr.f: XC_MACROS.h YC_MACROS.h
calc_viscosity.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
calc_viscosity.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
calc_viscosity.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
calc_viscosity.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
calc_viscosity.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
calc_viscosity.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
calc_viscosity.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
calc_viscosity.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
calc_viscosity.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
calc_viscosity.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
calc_viscosity.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
calc_viscosity.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
calc_wsurf_tr.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
calc_wsurf_tr.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
calc_wsurf_tr.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
calc_wsurf_tr.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
calc_wsurf_tr.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
calc_wsurf_tr.f: MASKW_MACROS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
calc_wsurf_tr.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
calc_wsurf_tr.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
calc_wsurf_tr.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
calc_wsurf_tr.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
calc_wsurf_tr.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
cg2d.f: /usr/include/stdc-predef.h CG2D.h CPP_EEMACROS.h CPP_EEOPTIONS.h
cg2d.f: CPP_OPTIONS.h EEPARAMS.h PARAMS.h SIZE.h
cg2d_ex0.f: /usr/include/stdc-predef.h CG2D.h CPP_EEMACROS.h CPP_EEOPTIONS.h
cg2d_ex0.f: CPP_OPTIONS.h EEPARAMS.h PARAMS.h SIZE.h
cg2d_nsa.f: /usr/include/stdc-predef.h CG2D.h CPP_EEMACROS.h CPP_EEOPTIONS.h
cg2d_nsa.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
cg2d_sr.f: /usr/include/stdc-predef.h CG2D.h CPP_EEMACROS.h CPP_EEOPTIONS.h
cg2d_sr.f: CPP_OPTIONS.h EEPARAMS.h PARAMS.h SIZE.h
cg3d.f: /usr/include/stdc-predef.h CG3D.h CPP_EEMACROS.h CPP_EEOPTIONS.h
cg3d.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
cg3d.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
cg3d.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
cg3d.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PARAMS.h RAS_MACROS.h
cg3d.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
cg3d.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
cg3d.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
cg3d.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
cg3d.f: SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
cg3d.f: YC_MACROS.h
cg3d_ex0.f: /usr/include/stdc-predef.h CG3D.h CPP_EEMACROS.h CPP_EEOPTIONS.h
cg3d_ex0.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
cg3d_ex0.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
cg3d_ex0.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
cg3d_ex0.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PARAMS.h RAS_MACROS.h
cg3d_ex0.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
cg3d_ex0.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
cg3d_ex0.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
cg3d_ex0.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
cg3d_ex0.f: SIZE.h SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
cg3d_ex0.f: YC_MACROS.h
check_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
check_pickup.f: CPP_OPTIONS.h EEPARAMS.h PARAMS.h RESTART.h SIZE.h
check_threads.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
check_threads.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
check_threads.f: EEPARAMS.h EESUPPORT.h SIZE.h
chksum_tiled.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
chksum_tiled.f: CPP_OPTIONS.h DEBUG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
chksum_tiled.f: SIZE.h
comm_stats.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
comm_stats.f: /usr/include/stdc-predef.h BAR2.h CPP_EEMACROS.h CPP_EEOPTIONS.h
comm_stats.f: EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
config_check.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
config_check.f: CPP_OPTIONS.h EEPARAMS.h MOM_COMMON_OPTIONS.h
config_check.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
config_summary.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
config_summary.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
config_summary.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
config_summary.f: DYU_MACROS.h EEPARAMS.h EOS.h FCORI_MACROS.h GRID.h
config_summary.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
config_summary.f: MASKS_MACROS.h MASKW_MACROS.h MNC_PARAMS.h
config_summary.f: MOM_COMMON_OPTIONS.h MOM_VISC.h PACKAGES_CONFIG.h PARAMS.h
config_summary.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
config_summary.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
config_summary.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
config_summary.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
config_summary.f: RECIP_HFACW_MACROS.h SET_GRID.h SIZE.h TANPHIATU_MACROS.h
config_summary.f: TANPHIATV_MACROS.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
config_summary.f: W2_OPTIONS.h XC_MACROS.h YC_MACROS.h
convective_adjustment.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
convective_adjustment.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
convective_adjustment.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
convective_adjustment.f: DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
convective_adjustment.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
convective_adjustment.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
convective_adjustment.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
convective_adjustment.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
convective_adjustment.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
convective_adjustment.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
convective_adjustment.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
convective_adjustment.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
convective_adjustment.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
convective_adjustment.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
convective_adjustment.f: TANPHIATV_MACROS.h TIMEAVE_OPTIONS.h TIMEAVE_STATV.h
convective_adjustment.f: XC_MACROS.h YC_MACROS.h
convective_adjustment_ini.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
convective_adjustment_ini.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
convective_adjustment_ini.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
convective_adjustment_ini.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
convective_adjustment_ini.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
convective_adjustment_ini.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
convective_adjustment_ini.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
convective_adjustment_ini.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
convective_adjustment_ini.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
convective_adjustment_ini.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
convective_adjustment_ini.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
convective_adjustment_ini.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
convective_adjustment_ini.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
convective_adjustment_ini.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
convective_adjustment_ini.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h
convective_adjustment_ini.f: TIMEAVE_OPTIONS.h TIMEAVE_STATV.h XC_MACROS.h
convective_adjustment_ini.f: YC_MACROS.h
convective_weights.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
convective_weights.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
convective_weights.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
convective_weights.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
convective_weights.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
convective_weights.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PARAMS.h
convective_weights.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
convective_weights.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
convective_weights.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
convective_weights.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
convective_weights.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
convective_weights.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
convective_weights.f: YC_MACROS.h
convectively_mixtracer.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
convectively_mixtracer.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h SIZE.h
correction_step.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
correction_step.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
correction_step.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
correction_step.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h FFIELDS.h
correction_step.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
correction_step.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h NH_VARS.h
correction_step.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
correction_step.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
correction_step.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
correction_step.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
correction_step.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
correction_step.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
correction_step.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
cost_ice_test.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
cost_ice_test.f: CPP_OPTIONS.h PACKAGES_CONFIG.h SEAICE_OPTIONS.h
cumulsum_z_tile.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
cumulsum_z_tile.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
cumulsum_z_tile.f: CUMULSUM.h EEPARAMS.h EESUPPORT.h PACKAGES_CONFIG.h SIZE.h
cycle_ab_tracer.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
cycle_ab_tracer.f: CPP_OPTIONS.h EEPARAMS.h PARAMS.h SIZE.h
cycle_tracer.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
cycle_tracer.f: CPP_OPTIONS.h EEPARAMS.h PARAMS.h SIZE.h
debug_call.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
debug_call.f: CPP_OPTIONS.h DEBUG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
debug_call.f: SIZE.h
debug_cs_corner_uv.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
debug_cs_corner_uv.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DEBUG_OPTIONS.h EEPARAMS.h
debug_cs_corner_uv.f: PACKAGES_CONFIG.h SIZE.h W2_EXCH2_SIZE.h
debug_cs_corner_uv.f: W2_EXCH2_TOPOLOGY.h
debug_enter.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
debug_enter.f: CPP_OPTIONS.h DEBUG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
debug_enter.f: SIZE.h
debug_fld_stats_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
debug_fld_stats_rl.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DEBUG_OPTIONS.h EEPARAMS.h
debug_fld_stats_rl.f: PACKAGES_CONFIG.h SIZE.h
debug_fld_stats_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
debug_fld_stats_rs.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DEBUG_OPTIONS.h EEPARAMS.h
debug_fld_stats_rs.f: PACKAGES_CONFIG.h SIZE.h
debug_leave.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
debug_leave.f: CPP_OPTIONS.h DEBUG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
debug_leave.f: SIZE.h
debug_msg.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
debug_msg.f: CPP_OPTIONS.h DEBUG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
debug_stats_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
debug_stats_rl.f: CPP_OPTIONS.h DEBUG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
debug_stats_rl.f: SIZE.h
debug_stats_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
debug_stats_rs.f: CPP_OPTIONS.h DEBUG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
debug_stats_rs.f: SIZE.h
diag_calc_psivel.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diag_calc_psivel.f: CPP_OPTIONS.h DIAG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
diag_calc_psivel.f: PARAMS.h SIZE.h
diag_cg2d.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diag_cg2d.f: CPP_OPTIONS.h DIAG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
diag_cg2d.f: PARAMS.h SIZE.h
diag_vegtile_fill.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diag_vegtile_fill.f: CPP_OPTIONS.h DIAGNOSTICS.h DIAGNOSTICS_SIZE.h
diag_vegtile_fill.f: DIAG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
diagnostics_addtolist.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_addtolist.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_addtolist.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_addtolist.f: PACKAGES_CONFIG.h SIZE.h
diagnostics_calc_phivel.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_calc_phivel.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_calc_phivel.f: DIAGNOSTICS_CALC.h DIAGNOSTICS_SIZE.h
diagnostics_calc_phivel.f: DIAG_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
diagnostics_calc_phivel.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
diagnostics_calc_phivel.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
diagnostics_calc_phivel.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
diagnostics_calc_phivel.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
diagnostics_calc_phivel.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
diagnostics_calc_phivel.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
diagnostics_calc_phivel.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
diagnostics_calc_phivel.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
diagnostics_calc_phivel.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
diagnostics_calc_phivel.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
diagnostics_calc_phivel.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
diagnostics_calc_phivel.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
diagnostics_calc_phivel.f: YC_MACROS.h
diagnostics_check.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagnostics_check.f: CPP_OPTIONS.h DIAGNOSTICS.h DIAGNOSTICS_SIZE.h
diagnostics_check.f: DIAG_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
diagnostics_check.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
diagnostics_check.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
diagnostics_check.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
diagnostics_check.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
diagnostics_check.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
diagnostics_check.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
diagnostics_check.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
diagnostics_check.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
diagnostics_check.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
diagnostics_check.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
diagnostics_check.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
diagnostics_clear.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagnostics_clear.f: CPP_OPTIONS.h DIAGNOSTICS.h DIAGNOSTICS_SIZE.h
diagnostics_clear.f: DIAG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
diagnostics_fill.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagnostics_fill.f: CPP_OPTIONS.h DIAGNOSTICS.h DIAGNOSTICS_SIZE.h
diagnostics_fill.f: DIAG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
diagnostics_fill_field.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_fill_field.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_fill_field.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h DXC_MACROS.h
diagnostics_fill_field.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
diagnostics_fill_field.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
diagnostics_fill_field.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
diagnostics_fill_field.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
diagnostics_fill_field.f: MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
diagnostics_fill_field.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
diagnostics_fill_field.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
diagnostics_fill_field.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
diagnostics_fill_field.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
diagnostics_fill_field.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
diagnostics_fill_field.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
diagnostics_fill_field.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
diagnostics_fill_field.f: YC_MACROS.h
diagnostics_fill_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_fill_rs.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_fill_rs.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_fill_rs.f: PACKAGES_CONFIG.h SIZE.h
diagnostics_fill_state.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_fill_state.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAG_OPTIONS.h
diagnostics_fill_state.f: DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
diagnostics_fill_state.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
diagnostics_fill_state.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h GRID.h
diagnostics_fill_state.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
diagnostics_fill_state.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
diagnostics_fill_state.f: NH_VARS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
diagnostics_fill_state.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
diagnostics_fill_state.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
diagnostics_fill_state.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
diagnostics_fill_state.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
diagnostics_fill_state.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
diagnostics_fill_state.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
diagnostics_fill_state.f: SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
diagnostics_fill_state.f: XC_MACROS.h YC_MACROS.h
diagnostics_fract_fill.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_fract_fill.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_fract_fill.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_fract_fill.f: PACKAGES_CONFIG.h SIZE.h
diagnostics_ini_io.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_ini_io.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_ini_io.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_ini_io.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
diagnostics_init_early.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_init_early.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_init_early.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_init_early.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
diagnostics_init_fixed.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_init_fixed.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_init_fixed.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_init_fixed.f: PACKAGES_CONFIG.h SIZE.h
diagnostics_init_varia.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_init_varia.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_init_varia.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_init_varia.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
diagnostics_interp_p2p.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_interp_p2p.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAG_OPTIONS.h
diagnostics_interp_p2p.f: PACKAGES_CONFIG.h
diagnostics_interp_vert.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_interp_vert.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_interp_vert.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h DXC_MACROS.h
diagnostics_interp_vert.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
diagnostics_interp_vert.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
diagnostics_interp_vert.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
diagnostics_interp_vert.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
diagnostics_interp_vert.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
diagnostics_interp_vert.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
diagnostics_interp_vert.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
diagnostics_interp_vert.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
diagnostics_interp_vert.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
diagnostics_interp_vert.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
diagnostics_interp_vert.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
diagnostics_interp_vert.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
diagnostics_interp_vert.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
diagnostics_is_on.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagnostics_is_on.f: CPP_OPTIONS.h DIAGNOSTICS.h DIAGNOSTICS_SIZE.h
diagnostics_is_on.f: DIAG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
diagnostics_list_check.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_list_check.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_list_check.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_list_check.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
diagnostics_main_init.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_main_init.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAG_OPTIONS.h
diagnostics_main_init.f: EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
diagnostics_mnc_out.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_mnc_out.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_mnc_out.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h DXC_MACROS.h
diagnostics_mnc_out.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
diagnostics_mnc_out.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
diagnostics_mnc_out.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
diagnostics_mnc_out.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
diagnostics_mnc_out.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
diagnostics_mnc_out.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
diagnostics_mnc_out.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
diagnostics_mnc_out.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
diagnostics_mnc_out.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
diagnostics_mnc_out.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
diagnostics_mnc_out.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
diagnostics_mnc_out.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
diagnostics_mnc_out.f: YC_MACROS.h
diagnostics_out.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagnostics_out.f: CPP_OPTIONS.h DIAGNOSTICS.h DIAGNOSTICS_SIZE.h
diagnostics_out.f: DIAG_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
diagnostics_out.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
diagnostics_out.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
diagnostics_out.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
diagnostics_out.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
diagnostics_out.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
diagnostics_out.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
diagnostics_out.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
diagnostics_out.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
diagnostics_out.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
diagnostics_out.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
diagnostics_out.f: YC_MACROS.h
diagnostics_read_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_read_pickup.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_read_pickup.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_read_pickup.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
diagnostics_readparms.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_readparms.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_readparms.f: DIAGNOSTICS_CALC.h DIAGNOSTICS_SIZE.h
diagnostics_readparms.f: DIAGSTATS_REGIONS.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_readparms.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
diagnostics_scale_fill.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_scale_fill.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_scale_fill.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_scale_fill.f: PACKAGES_CONFIG.h SIZE.h
diagnostics_scale_fill_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_scale_fill_rs.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_scale_fill_rs.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_scale_fill_rs.f: PACKAGES_CONFIG.h SIZE.h
diagnostics_set_calc.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_set_calc.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS_CALC.h
diagnostics_set_calc.f: DIAG_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
diagnostics_set_calc.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
diagnostics_set_calc.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
diagnostics_set_calc.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
diagnostics_set_calc.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
diagnostics_set_calc.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
diagnostics_set_calc.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
diagnostics_set_calc.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
diagnostics_set_calc.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
diagnostics_set_calc.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
diagnostics_set_calc.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
diagnostics_set_calc.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
diagnostics_set_calc.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
diagnostics_set_levels.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_set_levels.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_set_levels.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_set_levels.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
diagnostics_set_pointers.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_set_pointers.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_set_pointers.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_set_pointers.f: PACKAGES_CONFIG.h SIZE.h
diagnostics_setdiag.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_setdiag.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_setdiag.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_setdiag.f: PACKAGES_CONFIG.h SIZE.h
diagnostics_status_error.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_status_error.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_status_error.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_status_error.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
diagnostics_sum_levels.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_sum_levels.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_sum_levels.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h DXC_MACROS.h
diagnostics_sum_levels.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
diagnostics_sum_levels.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
diagnostics_sum_levels.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
diagnostics_sum_levels.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
diagnostics_sum_levels.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
diagnostics_sum_levels.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
diagnostics_sum_levels.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
diagnostics_sum_levels.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
diagnostics_sum_levels.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
diagnostics_sum_levels.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
diagnostics_sum_levels.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
diagnostics_sum_levels.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
diagnostics_sum_levels.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
diagnostics_summary.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_summary.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_summary.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_summary.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
diagnostics_switch_onoff.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_switch_onoff.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_switch_onoff.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_switch_onoff.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
diagnostics_utils.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagnostics_utils.f: CPP_OPTIONS.h DIAGNOSTICS.h DIAGNOSTICS_SIZE.h
diagnostics_utils.f: DIAG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
diagnostics_utils.f: SIZE.h
diagnostics_write.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagnostics_write.f: CPP_OPTIONS.h DIAGNOSTICS.h DIAGNOSTICS_SIZE.h
diagnostics_write.f: DIAG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
diagnostics_write.f: SIZE.h
diagnostics_write_adj.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_write_adj.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_write_adj.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_write_adj.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
diagnostics_write_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagnostics_write_pickup.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagnostics_write_pickup.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagnostics_write_pickup.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
diags_oceanic_surf_flux.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diags_oceanic_surf_flux.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
diags_oceanic_surf_flux.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
diags_oceanic_surf_flux.f: DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
diags_oceanic_surf_flux.f: EEPARAMS.h FCORI_MACROS.h FFIELDS.h GRID.h
diags_oceanic_surf_flux.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
diags_oceanic_surf_flux.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
diags_oceanic_surf_flux.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
diags_oceanic_surf_flux.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
diags_oceanic_surf_flux.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
diags_oceanic_surf_flux.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
diags_oceanic_surf_flux.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
diags_oceanic_surf_flux.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
diags_oceanic_surf_flux.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
diags_oceanic_surf_flux.f: SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
diags_oceanic_surf_flux.f: XC_MACROS.h YC_MACROS.h
diags_phi_hyd.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diags_phi_hyd.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
diags_phi_hyd.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
diags_phi_hyd.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
diags_phi_hyd.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
diags_phi_hyd.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
diags_phi_hyd.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
diags_phi_hyd.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
diags_phi_hyd.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
diags_phi_hyd.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
diags_phi_hyd.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
diags_phi_hyd.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
diags_phi_rlow.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diags_phi_rlow.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
diags_phi_rlow.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
diags_phi_rlow.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
diags_phi_rlow.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
diags_phi_rlow.f: MASKS_MACROS.h MASKW_MACROS.h PARAMS.h RAS_MACROS.h
diags_phi_rlow.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
diags_phi_rlow.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
diags_phi_rlow.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
diags_phi_rlow.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
diags_phi_rlow.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
diags_phi_rlow.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
diags_rho.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diags_rho.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
diags_rho.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
diags_rho.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
diags_rho.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
diags_rho.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
diags_rho.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
diags_rho.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
diags_rho.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
diags_rho.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
diags_rho.f: XC_MACROS.h YC_MACROS.h
diagstats_ascii_out.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagstats_ascii_out.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagstats_ascii_out.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagstats_ascii_out.f: PACKAGES_CONFIG.h SIZE.h
diagstats_calc.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagstats_calc.f: CPP_OPTIONS.h DIAG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
diagstats_calc.f: SIZE.h
diagstats_clear.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagstats_clear.f: CPP_OPTIONS.h DIAGNOSTICS.h DIAGNOSTICS_SIZE.h
diagstats_clear.f: DIAG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
diagstats_close_io.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagstats_close_io.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagstats_close_io.f: DIAGNOSTICS_SIZE.h DIAG_OPTIONS.h EEPARAMS.h
diagstats_close_io.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
diagstats_fill.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagstats_fill.f: CPP_OPTIONS.h DIAGNOSTICS.h DIAGNOSTICS_SIZE.h
diagstats_fill.f: DIAG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
diagstats_global.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagstats_global.f: CPP_OPTIONS.h DIAGNOSTICS.h DIAGNOSTICS_SIZE.h
diagstats_global.f: DIAG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
diagstats_ini_io.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagstats_ini_io.f: CPP_OPTIONS.h DIAGNOSTICS.h DIAGNOSTICS_SIZE.h
diagstats_ini_io.f: DIAG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
diagstats_ini_io.f: SIZE.h
diagstats_local.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagstats_local.f: CPP_OPTIONS.h DIAGNOSTICS_SIZE.h DIAGSTATS_REGIONS.h
diagstats_local.f: DIAG_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
diagstats_local.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
diagstats_local.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
diagstats_local.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
diagstats_local.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
diagstats_local.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
diagstats_local.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
diagstats_local.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
diagstats_local.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
diagstats_local.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
diagstats_local.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
diagstats_local.f: YC_MACROS.h
diagstats_mnc_out.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
diagstats_mnc_out.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagstats_mnc_out.f: CPP_OPTIONS.h DIAGNOSTICS.h DIAGNOSTICS_SIZE.h
diagstats_mnc_out.f: DIAG_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
diagstats_mnc_out.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
diagstats_mnc_out.f: DYU_MACROS.h EEPARAMS.h EESUPPORT.h FCORI_MACROS.h GRID.h
diagstats_mnc_out.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
diagstats_mnc_out.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
diagstats_mnc_out.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
diagstats_mnc_out.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
diagstats_mnc_out.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
diagstats_mnc_out.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
diagstats_mnc_out.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
diagstats_mnc_out.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
diagstats_mnc_out.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
diagstats_others_calc.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagstats_others_calc.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAG_OPTIONS.h
diagstats_others_calc.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
diagstats_output.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagstats_output.f: CPP_OPTIONS.h DIAGNOSTICS.h DIAGNOSTICS_SIZE.h
diagstats_output.f: DIAG_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
diagstats_output.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
diagstats_output.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
diagstats_output.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
diagstats_output.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
diagstats_output.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
diagstats_output.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
diagstats_output.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
diagstats_output.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
diagstats_output.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
diagstats_output.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
diagstats_output.f: YC_MACROS.h
diagstats_set_pointers.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagstats_set_pointers.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS.h
diagstats_set_pointers.f: DIAGNOSTICS_SIZE.h DIAGSTATS_REGIONS.h
diagstats_set_pointers.f: DIAG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
diagstats_set_regions.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diagstats_set_regions.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DIAGNOSTICS_SIZE.h
diagstats_set_regions.f: DIAGSTATS_REGIONS.h DIAG_OPTIONS.h EEPARAMS.h
diagstats_set_regions.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
diagstats_setdiag.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diagstats_setdiag.f: CPP_OPTIONS.h DIAGNOSTICS.h DIAGNOSTICS_SIZE.h
diagstats_setdiag.f: DIAG_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
diff_phase_multiple.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
diff_phase_multiple.f: CPP_EEOPTIONS.h
different_multiple.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
different_multiple.f: CPP_EEOPTIONS.h
diffus.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
diffus.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
diffus.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
diffus.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
diffus.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
diffus.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
diffus.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
diffus.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
diffus.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
diffus.f: RECIP_HFACW_MACROS.h SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h
diffus.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
do_atmospheric_phys.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
do_atmospheric_phys.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
do_atmospheric_phys.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
do_atmospheric_phys.f: DYG_MACROS.h DYNVARS.h DYU_MACROS.h EEPARAMS.h
do_atmospheric_phys.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
do_atmospheric_phys.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
do_atmospheric_phys.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
do_atmospheric_phys.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
do_atmospheric_phys.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
do_atmospheric_phys.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
do_atmospheric_phys.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
do_atmospheric_phys.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
do_atmospheric_phys.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
do_atmospheric_phys.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
do_atmospheric_phys.f: YC_MACROS.h
do_fields_blocking_exchanges.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
do_fields_blocking_exchanges.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DYNVARS.h
do_fields_blocking_exchanges.f: EEPARAMS.h GAD.h PACKAGES_CONFIG.h PARAMS.h
do_fields_blocking_exchanges.f: SIZE.h
do_oceanic_phys.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
do_oceanic_phys.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
do_oceanic_phys.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
do_oceanic_phys.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
do_oceanic_phys.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
do_oceanic_phys.f: MASKS_MACROS.h MASKW_MACROS.h MOM_COMMON_OPTIONS.h
do_oceanic_phys.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
do_oceanic_phys.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
do_oceanic_phys.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
do_oceanic_phys.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
do_oceanic_phys.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
do_oceanic_phys.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
do_oceanic_phys.f: TANPHIATV_MACROS.h TIMEAVE_OPTIONS.h TIMEAVE_STATV.h
do_oceanic_phys.f: XC_MACROS.h YC_MACROS.h
do_stagger_fields_exchanges.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
do_stagger_fields_exchanges.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DYNVARS.h
do_stagger_fields_exchanges.f: EEPARAMS.h PARAMS.h SIZE.h
do_statevars_diags.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
do_statevars_diags.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
do_statevars_diags.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
do_statevars_tave.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
do_statevars_tave.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
do_statevars_tave.f: SIZE.h
do_the_model_io.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
do_the_model_io.f: CPP_OPTIONS.h DYNVARS.h EEPARAMS.h PACKAGES_CONFIG.h
do_the_model_io.f: PARAMS.h SIZE.h
do_write_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
do_write_pickup.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
do_write_pickup.f: RESTART.h SIZE.h
dynamics.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
dynamics.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
dynamics.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
dynamics.f: EEPARAMS.h FCORI_MACROS.h FFIELDS.h GRID.h GRID_MACROS.h
dynamics.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
dynamics.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h MOM_VISC.h PACKAGES_CONFIG.h
dynamics.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
dynamics.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
dynamics.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
dynamics.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
dynamics.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
dynamics.f: XC_MACROS.h YC_MACROS.h
dynsolver.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
dynsolver.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
dynsolver.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
dynsolver.f: EEPARAMS.h EXF_FIELDS.h EXF_OPTIONS.h FCORI_MACROS.h FFIELDS.h
dynsolver.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
dynsolver.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
dynsolver.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
dynsolver.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
dynsolver.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
dynsolver.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
dynsolver.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h SEAICE_PARAMS.h
dynsolver.f: SEAICE_SIZE.h SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
dynsolver.f: XC_MACROS.h YC_MACROS.h
eeboot.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h /usr/include/stdc-predef.h
eeboot.f: CPP_EEMACROS.h CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h
eeboot.f: PACKAGES_CONFIG.h SIZE.h
eeboot_minimal.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
eeboot_minimal.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
eeboot_minimal.f: EEPARAMS.h EESUPPORT.h PACKAGES_CONFIG.h SIZE.h
eedata_example.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
eedata_example.f: EEPARAMS.h SIZE.h
eedie.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h /usr/include/stdc-predef.h
eedie.f: CPP_EEMACROS.h CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h SIZE.h
eeintro_msg.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
eeintro_msg.f: /usr/include/stdc-predef.h BUILD_INFO.h CPP_EEMACROS.h
eeintro_msg.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h SIZE.h
eeset_parms.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
eeset_parms.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
eeset_parms.f: EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
eewrite_eeenv.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
eewrite_eeenv.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
eewrite_eeenv.f: EEPARAMS.h EESUPPORT.h SIZE.h
exch0_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch0_r4.f: EEPARAMS.h SIZE.h
exch0_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch0_r8.f: EEPARAMS.h SIZE.h
exch0_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch0_rl.f: EEPARAMS.h SIZE.h
exch0_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch0_rs.f: EEPARAMS.h SIZE.h
exch1_bg_r4_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_bg_r4_cube.f: EEPARAMS.h SIZE.h
exch1_bg_r8_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_bg_r8_cube.f: EEPARAMS.h SIZE.h
exch1_bg_rl_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_bg_rl_cube.f: EEPARAMS.h SIZE.h
exch1_bg_rs_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_bg_rs_cube.f: EEPARAMS.h SIZE.h
exch1_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_r4.f: EEPARAMS.h EXCH.h SIZE.h
exch1_r4_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_r4_cube.f: EEPARAMS.h SIZE.h
exch1_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_r8.f: EEPARAMS.h EXCH.h SIZE.h
exch1_r8_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_r8_cube.f: EEPARAMS.h SIZE.h
exch1_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_rl.f: EEPARAMS.h EXCH.h SIZE.h
exch1_rl_ad.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_rl_ad.f: EEPARAMS.h EXCH.h SIZE.h
exch1_rl_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_rl_cube.f: EEPARAMS.h SIZE.h
exch1_rl_cube_ad.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_rl_cube_ad.f: EEPARAMS.h SIZE.h
exch1_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_rs.f: EEPARAMS.h EXCH.h SIZE.h
exch1_rs_ad.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_rs_ad.f: EEPARAMS.h EXCH.h SIZE.h
exch1_rs_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_rs_cube.f: EEPARAMS.h SIZE.h
exch1_rs_cube_ad.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_rs_cube_ad.f: EEPARAMS.h SIZE.h
exch1_uv_r4_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_uv_r4_cube.f: EEPARAMS.h SIZE.h
exch1_uv_r8_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_uv_r8_cube.f: EEPARAMS.h SIZE.h
exch1_uv_rl_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_uv_rl_cube.f: EEPARAMS.h SIZE.h
exch1_uv_rs_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_uv_rs_cube.f: EEPARAMS.h SIZE.h
exch1_z_r4_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_z_r4_cube.f: EEPARAMS.h SIZE.h
exch1_z_r8_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_z_r8_cube.f: EEPARAMS.h SIZE.h
exch1_z_rl_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_z_rl_cube.f: EEPARAMS.h SIZE.h
exch1_z_rs_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch1_z_rs_cube.f: EEPARAMS.h SIZE.h
exch2_3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_3d_r4.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_3d_r4.f: W2_OPTIONS.h
exch2_3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_3d_r8.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_3d_r8.f: W2_OPTIONS.h
exch2_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_3d_rl.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_3d_rl.f: W2_OPTIONS.h
exch2_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_3d_rs.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_3d_rs.f: W2_OPTIONS.h
exch2_ad_get_r41.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_get_r41.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_get_r41.f: W2_OPTIONS.h
exch2_ad_get_r42.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_get_r42.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_get_r42.f: W2_OPTIONS.h
exch2_ad_get_r81.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_get_r81.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_get_r81.f: W2_OPTIONS.h
exch2_ad_get_r82.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_get_r82.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_get_r82.f: W2_OPTIONS.h
exch2_ad_get_rl1.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_get_rl1.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_get_rl1.f: W2_OPTIONS.h
exch2_ad_get_rl2.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_get_rl2.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_get_rl2.f: W2_OPTIONS.h
exch2_ad_get_rs1.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_get_rs1.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_get_rs1.f: W2_OPTIONS.h
exch2_ad_get_rs2.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_get_rs2.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_get_rs2.f: W2_OPTIONS.h
exch2_ad_put_r41.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_put_r41.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_put_r41.f: W2_OPTIONS.h
exch2_ad_put_r42.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_put_r42.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_put_r42.f: W2_OPTIONS.h
exch2_ad_put_r81.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_put_r81.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_put_r81.f: W2_OPTIONS.h
exch2_ad_put_r82.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_put_r82.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_put_r82.f: W2_OPTIONS.h
exch2_ad_put_rl1.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_put_rl1.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_put_rl1.f: W2_OPTIONS.h
exch2_ad_put_rl2.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_put_rl2.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_put_rl2.f: W2_OPTIONS.h
exch2_ad_put_rs1.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_put_rs1.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_put_rs1.f: W2_OPTIONS.h
exch2_ad_put_rs2.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_ad_put_rs2.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_ad_put_rs2.f: W2_OPTIONS.h
exch2_check_depths.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_check_depths.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
exch2_check_depths.f: PACKAGES_CONFIG.h SIZE.h W2_EXCH2_SIZE.h
exch2_check_depths.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_get_r41.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_get_r41.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_get_r41.f: W2_OPTIONS.h
exch2_get_r42.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_get_r42.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_get_r42.f: W2_OPTIONS.h
exch2_get_r81.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_get_r81.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_get_r81.f: W2_OPTIONS.h
exch2_get_r82.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_get_r82.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_get_r82.f: W2_OPTIONS.h
exch2_get_rl1.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_get_rl1.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_get_rl1.f: W2_OPTIONS.h
exch2_get_rl2.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_get_rl2.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_get_rl2.f: W2_OPTIONS.h
exch2_get_rs1.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_get_rs1.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_get_rs1.f: W2_OPTIONS.h
exch2_get_rs2.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_get_rs2.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_get_rs2.f: W2_OPTIONS.h
exch2_get_scal_bounds.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_get_scal_bounds.f: CPP_EEOPTIONS.h SIZE.h W2_EXCH2_SIZE.h
exch2_get_scal_bounds.f: W2_EXCH2_TOPOLOGY.h
exch2_get_uv_bounds.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_get_uv_bounds.f: CPP_EEOPTIONS.h SIZE.h W2_EXCH2_SIZE.h
exch2_get_uv_bounds.f: W2_EXCH2_TOPOLOGY.h
exch2_put_r41.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_put_r41.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_put_r41.f: W2_OPTIONS.h
exch2_put_r42.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_put_r42.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_put_r42.f: W2_OPTIONS.h
exch2_put_r81.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_put_r81.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_put_r81.f: W2_OPTIONS.h
exch2_put_r82.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_put_r82.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_put_r82.f: W2_OPTIONS.h
exch2_put_rl1.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_put_rl1.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_put_rl1.f: W2_OPTIONS.h
exch2_put_rl2.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_put_rl2.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_put_rl2.f: W2_OPTIONS.h
exch2_put_rs1.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_put_rs1.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_put_rs1.f: W2_OPTIONS.h
exch2_put_rs2.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_put_rs2.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_put_rs2.f: W2_OPTIONS.h
exch2_r41_cube.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_r41_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_r41_cube.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_r41_cube.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_r41_cube_ad.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_r41_cube_ad.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_r41_cube_ad.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_r41_cube_ad.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_r42_cube.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_r42_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_r42_cube.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_r42_cube.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_r42_cube_ad.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_r42_cube_ad.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_r42_cube_ad.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_r42_cube_ad.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_r81_cube.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_r81_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_r81_cube.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_r81_cube.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_r81_cube_ad.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_r81_cube_ad.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_r81_cube_ad.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_r81_cube_ad.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_r82_cube.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_r82_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_r82_cube.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_r82_cube.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_r82_cube_ad.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_r82_cube_ad.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_r82_cube_ad.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_r82_cube_ad.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_recv_r41.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_recv_r41.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_recv_r41.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_recv_r41.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_recv_r42.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_recv_r42.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_recv_r42.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_recv_r42.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_recv_r81.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_recv_r81.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_recv_r81.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_recv_r81.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_recv_r82.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_recv_r82.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_recv_r82.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_recv_r82.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_recv_rl1.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_recv_rl1.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_recv_rl1.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_recv_rl1.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_recv_rl2.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_recv_rl2.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_recv_rl2.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_recv_rl2.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_recv_rs1.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_recv_rs1.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_recv_rs1.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_recv_rs1.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_recv_rs2.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_recv_rs2.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_recv_rs2.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_recv_rs2.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_rl1_cube.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_rl1_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_rl1_cube.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_rl1_cube.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_rl1_cube_ad.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_rl1_cube_ad.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_rl1_cube_ad.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_rl1_cube_ad.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_rl2_cube.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_rl2_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_rl2_cube.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_rl2_cube.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_rl2_cube_ad.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_rl2_cube_ad.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_rl2_cube_ad.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_rl2_cube_ad.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_rs1_cube.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_rs1_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_rs1_cube.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_rs1_cube.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_rs1_cube_ad.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_rs1_cube_ad.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_rs1_cube_ad.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_rs1_cube_ad.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_rs2_cube.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_rs2_cube.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_rs2_cube.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_rs2_cube.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_rs2_cube_ad.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_rs2_cube_ad.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_rs2_cube_ad.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_BUFFER.h
exch2_rs2_cube_ad.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_s3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_s3d_r4.f: EEPARAMS.h SIZE.h W2_OPTIONS.h
exch2_s3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_s3d_r8.f: EEPARAMS.h SIZE.h W2_OPTIONS.h
exch2_s3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_s3d_rl.f: EEPARAMS.h SIZE.h W2_OPTIONS.h
exch2_s3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_s3d_rs.f: EEPARAMS.h SIZE.h W2_OPTIONS.h
exch2_send_r41.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_send_r41.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_send_r41.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_send_r41.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_send_r42.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_send_r42.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_send_r42.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_send_r42.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_send_r81.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_send_r81.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_send_r81.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_send_r81.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_send_r82.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_send_r82.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_send_r82.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_send_r82.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_send_rl1.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_send_rl1.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_send_rl1.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_send_rl1.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_send_rl2.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_send_rl2.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_send_rl2.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_send_rl2.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_send_rs1.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_send_rs1.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_send_rs1.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_send_rs1.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_send_rs2.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch2_send_rs2.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_send_rs2.f: EEPARAMS.h EESUPPORT.h SIZE.h W2_EXCH2_SIZE.h
exch2_send_rs2.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_sm_3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_sm_3d_r4.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_sm_3d_r4.f: W2_OPTIONS.h
exch2_sm_3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_sm_3d_r8.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_sm_3d_r8.f: W2_OPTIONS.h
exch2_sm_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_sm_3d_rl.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_sm_3d_rl.f: W2_OPTIONS.h
exch2_sm_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_sm_3d_rs.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_sm_3d_rs.f: W2_OPTIONS.h
exch2_uv_3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_uv_3d_r4.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_uv_3d_r4.f: W2_OPTIONS.h
exch2_uv_3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_uv_3d_r8.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_uv_3d_r8.f: W2_OPTIONS.h
exch2_uv_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_uv_3d_rl.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_uv_3d_rl.f: W2_OPTIONS.h
exch2_uv_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_uv_3d_rs.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_uv_3d_rs.f: W2_OPTIONS.h
exch2_uv_agrid_3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_agrid_3d_r4.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_agrid_3d_r4.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_uv_agrid_3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_agrid_3d_r8.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_agrid_3d_r8.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_uv_agrid_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_agrid_3d_rl.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_agrid_3d_rl.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_uv_agrid_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_agrid_3d_rs.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_agrid_3d_rs.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_uv_bgrid_3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_bgrid_3d_r4.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_bgrid_3d_r4.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_uv_bgrid_3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_bgrid_3d_r8.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_bgrid_3d_r8.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_uv_bgrid_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_bgrid_3d_rl.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_bgrid_3d_rl.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_uv_bgrid_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_bgrid_3d_rs.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_bgrid_3d_rs.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_uv_cgrid_3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_cgrid_3d_r4.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_cgrid_3d_r4.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_uv_cgrid_3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_cgrid_3d_r8.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_cgrid_3d_r8.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_uv_cgrid_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_cgrid_3d_rl.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_cgrid_3d_rl.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_uv_cgrid_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_cgrid_3d_rs.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_cgrid_3d_rs.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_uv_dgrid_3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_dgrid_3d_r4.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_dgrid_3d_r4.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_uv_dgrid_3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_dgrid_3d_r8.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_dgrid_3d_r8.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_uv_dgrid_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_dgrid_3d_rl.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_dgrid_3d_rl.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_uv_dgrid_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch2_uv_dgrid_3d_rs.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h
exch2_uv_dgrid_3d_rs.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
exch2_z_3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_z_3d_r4.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_z_3d_r4.f: W2_OPTIONS.h
exch2_z_3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_z_3d_r8.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_z_3d_r8.f: W2_OPTIONS.h
exch2_z_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_z_3d_rl.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_z_3d_rl.f: W2_OPTIONS.h
exch2_z_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch2_z_3d_rs.f: EEPARAMS.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
exch2_z_3d_rs.f: W2_OPTIONS.h
exch_3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_3d_r4.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_3d_r8.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_3d_rl.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_3d_rs.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_cycle_ebl.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_cycle_ebl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_cycle_ebl.f: EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_init.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_init.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_init.f: EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_r4_recv_get_x.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_r4_recv_get_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_r4_recv_get_x.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_r4_recv_get_y.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_r4_recv_get_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_r4_recv_get_y.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_r4_send_put_x.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_r4_send_put_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_r4_send_put_x.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_r4_send_put_y.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_r4_send_put_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_r4_send_put_y.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_r8_recv_get_x.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_r8_recv_get_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_r8_recv_get_x.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_r8_recv_get_y.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_r8_recv_get_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_r8_recv_get_y.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_r8_send_put_x.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_r8_send_put_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_r8_send_put_x.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_r8_send_put_y.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_r8_send_put_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_r8_send_put_y.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_rl_recv_get_x.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_rl_recv_get_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_rl_recv_get_x.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_rl_recv_get_y.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_rl_recv_get_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_rl_recv_get_y.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_rl_send_put_x.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_rl_send_put_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_rl_send_put_x.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_rl_send_put_y.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_rl_send_put_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_rl_send_put_y.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_rs_recv_get_x.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_rs_recv_get_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_rs_recv_get_x.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_rs_recv_get_y.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_rs_recv_get_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_rs_recv_get_y.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_rs_send_put_x.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_rs_send_put_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_rs_send_put_x.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_rs_send_put_y.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exch_rs_send_put_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_rs_send_put_y.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h SIZE.h
exch_s3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_s3d_r4.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_s3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_s3d_r8.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_s3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_s3d_rl.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_s3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_s3d_rs.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_sm_3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_sm_3d_r4.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_sm_3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_sm_3d_r8.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_sm_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_sm_3d_rl.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_sm_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_sm_3d_rs.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_uv_3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_uv_3d_r4.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h W2_OPTIONS.h
exch_uv_3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_uv_3d_r8.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h W2_OPTIONS.h
exch_uv_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_uv_3d_rl.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h W2_OPTIONS.h
exch_uv_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_uv_3d_rs.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h W2_OPTIONS.h
exch_uv_agrid_3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_uv_agrid_3d_r4.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_uv_agrid_3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_uv_agrid_3d_r8.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_uv_agrid_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_uv_agrid_3d_rl.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_uv_agrid_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_uv_agrid_3d_rs.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_uv_bgrid_3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_uv_bgrid_3d_r4.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_uv_bgrid_3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_uv_bgrid_3d_r8.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_uv_bgrid_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_uv_bgrid_3d_rl.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_uv_bgrid_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_uv_bgrid_3d_rs.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_uv_dgrid_3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_uv_dgrid_3d_r4.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_uv_dgrid_3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_uv_dgrid_3d_r8.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_uv_dgrid_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_uv_dgrid_3d_rl.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_uv_dgrid_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exch_uv_dgrid_3d_rs.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_uv_xy_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_uv_xy_r4.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h W2_OPTIONS.h
exch_uv_xy_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_uv_xy_r8.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h W2_OPTIONS.h
exch_uv_xy_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_uv_xy_rl.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h W2_OPTIONS.h
exch_uv_xy_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_uv_xy_rs.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h W2_OPTIONS.h
exch_uv_xyz_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_uv_xyz_r4.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h W2_OPTIONS.h
exch_uv_xyz_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_uv_xyz_r8.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h W2_OPTIONS.h
exch_uv_xyz_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_uv_xyz_rl.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h W2_OPTIONS.h
exch_uv_xyz_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_uv_xyz_rs.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h W2_OPTIONS.h
exch_xy_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_xy_r4.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_xy_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_xy_r8.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_xy_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_xy_rl.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_xy_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_xy_rs.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_xyz_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_xyz_r4.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_xyz_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_xyz_r8.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_xyz_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_xyz_rl.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_xyz_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_xyz_rs.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_z_3d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_z_3d_r4.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_z_3d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_z_3d_r8.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_z_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_z_3d_rl.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exch_z_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exch_z_3d_rs.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
exf_ad_dump.f: /usr/include/stdc-predef.h AD_CONFIG.h CPP_EEMACROS.h
exf_ad_dump.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
exf_ad_dump.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
exf_ad_dump.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h EXF_OPTIONS.h EXF_PARAM.h
exf_ad_dump.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
exf_ad_dump.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
exf_ad_dump.f: MNC_PARAMS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
exf_ad_dump.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
exf_ad_dump.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
exf_ad_dump.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
exf_ad_dump.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
exf_ad_dump.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
exf_ad_dump.f: YC_MACROS.h
exf_adjoint_snapshots.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exf_adjoint_snapshots.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
exf_adjoint_snapshots.f: EXF_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
exf_adjoint_snapshots__g.f: /usr/include/stdc-predef.h AD_CONFIG.h
exf_adjoint_snapshots__g.f: CPP_EEMACROS.h CPP_EEOPTIONS.h CPP_OPTIONS.h
exf_adjoint_snapshots__g.f: EEPARAMS.h EXF_OPTIONS.h EXF_PARAM.h
exf_adjoint_snapshots__g.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
exf_adjoint_snapshots_ad.f: /usr/include/stdc-predef.h AD_CONFIG.h
exf_adjoint_snapshots_ad.f: CPP_EEMACROS.h CPP_EEOPTIONS.h CPP_OPTIONS.h
exf_adjoint_snapshots_ad.f: DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_adjoint_snapshots_ad.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
exf_adjoint_snapshots_ad.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h EXF_OPTIONS.h
exf_adjoint_snapshots_ad.f: EXF_PARAM.h FCORI_MACROS.h GRID.h GRID_MACROS.h
exf_adjoint_snapshots_ad.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
exf_adjoint_snapshots_ad.f: MASKS_MACROS.h MASKW_MACROS.h MNC_PARAMS.h
exf_adjoint_snapshots_ad.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
exf_adjoint_snapshots_ad.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
exf_adjoint_snapshots_ad.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
exf_adjoint_snapshots_ad.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
exf_adjoint_snapshots_ad.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
exf_adjoint_snapshots_ad.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
exf_adjoint_snapshots_ad.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
exf_adjoint_snapshots_ad.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
exf_adjoint_snapshots_ad.f: YC_MACROS.h
exf_bulkformulae.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_bulkformulae.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_bulkformulae.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
exf_bulkformulae.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h EXF_CONSTANTS.h
exf_bulkformulae.f: EXF_FIELDS.h EXF_OPTIONS.h EXF_PARAM.h FCORI_MACROS.h
exf_bulkformulae.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
exf_bulkformulae.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
exf_bulkformulae.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
exf_bulkformulae.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
exf_bulkformulae.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
exf_bulkformulae.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
exf_bulkformulae.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
exf_bulkformulae.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
exf_bulkformulae.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
exf_check.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_check.f: CPP_OPTIONS.h EEPARAMS.h EXF_CONSTANTS.h EXF_INTERP_PARAM.h
exf_check.f: EXF_INTERP_SIZE.h EXF_OPTIONS.h EXF_PARAM.h PACKAGES_CONFIG.h
exf_check.f: PARAMS.h SIZE.h
exf_check_range.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_check_range.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_check_range.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
exf_check_range.f: DYU_MACROS.h EEPARAMS.h EXF_FIELDS.h EXF_OPTIONS.h
exf_check_range.f: EXF_PARAM.h FCORI_MACROS.h GRID.h GRID_MACROS.h
exf_check_range.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
exf_check_range.f: MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h RAW_MACROS.h
exf_check_range.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
exf_check_range.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
exf_check_range.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
exf_check_range.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
exf_check_range.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
exf_check_range.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
exf_diagnostics_fill.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exf_diagnostics_fill.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h EXF_FIELDS.h
exf_diagnostics_fill.f: EXF_OPTIONS.h EXF_PARAM.h PACKAGES_CONFIG.h PARAMS.h
exf_diagnostics_fill.f: SIZE.h
exf_diagnostics_init.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exf_diagnostics_init.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h EXF_OPTIONS.h
exf_diagnostics_init.f: EXF_PARAM.h PACKAGES_CONFIG.h
exf_filter_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_filter_rl.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_filter_rl.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
exf_filter_rl.f: DYU_MACROS.h EEPARAMS.h EXF_OPTIONS.h FCORI_MACROS.h GRID.h
exf_filter_rl.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
exf_filter_rl.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
exf_filter_rl.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
exf_filter_rl.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
exf_filter_rl.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
exf_filter_rl.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
exf_filter_rl.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
exf_filter_rl.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
exf_geos_bulkf.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_geos_bulkf.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_geos_bulkf.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
exf_geos_bulkf.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h EXF_CONSTANTS.h
exf_geos_bulkf.f: EXF_FIELDS.h EXF_OPTIONS.h EXF_PARAM.h FCORI_MACROS.h GRID.h
exf_geos_bulkf.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
exf_geos_bulkf.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
exf_geos_bulkf.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
exf_geos_bulkf.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
exf_geos_bulkf.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
exf_geos_bulkf.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
exf_geos_bulkf.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
exf_geos_bulkf.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
exf_getclim.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_getclim.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_getclim.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
exf_getclim.f: DYU_MACROS.h EEPARAMS.h EXF_CONSTANTS.h EXF_FIELDS.h
exf_getclim.f: EXF_INTERP_PARAM.h EXF_INTERP_SIZE.h EXF_OPTIONS.h EXF_PARAM.h
exf_getclim.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
exf_getclim.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
exf_getclim.f: PACKAGES_CONFIG.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
exf_getclim.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
exf_getclim.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
exf_getclim.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
exf_getclim.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
exf_getclim.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
exf_getffield_start.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exf_getffield_start.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h EXF_OPTIONS.h
exf_getffield_start.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
exf_getffieldrec.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_getffieldrec.f: CPP_OPTIONS.h EEPARAMS.h EXF_OPTIONS.h EXF_PARAM.h
exf_getffieldrec.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h cal.h
exf_getffields.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_getffields.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_getffields.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
exf_getffields.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h EXF_CONSTANTS.h
exf_getffields.f: EXF_FIELDS.h EXF_INTERP_PARAM.h EXF_INTERP_SIZE.h
exf_getffields.f: EXF_OPTIONS.h EXF_PARAM.h FCORI_MACROS.h GRID.h
exf_getffields.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
exf_getffields.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
exf_getffields.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
exf_getffields.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
exf_getffields.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
exf_getffields.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
exf_getffields.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
exf_getffields.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
exf_getfield_start.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exf_getfield_start.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h EXF_OPTIONS.h
exf_getfield_start.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
exf_getforcing.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_getforcing.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_getforcing.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
exf_getforcing.f: DYU_MACROS.h EEPARAMS.h EXF_CONSTANTS.h EXF_FIELDS.h
exf_getforcing.f: EXF_OPTIONS.h EXF_PARAM.h FCORI_MACROS.h GRID.h
exf_getforcing.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
exf_getforcing.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
exf_getforcing.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
exf_getforcing.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
exf_getforcing.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
exf_getforcing.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
exf_getforcing.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
exf_getforcing.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
exf_getsurfacefluxes.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exf_getsurfacefluxes.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
exf_getsurfacefluxes.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
exf_getsurfacefluxes.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
exf_getsurfacefluxes.f: EXF_FIELDS.h EXF_OPTIONS.h EXF_PARAM.h FCORI_MACROS.h
exf_getsurfacefluxes.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
exf_getsurfacefluxes.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
exf_getsurfacefluxes.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
exf_getsurfacefluxes.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
exf_getsurfacefluxes.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
exf_getsurfacefluxes.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
exf_getsurfacefluxes.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
exf_getsurfacefluxes.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
exf_getsurfacefluxes.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
exf_getsurfacefluxes.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
exf_getyearlyfieldname.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exf_getyearlyfieldname.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EXF_OPTIONS.h
exf_getyearlyfieldname.f: PACKAGES_CONFIG.h
exf_init_fixed.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_init_fixed.f: CPP_OPTIONS.h EEPARAMS.h EXF_CONSTANTS.h EXF_INTERP_PARAM.h
exf_init_fixed.f: EXF_INTERP_SIZE.h EXF_OPTIONS.h EXF_PARAM.h
exf_init_fixed.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
exf_init_fld.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_init_fld.f: CPP_OPTIONS.h EEPARAMS.h EXF_INTERP_SIZE.h EXF_OPTIONS.h
exf_init_fld.f: EXF_PARAM.h PACKAGES_CONFIG.h SIZE.h
exf_init_interp.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_init_interp.f: CPP_OPTIONS.h EEPARAMS.h EXF_INTERP_PARAM.h
exf_init_interp.f: EXF_INTERP_SIZE.h EXF_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
exf_init_interp.f: SIZE.h W2_OPTIONS.h
exf_init_varia.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_init_varia.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_init_varia.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
exf_init_varia.f: DYU_MACROS.h EEPARAMS.h EXF_FIELDS.h EXF_INTERP_PARAM.h
exf_init_varia.f: EXF_INTERP_SIZE.h EXF_OPTIONS.h EXF_PARAM.h FCORI_MACROS.h
exf_init_varia.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
exf_init_varia.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
exf_init_varia.f: PACKAGES_CONFIG.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
exf_init_varia.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
exf_init_varia.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
exf_init_varia.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
exf_init_varia.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
exf_init_varia.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
exf_init_varia.f: YC_MACROS.h
exf_interp.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_interp.f: CPP_OPTIONS.h EEPARAMS.h EXF_INTERP_SIZE.h EXF_OPTIONS.h
exf_interp.f: EXF_PARAM.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
exf_interp_read.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
exf_interp_read.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_interp_read.f: CPP_OPTIONS.h EEPARAMS.h EESUPPORT.h EXF_INTERP_SIZE.h
exf_interp_read.f: EXF_OPTIONS.h EXF_PARAM.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
exf_interp_uv.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_interp_uv.f: CPP_OPTIONS.h EEPARAMS.h EXF_INTERP_SIZE.h EXF_OPTIONS.h
exf_interp_uv.f: EXF_PARAM.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
exf_interpolate.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_interpolate.f: CPP_OPTIONS.h EEPARAMS.h EXF_OPTIONS.h PACKAGES_CONFIG.h
exf_interpolate.f: PARAMS.h SIZE.h
exf_mapfields.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_mapfields.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_mapfields.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
exf_mapfields.f: DYU_MACROS.h EEPARAMS.h EXF_CONSTANTS.h EXF_FIELDS.h
exf_mapfields.f: EXF_OPTIONS.h EXF_PARAM.h FCORI_MACROS.h FFIELDS.h GRID.h
exf_mapfields.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
exf_mapfields.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
exf_mapfields.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
exf_mapfields.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
exf_mapfields.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
exf_mapfields.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
exf_mapfields.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
exf_mapfields.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
exf_monitor.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_monitor.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_monitor.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
exf_monitor.f: DYU_MACROS.h EEPARAMS.h EXF_FIELDS.h EXF_OPTIONS.h EXF_PARAM.h
exf_monitor.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
exf_monitor.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
exf_monitor.f: MNC_PARAMS.h MONITOR.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
exf_monitor.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
exf_monitor.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
exf_monitor.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
exf_monitor.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
exf_monitor.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
exf_monitor.f: YC_MACROS.h
exf_monitor_ad.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_monitor_ad.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_monitor_ad.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
exf_monitor_ad.f: DYU_MACROS.h EEPARAMS.h EXF_FIELDS.h EXF_OPTIONS.h
exf_monitor_ad.f: EXF_PARAM.h FCORI_MACROS.h GRID.h GRID_MACROS.h
exf_monitor_ad.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
exf_monitor_ad.f: MASKW_MACROS.h MNC_PARAMS.h MONITOR.h PACKAGES_CONFIG.h
exf_monitor_ad.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
exf_monitor_ad.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
exf_monitor_ad.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
exf_monitor_ad.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
exf_monitor_ad.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
exf_monitor_ad.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
exf_monitor_ad.f: YC_MACROS.h
exf_radiation.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_radiation.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_radiation.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
exf_radiation.f: DYU_MACROS.h EEPARAMS.h EXF_CONSTANTS.h EXF_FIELDS.h
exf_radiation.f: EXF_OPTIONS.h EXF_PARAM.h FCORI_MACROS.h GRID.h GRID_MACROS.h
exf_radiation.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
exf_radiation.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
exf_radiation.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
exf_radiation.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
exf_radiation.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
exf_radiation.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
exf_radiation.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
exf_radiation.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
exf_readparms.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_readparms.f: CPP_OPTIONS.h EEPARAMS.h EXF_CONSTANTS.h EXF_INTERP_PARAM.h
exf_readparms.f: EXF_INTERP_SIZE.h EXF_OPTIONS.h EXF_PARAM.h PACKAGES_CONFIG.h
exf_readparms.f: PARAMS.h SIZE.h
exf_set_fld.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_set_fld.f: CPP_OPTIONS.h EEPARAMS.h EXF_CONSTANTS.h EXF_INTERP_PARAM.h
exf_set_fld.f: EXF_INTERP_SIZE.h EXF_OPTIONS.h EXF_PARAM.h PACKAGES_CONFIG.h
exf_set_fld.f: PARAMS.h SIZE.h
exf_set_gen.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_set_gen.f: CPP_OPTIONS.h EEPARAMS.h EXF_INTERP_SIZE.h EXF_OPTIONS.h
exf_set_gen.f: EXF_PARAM.h PACKAGES_CONFIG.h SIZE.h
exf_set_obcs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_set_obcs.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_set_obcs.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
exf_set_obcs.f: DYU_MACROS.h EEPARAMS.h EXF_CONSTANTS.h EXF_OPTIONS.h
exf_set_obcs.f: EXF_PARAM.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
exf_set_obcs.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
exf_set_obcs.f: PACKAGES_CONFIG.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
exf_set_obcs.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
exf_set_obcs.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
exf_set_obcs.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
exf_set_obcs.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
exf_set_obcs.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
exf_set_uv.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_set_uv.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_set_uv.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h
exf_set_uv.f: EEPARAMS.h EXF_CONSTANTS.h EXF_FIELDS.h EXF_INTERP_PARAM.h
exf_set_uv.f: EXF_INTERP_SIZE.h EXF_OPTIONS.h EXF_PARAM.h FCORI_MACROS.h
exf_set_uv.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
exf_set_uv.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
exf_set_uv.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
exf_set_uv.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
exf_set_uv.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
exf_set_uv.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
exf_set_uv.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
exf_set_uv.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
exf_summary.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_summary.f: CPP_OPTIONS.h EEPARAMS.h EXF_CONSTANTS.h EXF_INTERP_PARAM.h
exf_summary.f: EXF_INTERP_SIZE.h EXF_OPTIONS.h EXF_PARAM.h PACKAGES_CONFIG.h
exf_summary.f: SIZE.h
exf_swapffields.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_swapffields.f: CPP_OPTIONS.h EEPARAMS.h EXF_OPTIONS.h PACKAGES_CONFIG.h
exf_swapffields.f: SIZE.h
exf_weight_sfx_diags.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exf_weight_sfx_diags.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h EXF_FIELDS.h
exf_weight_sfx_diags.f: EXF_OPTIONS.h EXF_PARAM.h PACKAGES_CONFIG.h PARAMS.h
exf_weight_sfx_diags.f: SIZE.h
exf_wind.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_wind.f: CPP_OPTIONS.h EEPARAMS.h EXF_CONSTANTS.h EXF_FIELDS.h
exf_wind.f: EXF_OPTIONS.h EXF_PARAM.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
exf_zenithangle.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
exf_zenithangle.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
exf_zenithangle.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
exf_zenithangle.f: DYU_MACROS.h EEPARAMS.h EXF_CONSTANTS.h EXF_FIELDS.h
exf_zenithangle.f: EXF_OPTIONS.h EXF_PARAM.h FCORI_MACROS.h GRID.h
exf_zenithangle.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
exf_zenithangle.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
exf_zenithangle.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
exf_zenithangle.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
exf_zenithangle.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
exf_zenithangle.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
exf_zenithangle.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
exf_zenithangle.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
exf_zenithangle.f: YC_MACROS.h cal.h
exf_zenithangle_table.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
exf_zenithangle_table.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
exf_zenithangle_table.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
exf_zenithangle_table.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
exf_zenithangle_table.f: EXF_CONSTANTS.h EXF_FIELDS.h EXF_OPTIONS.h
exf_zenithangle_table.f: EXF_PARAM.h FCORI_MACROS.h GRID.h GRID_MACROS.h
exf_zenithangle_table.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
exf_zenithangle_table.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
exf_zenithangle_table.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
exf_zenithangle_table.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
exf_zenithangle_table.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
exf_zenithangle_table.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
exf_zenithangle_table.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
exf_zenithangle_table.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
exf_zenithangle_table.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
exf_zenithangle_table.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
external_fields_load.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
external_fields_load.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
external_fields_load.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
external_fields_load.f: DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
external_fields_load.f: EEPARAMS.h FCORI_MACROS.h FFIELDS.h GRID.h
external_fields_load.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
external_fields_load.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
external_fields_load.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
external_fields_load.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
external_fields_load.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
external_fields_load.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
external_fields_load.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
external_fields_load.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
external_fields_load.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
external_fields_load.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
external_forcing.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
external_forcing.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
external_forcing.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
external_forcing.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h FFIELDS.h
external_forcing.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
external_forcing.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
external_forcing.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
external_forcing.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
external_forcing.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
external_forcing.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
external_forcing.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
external_forcing.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
external_forcing.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
external_forcing_surf.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
external_forcing_surf.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
external_forcing_surf.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
external_forcing_surf.f: DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
external_forcing_surf.f: EEPARAMS.h FCORI_MACROS.h FFIELDS.h GRID.h
external_forcing_surf.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
external_forcing_surf.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
external_forcing_surf.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
external_forcing_surf.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
external_forcing_surf.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
external_forcing_surf.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
external_forcing_surf.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
external_forcing_surf.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
external_forcing_surf.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
external_forcing_surf.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
external_forcing_surf.f: YC_MACROS.h
fill_cs_corner_ag_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
fill_cs_corner_ag_rl.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
fill_cs_corner_ag_rl.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
fill_cs_corner_tr_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
fill_cs_corner_tr_rl.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
fill_cs_corner_tr_rl.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
fill_cs_corner_uv_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
fill_cs_corner_uv_rl.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
fill_cs_corner_uv_rl.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
fill_cs_corner_uv_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
fill_cs_corner_uv_rs.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
fill_cs_corner_uv_rs.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
fill_in_corners_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
fill_in_corners_rl.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h
find_alpha.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
find_alpha.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
find_alpha.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
find_alpha.f: DYU_MACROS.h EEPARAMS.h EOS.h FCORI_MACROS.h GRID.h
find_alpha.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
find_alpha.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
find_alpha.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
find_alpha.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
find_alpha.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
find_alpha.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
find_alpha.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
find_alpha.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
find_hyd_press_1d.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
find_hyd_press_1d.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
find_hyd_press_1d.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
find_hyd_press_1d.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
find_hyd_press_1d.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
find_hyd_press_1d.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PARAMS.h
find_hyd_press_1d.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
find_hyd_press_1d.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
find_hyd_press_1d.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
find_hyd_press_1d.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
find_hyd_press_1d.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
find_hyd_press_1d.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
find_hyd_press_1d.f: YC_MACROS.h
find_rho.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
find_rho.f: CPP_OPTIONS.h EEPARAMS.h EOS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
fool_the_compiler.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
forcing_surf_relax.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
forcing_surf_relax.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
forcing_surf_relax.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
forcing_surf_relax.f: DYG_MACROS.h DYNVARS.h DYU_MACROS.h EEPARAMS.h
forcing_surf_relax.f: FCORI_MACROS.h FFIELDS.h GRID.h GRID_MACROS.h
forcing_surf_relax.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
forcing_surf_relax.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
forcing_surf_relax.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
forcing_surf_relax.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
forcing_surf_relax.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
forcing_surf_relax.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
forcing_surf_relax.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SEAICE.h
forcing_surf_relax.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h SURFACE.h
forcing_surf_relax.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
forcing_surf_relax.f: YC_MACROS.h
forward_step.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
forward_step.f: CPP_OPTIONS.h DYNVARS.h EEPARAMS.h EXF_OPTIONS.h GAD_OPTIONS.h
forward_step.f: GMREDI_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h SEAICE_OPTIONS.h
forward_step.f: SIGREG.h SIZE.h THSICE_OPTIONS.h
freesurf_rescale_g.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
freesurf_rescale_g.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
freesurf_rescale_g.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
freesurf_rescale_g.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
freesurf_rescale_g.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
freesurf_rescale_g.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PARAMS.h
freesurf_rescale_g.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
freesurf_rescale_g.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
freesurf_rescale_g.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
freesurf_rescale_g.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
freesurf_rescale_g.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
freesurf_rescale_g.f: SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
freesurf_rescale_g.f: XC_MACROS.h YC_MACROS.h
freeze_surface.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
freeze_surface.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
freeze_surface.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
freeze_surface.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h FFIELDS.h
freeze_surface.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
freeze_surface.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
freeze_surface.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
freeze_surface.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
freeze_surface.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
freeze_surface.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
freeze_surface.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
freeze_surface.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
freeze_surface.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_advection.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_advection.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_advection.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_advection.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h
gad_advection.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
gad_advection.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
gad_advection.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
gad_advection.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_advection.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_advection.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_advection.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_advection.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_advection.f: TANPHIATV_MACROS.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
gad_advection.f: XC_MACROS.h YC_MACROS.h
gad_advscheme.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_advscheme.f: CPP_OPTIONS.h EEPARAMS.h GAD.h GAD_OPTIONS.h
gad_advscheme.f: PACKAGES_CONFIG.h SIZE.h
gad_biharm_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_biharm_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_biharm_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_biharm_r.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD_OPTIONS.h GRID.h
gad_biharm_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_biharm_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
gad_biharm_r.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_biharm_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_biharm_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_biharm_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_biharm_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_biharm_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_biharm_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_biharm_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_biharm_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_biharm_x.f: DYU_MACROS.h FCORI_MACROS.h GAD_OPTIONS.h GRID.h GRID_MACROS.h
gad_biharm_x.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gad_biharm_x.f: MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h RAW_MACROS.h
gad_biharm_x.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_biharm_x.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_biharm_x.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_biharm_x.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
gad_biharm_x.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_biharm_x.f: YC_MACROS.h
gad_biharm_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_biharm_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_biharm_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_biharm_y.f: DYU_MACROS.h FCORI_MACROS.h GAD_OPTIONS.h GRID.h GRID_MACROS.h
gad_biharm_y.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gad_biharm_y.f: MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h RAW_MACROS.h
gad_biharm_y.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_biharm_y.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_biharm_y.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_biharm_y.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
gad_biharm_y.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_biharm_y.f: YC_MACROS.h
gad_c2_adv_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_c2_adv_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_c2_adv_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_c2_adv_r.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD_OPTIONS.h GRID.h
gad_c2_adv_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_c2_adv_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
gad_c2_adv_r.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_c2_adv_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_c2_adv_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_c2_adv_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_c2_adv_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_c2_adv_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_c2_adv_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_c2_adv_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_c2_adv_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_c2_adv_x.f: DYU_MACROS.h FCORI_MACROS.h GAD_OPTIONS.h GRID.h GRID_MACROS.h
gad_c2_adv_x.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gad_c2_adv_x.f: MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h RAW_MACROS.h
gad_c2_adv_x.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_c2_adv_x.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_c2_adv_x.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_c2_adv_x.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
gad_c2_adv_x.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_c2_adv_x.f: YC_MACROS.h
gad_c2_adv_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_c2_adv_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_c2_adv_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_c2_adv_y.f: DYU_MACROS.h FCORI_MACROS.h GAD_OPTIONS.h GRID.h GRID_MACROS.h
gad_c2_adv_y.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gad_c2_adv_y.f: MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h RAW_MACROS.h
gad_c2_adv_y.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_c2_adv_y.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_c2_adv_y.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_c2_adv_y.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
gad_c2_adv_y.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_c2_adv_y.f: YC_MACROS.h
gad_c2_impl_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_c2_impl_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_c2_impl_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_c2_impl_r.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD_OPTIONS.h GRID.h
gad_c2_impl_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_c2_impl_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
gad_c2_impl_r.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_c2_impl_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_c2_impl_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_c2_impl_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_c2_impl_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_c2_impl_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_c4_adv_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_c4_adv_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_c4_adv_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_c4_adv_r.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_c4_adv_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_c4_adv_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_c4_adv_r.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_c4_adv_r.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_c4_adv_r.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_c4_adv_r.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
gad_c4_adv_r.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_c4_adv_r.f: YC_MACROS.h
gad_c4_adv_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_c4_adv_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_c4_adv_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_c4_adv_x.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_c4_adv_x.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_c4_adv_x.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_c4_adv_x.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_c4_adv_x.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_c4_adv_x.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_c4_adv_x.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
gad_c4_adv_x.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_c4_adv_x.f: YC_MACROS.h
gad_c4_adv_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_c4_adv_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_c4_adv_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_c4_adv_y.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_c4_adv_y.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_c4_adv_y.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_c4_adv_y.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_c4_adv_y.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_c4_adv_y.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_c4_adv_y.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
gad_c4_adv_y.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_c4_adv_y.f: YC_MACROS.h
gad_calc_rhs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_calc_rhs.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_calc_rhs.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_calc_rhs.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h
gad_calc_rhs.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
gad_calc_rhs.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
gad_calc_rhs.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
gad_calc_rhs.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
gad_calc_rhs.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
gad_calc_rhs.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gad_calc_rhs.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
gad_calc_rhs.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_check.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_check.f: CPP_OPTIONS.h EEPARAMS.h GAD.h GAD_OPTIONS.h PACKAGES_CONFIG.h
gad_check.f: PARAMS.h SIZE.h
gad_del2.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_del2.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
gad_del2.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h FCORI_MACROS.h
gad_del2.f: GAD_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
gad_del2.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
gad_del2.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_del2.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_del2.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_del2.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_del2.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
gad_del2.f: XC_MACROS.h YC_MACROS.h
gad_diagnostics_init.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gad_diagnostics_init.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h GAD.h
gad_diagnostics_init.f: GAD_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
gad_diagnostics_state.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gad_diagnostics_state.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
gad_diagnostics_state.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
gad_diagnostics_state.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
gad_diagnostics_state.f: FCORI_MACROS.h GAD.h GAD_OPTIONS.h GAD_SOM_VARS.h
gad_diagnostics_state.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
gad_diagnostics_state.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
gad_diagnostics_state.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
gad_diagnostics_state.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_diagnostics_state.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_diagnostics_state.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
gad_diagnostics_state.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_diagnostics_state.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_diagnostics_state.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_diagnostics_state.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_diff_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_diff_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_diff_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h
gad_diff_r.f: EEPARAMS.h FCORI_MACROS.h GAD_OPTIONS.h GRID.h GRID_MACROS.h
gad_diff_r.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gad_diff_r.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
gad_diff_r.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_diff_r.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_diff_r.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_diff_r.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
gad_diff_r.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_diff_r.f: YC_MACROS.h
gad_diff_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_diff_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_diff_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h
gad_diff_x.f: FCORI_MACROS.h GAD_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
gad_diff_x.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
gad_diff_x.f: PACKAGES_CONFIG.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
gad_diff_x.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
gad_diff_x.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
gad_diff_x.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gad_diff_x.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gad_diff_x.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_diff_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_diff_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_diff_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h
gad_diff_y.f: FCORI_MACROS.h GAD_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
gad_diff_y.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
gad_diff_y.f: PACKAGES_CONFIG.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
gad_diff_y.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
gad_diff_y.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
gad_diff_y.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gad_diff_y.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gad_diff_y.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_dst2u1_adv_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_dst2u1_adv_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_dst2u1_adv_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_dst2u1_adv_r.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_dst2u1_adv_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_dst2u1_adv_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
gad_dst2u1_adv_r.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_dst2u1_adv_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_dst2u1_adv_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_dst2u1_adv_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gad_dst2u1_adv_r.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gad_dst2u1_adv_r.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_dst2u1_adv_r.f: YC_MACROS.h
gad_dst2u1_adv_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_dst2u1_adv_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_dst2u1_adv_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_dst2u1_adv_x.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_dst2u1_adv_x.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_dst2u1_adv_x.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
gad_dst2u1_adv_x.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_dst2u1_adv_x.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_dst2u1_adv_x.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_dst2u1_adv_x.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gad_dst2u1_adv_x.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gad_dst2u1_adv_x.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_dst2u1_adv_x.f: YC_MACROS.h
gad_dst2u1_adv_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_dst2u1_adv_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_dst2u1_adv_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_dst2u1_adv_y.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_dst2u1_adv_y.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_dst2u1_adv_y.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
gad_dst2u1_adv_y.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_dst2u1_adv_y.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_dst2u1_adv_y.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_dst2u1_adv_y.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gad_dst2u1_adv_y.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gad_dst2u1_adv_y.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_dst2u1_adv_y.f: YC_MACROS.h
gad_dst2u1_impl_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_dst2u1_impl_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_dst2u1_impl_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_dst2u1_impl_r.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h
gad_dst2u1_impl_r.f: GAD_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
gad_dst2u1_impl_r.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gad_dst2u1_impl_r.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
gad_dst2u1_impl_r.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_dst2u1_impl_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_dst2u1_impl_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_dst2u1_impl_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gad_dst2u1_impl_r.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gad_dst2u1_impl_r.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_dst2u1_impl_r.f: YC_MACROS.h
gad_dst3_adv_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_dst3_adv_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_dst3_adv_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_dst3_adv_r.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_dst3_adv_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_dst3_adv_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_dst3_adv_r.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_dst3_adv_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_dst3_adv_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_dst3_adv_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_dst3_adv_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_dst3_adv_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_dst3_adv_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_dst3_adv_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_dst3_adv_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_dst3_adv_x.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_dst3_adv_x.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_dst3_adv_x.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_dst3_adv_x.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_dst3_adv_x.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_dst3_adv_x.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_dst3_adv_x.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_dst3_adv_x.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_dst3_adv_x.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_dst3_adv_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_dst3_adv_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_dst3_adv_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_dst3_adv_y.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_dst3_adv_y.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_dst3_adv_y.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_dst3_adv_y.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_dst3_adv_y.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_dst3_adv_y.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_dst3_adv_y.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_dst3_adv_y.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_dst3_adv_y.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_dst3fl_adv_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_dst3fl_adv_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_dst3fl_adv_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_dst3fl_adv_r.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_dst3fl_adv_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_dst3fl_adv_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
gad_dst3fl_adv_r.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_dst3fl_adv_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_dst3fl_adv_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_dst3fl_adv_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gad_dst3fl_adv_r.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gad_dst3fl_adv_r.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_dst3fl_adv_r.f: YC_MACROS.h
gad_dst3fl_adv_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_dst3fl_adv_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_dst3fl_adv_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_dst3fl_adv_x.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_dst3fl_adv_x.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_dst3fl_adv_x.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
gad_dst3fl_adv_x.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_dst3fl_adv_x.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_dst3fl_adv_x.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_dst3fl_adv_x.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gad_dst3fl_adv_x.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gad_dst3fl_adv_x.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_dst3fl_adv_x.f: YC_MACROS.h
gad_dst3fl_adv_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_dst3fl_adv_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_dst3fl_adv_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_dst3fl_adv_y.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_dst3fl_adv_y.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_dst3fl_adv_y.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
gad_dst3fl_adv_y.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_dst3fl_adv_y.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_dst3fl_adv_y.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_dst3fl_adv_y.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gad_dst3fl_adv_y.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gad_dst3fl_adv_y.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_dst3fl_adv_y.f: YC_MACROS.h
gad_dst3fl_impl_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_dst3fl_impl_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_dst3fl_impl_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_dst3fl_impl_r.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h
gad_dst3fl_impl_r.f: GAD_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
gad_dst3fl_impl_r.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gad_dst3fl_impl_r.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
gad_dst3fl_impl_r.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_dst3fl_impl_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_dst3fl_impl_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_dst3fl_impl_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gad_dst3fl_impl_r.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gad_dst3fl_impl_r.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_dst3fl_impl_r.f: YC_MACROS.h
gad_exch_som.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_exch_som.f: CPP_OPTIONS.h EEPARAMS.h GAD.h GAD_OPTIONS.h PACKAGES_CONFIG.h
gad_exch_som.f: SIZE.h
gad_fluxlimit_adv_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gad_fluxlimit_adv_r.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
gad_fluxlimit_adv_r.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
gad_fluxlimit_adv_r.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
gad_fluxlimit_adv_r.f: GAD_FLUX_LIMITER.h GAD_OPTIONS.h GRID.h GRID_MACROS.h
gad_fluxlimit_adv_r.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_fluxlimit_adv_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
gad_fluxlimit_adv_r.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
gad_fluxlimit_adv_r.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_fluxlimit_adv_r.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_fluxlimit_adv_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
gad_fluxlimit_adv_r.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_fluxlimit_adv_r.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_fluxlimit_adv_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_fluxlimit_adv_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_fluxlimit_adv_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gad_fluxlimit_adv_x.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
gad_fluxlimit_adv_x.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
gad_fluxlimit_adv_x.f: DYG_MACROS.h DYU_MACROS.h FCORI_MACROS.h
gad_fluxlimit_adv_x.f: GAD_FLUX_LIMITER.h GAD_OPTIONS.h GRID.h GRID_MACROS.h
gad_fluxlimit_adv_x.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_fluxlimit_adv_x.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
gad_fluxlimit_adv_x.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
gad_fluxlimit_adv_x.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_fluxlimit_adv_x.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_fluxlimit_adv_x.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
gad_fluxlimit_adv_x.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_fluxlimit_adv_x.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_fluxlimit_adv_x.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_fluxlimit_adv_x.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_fluxlimit_adv_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gad_fluxlimit_adv_y.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
gad_fluxlimit_adv_y.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
gad_fluxlimit_adv_y.f: DYG_MACROS.h DYU_MACROS.h FCORI_MACROS.h
gad_fluxlimit_adv_y.f: GAD_FLUX_LIMITER.h GAD_OPTIONS.h GRID.h GRID_MACROS.h
gad_fluxlimit_adv_y.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_fluxlimit_adv_y.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
gad_fluxlimit_adv_y.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
gad_fluxlimit_adv_y.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_fluxlimit_adv_y.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_fluxlimit_adv_y.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
gad_fluxlimit_adv_y.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_fluxlimit_adv_y.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_fluxlimit_adv_y.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_fluxlimit_adv_y.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_fluxlimit_impl_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gad_fluxlimit_impl_r.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
gad_fluxlimit_impl_r.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
gad_fluxlimit_impl_r.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
gad_fluxlimit_impl_r.f: FCORI_MACROS.h GAD_FLUX_LIMITER.h GAD_OPTIONS.h GRID.h
gad_fluxlimit_impl_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
gad_fluxlimit_impl_r.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
gad_fluxlimit_impl_r.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
gad_fluxlimit_impl_r.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_fluxlimit_impl_r.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_fluxlimit_impl_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
gad_fluxlimit_impl_r.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_fluxlimit_impl_r.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_fluxlimit_impl_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_fluxlimit_impl_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_grad_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_grad_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_grad_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h
gad_grad_x.f: EEPARAMS.h FCORI_MACROS.h GAD_OPTIONS.h GRID.h GRID_MACROS.h
gad_grad_x.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gad_grad_x.f: MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h RAW_MACROS.h
gad_grad_x.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_grad_x.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_grad_x.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_grad_x.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
gad_grad_x.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_grad_x.f: YC_MACROS.h
gad_grad_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_grad_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_grad_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h
gad_grad_y.f: EEPARAMS.h FCORI_MACROS.h GAD_OPTIONS.h GRID.h GRID_MACROS.h
gad_grad_y.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gad_grad_y.f: MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h RAW_MACROS.h
gad_grad_y.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_grad_y.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_grad_y.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_grad_y.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
gad_grad_y.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_grad_y.f: YC_MACROS.h
gad_implicit_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_implicit_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_implicit_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_implicit_r.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h
gad_implicit_r.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
gad_implicit_r.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
gad_implicit_r.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
gad_implicit_r.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_implicit_r.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_implicit_r.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_implicit_r.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_implicit_r.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
gad_implicit_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_init_fixed.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_init_fixed.f: CPP_OPTIONS.h EEPARAMS.h GAD.h GAD_OPTIONS.h
gad_init_fixed.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
gad_init_varia.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_init_varia.f: CPP_OPTIONS.h EEPARAMS.h GAD.h GAD_OPTIONS.h GAD_SOM_VARS.h
gad_init_varia.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
gad_os7mp_adv_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_os7mp_adv_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_os7mp_adv_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_os7mp_adv_r.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_os7mp_adv_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_os7mp_adv_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
gad_os7mp_adv_r.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_os7mp_adv_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_os7mp_adv_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_os7mp_adv_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gad_os7mp_adv_r.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gad_os7mp_adv_r.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_os7mp_adv_r.f: YC_MACROS.h
gad_os7mp_adv_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_os7mp_adv_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_os7mp_adv_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_os7mp_adv_x.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_os7mp_adv_x.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_os7mp_adv_x.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
gad_os7mp_adv_x.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_os7mp_adv_x.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_os7mp_adv_x.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_os7mp_adv_x.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gad_os7mp_adv_x.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gad_os7mp_adv_x.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_os7mp_adv_x.f: YC_MACROS.h
gad_os7mp_adv_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_os7mp_adv_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_os7mp_adv_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_os7mp_adv_y.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_os7mp_adv_y.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_os7mp_adv_y.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
gad_os7mp_adv_y.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_os7mp_adv_y.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_os7mp_adv_y.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_os7mp_adv_y.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gad_os7mp_adv_y.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gad_os7mp_adv_y.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_os7mp_adv_y.f: YC_MACROS.h
gad_osc_hat_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_osc_hat_r.f: CPP_OPTIONS.h GAD_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
gad_osc_hat_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_osc_hat_x.f: CPP_OPTIONS.h GAD_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
gad_osc_hat_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_osc_hat_y.f: CPP_OPTIONS.h GAD_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
gad_osc_mul_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_osc_mul_r.f: CPP_OPTIONS.h GAD_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
gad_osc_mul_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_osc_mul_x.f: CPP_OPTIONS.h GAD_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
gad_osc_mul_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_osc_mul_y.f: CPP_OPTIONS.h GAD_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
gad_plm_fun.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_plm_fun.f: CPP_OPTIONS.h GAD_OPTIONS.h PACKAGES_CONFIG.h
gad_ppm_adv_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_ppm_adv_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_ppm_adv_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_ppm_adv_r.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_ppm_adv_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_ppm_adv_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_ppm_adv_r.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_ppm_adv_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_ppm_adv_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_ppm_adv_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_ppm_adv_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_ppm_adv_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_ppm_adv_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_ppm_adv_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_ppm_adv_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_ppm_adv_x.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_ppm_adv_x.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_ppm_adv_x.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_ppm_adv_x.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_ppm_adv_x.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_ppm_adv_x.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_ppm_adv_x.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_ppm_adv_x.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_ppm_adv_x.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_ppm_adv_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_ppm_adv_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_ppm_adv_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_ppm_adv_y.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_ppm_adv_y.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_ppm_adv_y.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_ppm_adv_y.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_ppm_adv_y.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_ppm_adv_y.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_ppm_adv_y.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_ppm_adv_y.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_ppm_adv_y.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_ppm_flx_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_ppm_flx_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_ppm_flx_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_ppm_flx_r.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_ppm_flx_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_ppm_flx_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_ppm_flx_r.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_ppm_flx_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_ppm_flx_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_ppm_flx_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_ppm_flx_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_ppm_flx_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_ppm_flx_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_ppm_flx_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_ppm_flx_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_ppm_flx_x.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_ppm_flx_x.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_ppm_flx_x.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_ppm_flx_x.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_ppm_flx_x.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_ppm_flx_x.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_ppm_flx_x.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_ppm_flx_x.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_ppm_flx_x.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_ppm_flx_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_ppm_flx_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_ppm_flx_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_ppm_flx_y.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_ppm_flx_y.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_ppm_flx_y.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_ppm_flx_y.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_ppm_flx_y.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_ppm_flx_y.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_ppm_flx_y.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_ppm_flx_y.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_ppm_flx_y.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_ppm_fun.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_ppm_fun.f: CPP_OPTIONS.h GAD_OPTIONS.h PACKAGES_CONFIG.h
gad_ppm_hat_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_ppm_hat_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_ppm_hat_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_ppm_hat_r.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_ppm_hat_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_ppm_hat_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_ppm_hat_r.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_ppm_hat_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_ppm_hat_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_ppm_hat_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_ppm_hat_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_ppm_hat_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_ppm_hat_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_ppm_hat_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_ppm_hat_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_ppm_hat_x.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_ppm_hat_x.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_ppm_hat_x.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_ppm_hat_x.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_ppm_hat_x.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_ppm_hat_x.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_ppm_hat_x.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_ppm_hat_x.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_ppm_hat_x.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_ppm_hat_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_ppm_hat_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_ppm_hat_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_ppm_hat_y.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_ppm_hat_y.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_ppm_hat_y.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_ppm_hat_y.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_ppm_hat_y.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_ppm_hat_y.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_ppm_hat_y.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_ppm_hat_y.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_ppm_hat_y.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_ppm_p3e_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_ppm_p3e_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_ppm_p3e_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_ppm_p3e_r.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_ppm_p3e_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_ppm_p3e_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_ppm_p3e_r.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_ppm_p3e_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_ppm_p3e_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_ppm_p3e_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_ppm_p3e_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_ppm_p3e_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_ppm_p3e_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_ppm_p3e_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_ppm_p3e_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_ppm_p3e_x.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_ppm_p3e_x.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_ppm_p3e_x.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_ppm_p3e_x.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_ppm_p3e_x.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_ppm_p3e_x.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_ppm_p3e_x.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_ppm_p3e_x.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_ppm_p3e_x.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_ppm_p3e_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_ppm_p3e_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_ppm_p3e_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_ppm_p3e_y.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_ppm_p3e_y.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_ppm_p3e_y.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_ppm_p3e_y.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_ppm_p3e_y.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_ppm_p3e_y.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_ppm_p3e_y.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_ppm_p3e_y.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_ppm_p3e_y.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_pqm_adv_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_pqm_adv_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_pqm_adv_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_pqm_adv_r.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_pqm_adv_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_pqm_adv_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_pqm_adv_r.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_pqm_adv_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_pqm_adv_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_pqm_adv_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_pqm_adv_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_pqm_adv_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_pqm_adv_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_pqm_adv_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_pqm_adv_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_pqm_adv_x.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_pqm_adv_x.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_pqm_adv_x.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_pqm_adv_x.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_pqm_adv_x.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_pqm_adv_x.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_pqm_adv_x.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_pqm_adv_x.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_pqm_adv_x.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_pqm_adv_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_pqm_adv_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_pqm_adv_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_pqm_adv_y.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_pqm_adv_y.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_pqm_adv_y.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_pqm_adv_y.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_pqm_adv_y.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_pqm_adv_y.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_pqm_adv_y.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_pqm_adv_y.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_pqm_adv_y.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_pqm_flx_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_pqm_flx_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_pqm_flx_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_pqm_flx_r.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_pqm_flx_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_pqm_flx_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_pqm_flx_r.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_pqm_flx_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_pqm_flx_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_pqm_flx_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_pqm_flx_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_pqm_flx_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_pqm_flx_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_pqm_flx_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_pqm_flx_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_pqm_flx_x.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_pqm_flx_x.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_pqm_flx_x.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_pqm_flx_x.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_pqm_flx_x.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_pqm_flx_x.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_pqm_flx_x.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_pqm_flx_x.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_pqm_flx_x.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_pqm_flx_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_pqm_flx_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_pqm_flx_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_pqm_flx_y.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_pqm_flx_y.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_pqm_flx_y.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_pqm_flx_y.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_pqm_flx_y.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_pqm_flx_y.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_pqm_flx_y.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_pqm_flx_y.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_pqm_flx_y.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_pqm_fun.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_pqm_fun.f: CPP_OPTIONS.h GAD_OPTIONS.h PACKAGES_CONFIG.h
gad_pqm_hat_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_pqm_hat_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_pqm_hat_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_pqm_hat_r.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_pqm_hat_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_pqm_hat_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_pqm_hat_r.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_pqm_hat_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_pqm_hat_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_pqm_hat_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_pqm_hat_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_pqm_hat_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_pqm_hat_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_pqm_hat_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_pqm_hat_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_pqm_hat_x.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_pqm_hat_x.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_pqm_hat_x.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_pqm_hat_x.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_pqm_hat_x.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_pqm_hat_x.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_pqm_hat_x.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_pqm_hat_x.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_pqm_hat_x.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_pqm_hat_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_pqm_hat_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_pqm_hat_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_pqm_hat_y.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_pqm_hat_y.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_pqm_hat_y.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_pqm_hat_y.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_pqm_hat_y.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_pqm_hat_y.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_pqm_hat_y.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_pqm_hat_y.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_pqm_hat_y.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_pqm_p5e_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_pqm_p5e_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_pqm_p5e_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_pqm_p5e_r.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_pqm_p5e_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_pqm_p5e_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_pqm_p5e_r.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_pqm_p5e_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_pqm_p5e_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_pqm_p5e_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_pqm_p5e_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_pqm_p5e_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_pqm_p5e_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_pqm_p5e_x.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_pqm_p5e_x.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_pqm_p5e_x.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_pqm_p5e_x.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_pqm_p5e_x.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_pqm_p5e_x.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_pqm_p5e_x.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_pqm_p5e_x.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_pqm_p5e_x.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_pqm_p5e_x.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_pqm_p5e_x.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_pqm_p5e_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_pqm_p5e_y.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_pqm_p5e_y.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_pqm_p5e_y.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_pqm_p5e_y.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_pqm_p5e_y.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_pqm_p5e_y.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gad_pqm_p5e_y.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gad_pqm_p5e_y.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gad_pqm_p5e_y.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_pqm_p5e_y.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_pqm_p5e_y.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_read_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_read_pickup.f: CPP_OPTIONS.h EEPARAMS.h GAD.h GAD_OPTIONS.h GAD_SOM_VARS.h
gad_read_pickup.f: MNC_PARAMS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
gad_som_adv_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_som_adv_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_som_adv_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_som_adv_r.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h
gad_som_adv_r.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
gad_som_adv_r.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
gad_som_adv_r.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
gad_som_adv_r.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_som_adv_r.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_som_adv_r.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_som_adv_r.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_som_adv_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_som_adv_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_som_adv_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_som_adv_x.f: CPP_OPTIONS.h EEPARAMS.h GAD.h GAD_OPTIONS.h
gad_som_adv_x.f: PACKAGES_CONFIG.h SIZE.h
gad_som_adv_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_som_adv_y.f: CPP_OPTIONS.h EEPARAMS.h GAD.h GAD_OPTIONS.h
gad_som_adv_y.f: PACKAGES_CONFIG.h SIZE.h
gad_som_advect.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_som_advect.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_som_advect.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_som_advect.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h
gad_som_advect.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
gad_som_advect.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
gad_som_advect.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
gad_som_advect.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_som_advect.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_som_advect.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_som_advect.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_som_advect.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_som_advect.f: TANPHIATV_MACROS.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
gad_som_advect.f: XC_MACROS.h YC_MACROS.h
gad_som_exchanges.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_som_exchanges.f: CPP_OPTIONS.h EEPARAMS.h GAD.h GAD_OPTIONS.h
gad_som_exchanges.f: GAD_SOM_VARS.h PACKAGES_CONFIG.h SIZE.h
gad_som_fill_cs_corner.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gad_som_fill_cs_corner.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h GAD.h
gad_som_fill_cs_corner.f: GAD_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
gad_som_lim_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_som_lim_r.f: CPP_OPTIONS.h GAD.h GAD_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
gad_som_prep_cs_corner.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gad_som_prep_cs_corner.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h GAD.h
gad_som_prep_cs_corner.f: GAD_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
gad_u3_adv_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_u3_adv_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_u3_adv_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_u3_adv_r.f: DYU_MACROS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h GRID.h
gad_u3_adv_r.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gad_u3_adv_r.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
gad_u3_adv_r.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_u3_adv_r.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_u3_adv_r.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_u3_adv_r.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
gad_u3_adv_r.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gad_u3_adv_r.f: YC_MACROS.h
gad_u3_adv_x.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_u3_adv_x.f: CPP_OPTIONS.h GAD.h GAD_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
gad_u3_adv_y.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_u3_adv_y.f: CPP_OPTIONS.h GAD.h GAD_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
gad_u3c4_impl_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_u3c4_impl_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gad_u3c4_impl_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gad_u3c4_impl_r.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h
gad_u3c4_impl_r.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
gad_u3c4_impl_r.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
gad_u3c4_impl_r.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
gad_u3c4_impl_r.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gad_u3c4_impl_r.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gad_u3c4_impl_r.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gad_u3c4_impl_r.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gad_u3c4_impl_r.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gad_u3c4_impl_r.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gad_write_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gad_write_pickup.f: CPP_OPTIONS.h EEPARAMS.h GAD.h GAD_OPTIONS.h
gad_write_pickup.f: GAD_SOM_VARS.h MNC_PARAMS.h PACKAGES_CONFIG.h PARAMS.h
gad_write_pickup.f: SIZE.h
gather_2d_r4.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
gather_2d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gather_2d_r4.f: EEPARAMS.h EESUPPORT.h PACKAGES_CONFIG.h SIZE.h
gather_2d_r4.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
gather_2d_r8.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
gather_2d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gather_2d_r8.f: EEPARAMS.h EESUPPORT.h PACKAGES_CONFIG.h SIZE.h
gather_2d_r8.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
gather_2d_wh_r4.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
gather_2d_wh_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gather_2d_wh_r4.f: EEPARAMS.h EESUPPORT.h PACKAGES_CONFIG.h SIZE.h
gather_2d_wh_r8.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
gather_2d_wh_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gather_2d_wh_r8.f: EEPARAMS.h EESUPPORT.h PACKAGES_CONFIG.h SIZE.h
gather_vec_r4.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
gather_vec_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gather_vec_r4.f: EEPARAMS.h EESUPPORT.h SIZE.h
gather_vec_r8.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
gather_vec_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gather_vec_r8.f: EEPARAMS.h EESUPPORT.h SIZE.h
gather_xz.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
gather_xz.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gather_xz.f: CPP_OPTIONS.h EEPARAMS.h EESUPPORT.h SIZE.h
gather_yz.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
gather_yz.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gather_yz.f: CPP_OPTIONS.h EEPARAMS.h EESUPPORT.h SIZE.h
get_periodic_interval.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
get_periodic_interval.f: CPP_EEOPTIONS.h EEPARAMS.h
get_write_global_fld.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
get_write_global_fld.f: CPP_EEOPTIONS.h
global_max.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
global_max.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
global_max.f: EEPARAMS.h EESUPPORT.h GLOBAL_MAX.h SIZE.h
global_sum.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
global_sum.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
global_sum.f: EEPARAMS.h EESUPPORT.h GLOBAL_SUM.h SIZE.h
global_sum_singlecpu.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
global_sum_singlecpu.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
global_sum_singlecpu.f: CPP_EEOPTIONS.h EEBUFF_SCPU.h EEPARAMS.h EESUPPORT.h
global_sum_singlecpu.f: GLOBAL_SUM.h PACKAGES_CONFIG.h SIZE.h W2_EXCH2_SIZE.h
global_sum_singlecpu.f: W2_EXCH2_TOPOLOGY.h
global_sum_tile.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
global_sum_tile.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
global_sum_tile.f: EEPARAMS.h EESUPPORT.h GLOBAL_SUM.h SIZE.h
global_vec_sum.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
global_vec_sum.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
global_vec_sum.f: EEPARAMS.h EESUPPORT.h SIZE.h
gmredi_calc_diff.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_calc_diff.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gmredi_calc_diff.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gmredi_calc_diff.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h GMREDI.h
gmredi_calc_diff.f: GMREDI_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
gmredi_calc_diff.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gmredi_calc_diff.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
gmredi_calc_diff.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gmredi_calc_diff.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gmredi_calc_diff.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gmredi_calc_diff.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gmredi_calc_diff.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gmredi_calc_diff.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gmredi_calc_diff.f: YC_MACROS.h
gmredi_calc_eigs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_calc_eigs.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gmredi_calc_eigs.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gmredi_calc_eigs.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GMREDI.h
gmredi_calc_eigs.f: GMREDI_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
gmredi_calc_eigs.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gmredi_calc_eigs.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
gmredi_calc_eigs.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gmredi_calc_eigs.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gmredi_calc_eigs.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gmredi_calc_eigs.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gmredi_calc_eigs.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gmredi_calc_eigs.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gmredi_calc_eigs.f: YC_MACROS.h
gmredi_calc_psi_b.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_calc_psi_b.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gmredi_calc_psi_b.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gmredi_calc_psi_b.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
gmredi_calc_psi_b.f: FFIELDS.h GMREDI.h GMREDI_OPTIONS.h GRID.h GRID_MACROS.h
gmredi_calc_psi_b.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gmredi_calc_psi_b.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
gmredi_calc_psi_b.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gmredi_calc_psi_b.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gmredi_calc_psi_b.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gmredi_calc_psi_b.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gmredi_calc_psi_b.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gmredi_calc_psi_b.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gmredi_calc_psi_b.f: YC_MACROS.h
gmredi_calc_psi_bvp.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gmredi_calc_psi_bvp.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
gmredi_calc_psi_bvp.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
gmredi_calc_psi_bvp.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
gmredi_calc_psi_bvp.f: GMREDI.h GMREDI_OPTIONS.h GRID.h GRID_MACROS.h
gmredi_calc_psi_bvp.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gmredi_calc_psi_bvp.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
gmredi_calc_psi_bvp.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
gmredi_calc_psi_bvp.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gmredi_calc_psi_bvp.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gmredi_calc_psi_bvp.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
gmredi_calc_psi_bvp.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gmredi_calc_psi_bvp.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gmredi_calc_psi_bvp.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gmredi_calc_psi_bvp.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gmredi_calc_qgleith.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gmredi_calc_qgleith.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
gmredi_calc_qgleith.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
gmredi_calc_qgleith.f: DYG_MACROS.h DYNVARS.h DYU_MACROS.h EEPARAMS.h
gmredi_calc_qgleith.f: FCORI_MACROS.h GMREDI_OPTIONS.h GRID.h GRID_MACROS.h
gmredi_calc_qgleith.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gmredi_calc_qgleith.f: MASKS_MACROS.h MASKW_MACROS.h MOM_VISC.h
gmredi_calc_qgleith.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
gmredi_calc_qgleith.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gmredi_calc_qgleith.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gmredi_calc_qgleith.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
gmredi_calc_qgleith.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gmredi_calc_qgleith.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gmredi_calc_qgleith.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gmredi_calc_qgleith.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gmredi_calc_tensor.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gmredi_calc_tensor.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
gmredi_calc_tensor.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
gmredi_calc_tensor.f: DYG_MACROS.h DYNVARS.h DYU_MACROS.h EEPARAMS.h
gmredi_calc_tensor.f: FCORI_MACROS.h GMREDI.h GMREDI_OPTIONS.h GMREDI_TAVE.h
gmredi_calc_tensor.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
gmredi_calc_tensor.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
gmredi_calc_tensor.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
gmredi_calc_tensor.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gmredi_calc_tensor.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gmredi_calc_tensor.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gmredi_calc_tensor.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gmredi_calc_tensor.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gmredi_calc_tensor.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gmredi_calc_urms.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_calc_urms.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gmredi_calc_urms.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gmredi_calc_urms.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GMREDI.h
gmredi_calc_urms.f: GMREDI_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
gmredi_calc_urms.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gmredi_calc_urms.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
gmredi_calc_urms.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gmredi_calc_urms.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gmredi_calc_urms.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gmredi_calc_urms.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gmredi_calc_urms.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gmredi_calc_urms.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gmredi_calc_urms.f: YC_MACROS.h
gmredi_check.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_check.f: CPP_OPTIONS.h EEPARAMS.h GAD.h GMREDI.h GMREDI_OPTIONS.h
gmredi_check.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
gmredi_diagnostics_fill.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gmredi_diagnostics_fill.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
gmredi_diagnostics_fill.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
gmredi_diagnostics_fill.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
gmredi_diagnostics_fill.f: FCORI_MACROS.h GMREDI.h GMREDI_OPTIONS.h GRID.h
gmredi_diagnostics_fill.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
gmredi_diagnostics_fill.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
gmredi_diagnostics_fill.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
gmredi_diagnostics_fill.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gmredi_diagnostics_fill.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
gmredi_diagnostics_fill.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gmredi_diagnostics_fill.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gmredi_diagnostics_fill.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gmredi_diagnostics_fill.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gmredi_diagnostics_fill.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gmredi_diagnostics_fill.f: YC_MACROS.h
gmredi_diagnostics_impl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gmredi_diagnostics_impl.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
gmredi_diagnostics_impl.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
gmredi_diagnostics_impl.f: DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
gmredi_diagnostics_impl.f: EEPARAMS.h FCORI_MACROS.h GMREDI.h GMREDI_OPTIONS.h
gmredi_diagnostics_impl.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
gmredi_diagnostics_impl.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
gmredi_diagnostics_impl.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
gmredi_diagnostics_impl.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gmredi_diagnostics_impl.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
gmredi_diagnostics_impl.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
gmredi_diagnostics_impl.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gmredi_diagnostics_impl.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gmredi_diagnostics_impl.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gmredi_diagnostics_impl.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gmredi_diagnostics_impl.f: YC_MACROS.h
gmredi_diagnostics_init.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gmredi_diagnostics_init.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
gmredi_diagnostics_init.f: GMREDI_OPTIONS.h PACKAGES_CONFIG.h
gmredi_do_exch.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_do_exch.f: CPP_OPTIONS.h EEPARAMS.h GMREDI.h GMREDI_OPTIONS.h
gmredi_do_exch.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
gmredi_init_fixed.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_init_fixed.f: CPP_OPTIONS.h EEPARAMS.h GMREDI.h GMREDI_OPTIONS.h
gmredi_init_fixed.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
gmredi_init_varia.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_init_varia.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gmredi_init_varia.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gmredi_init_varia.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GMREDI.h
gmredi_init_varia.f: GMREDI_OPTIONS.h GMREDI_TAVE.h GRID.h GRID_MACROS.h
gmredi_init_varia.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gmredi_init_varia.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
gmredi_init_varia.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gmredi_init_varia.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gmredi_init_varia.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gmredi_init_varia.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gmredi_init_varia.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gmredi_init_varia.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gmredi_init_varia.f: YC_MACROS.h
gmredi_k3d.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_k3d.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gmredi_k3d.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
gmredi_k3d.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h FFIELDS.h GMREDI.h
gmredi_k3d.f: GMREDI_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
gmredi_k3d.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
gmredi_k3d.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
gmredi_k3d.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
gmredi_k3d.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
gmredi_k3d.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gmredi_k3d.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gmredi_k3d.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gmredi_mnc_init.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_mnc_init.f: CPP_OPTIONS.h EEPARAMS.h GMREDI.h GMREDI_OPTIONS.h
gmredi_mnc_init.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
gmredi_output.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_output.f: CPP_OPTIONS.h EEPARAMS.h GMREDI.h GMREDI_OPTIONS.h
gmredi_output.f: GMREDI_TAVE.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
gmredi_read_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gmredi_read_pickup.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h GMREDI.h
gmredi_read_pickup.f: GMREDI_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
gmredi_readparms.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_readparms.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gmredi_readparms.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gmredi_readparms.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GMREDI.h
gmredi_readparms.f: GMREDI_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
gmredi_readparms.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gmredi_readparms.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
gmredi_readparms.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gmredi_readparms.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gmredi_readparms.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gmredi_readparms.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gmredi_readparms.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gmredi_readparms.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gmredi_readparms.f: YC_MACROS.h
gmredi_residual_flow.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gmredi_residual_flow.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
gmredi_residual_flow.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
gmredi_residual_flow.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
gmredi_residual_flow.f: FCORI_MACROS.h GMREDI.h GMREDI_OPTIONS.h GRID.h
gmredi_residual_flow.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
gmredi_residual_flow.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
gmredi_residual_flow.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
gmredi_residual_flow.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
gmredi_residual_flow.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gmredi_residual_flow.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
gmredi_residual_flow.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
gmredi_residual_flow.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
gmredi_residual_flow.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
gmredi_residual_flow.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gmredi_rtransport.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_rtransport.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gmredi_rtransport.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gmredi_rtransport.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h GMREDI.h
gmredi_rtransport.f: GMREDI_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
gmredi_rtransport.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gmredi_rtransport.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
gmredi_rtransport.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gmredi_rtransport.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gmredi_rtransport.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gmredi_rtransport.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gmredi_rtransport.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gmredi_rtransport.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gmredi_rtransport.f: YC_MACROS.h
gmredi_slope_limit.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gmredi_slope_limit.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
gmredi_slope_limit.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
gmredi_slope_limit.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
gmredi_slope_limit.f: GMREDI.h GMREDI_OPTIONS.h GRID.h GRID_MACROS.h
gmredi_slope_limit.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
gmredi_slope_limit.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
gmredi_slope_limit.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gmredi_slope_limit.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gmredi_slope_limit.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gmredi_slope_limit.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gmredi_slope_limit.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gmredi_slope_limit.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gmredi_slope_limit.f: YC_MACROS.h
gmredi_slope_psi.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_slope_psi.f: CPP_OPTIONS.h EEPARAMS.h GMREDI.h GMREDI_OPTIONS.h
gmredi_slope_psi.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
gmredi_write_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
gmredi_write_pickup.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h GMREDI.h
gmredi_write_pickup.f: GMREDI_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
gmredi_xtransport.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_xtransport.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gmredi_xtransport.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gmredi_xtransport.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GMREDI.h
gmredi_xtransport.f: GMREDI_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
gmredi_xtransport.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gmredi_xtransport.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
gmredi_xtransport.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gmredi_xtransport.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gmredi_xtransport.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gmredi_xtransport.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gmredi_xtransport.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gmredi_xtransport.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gmredi_xtransport.f: YC_MACROS.h
gmredi_ytransport.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gmredi_ytransport.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
gmredi_ytransport.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
gmredi_ytransport.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GMREDI.h
gmredi_ytransport.f: GMREDI_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
gmredi_ytransport.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
gmredi_ytransport.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
gmredi_ytransport.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
gmredi_ytransport.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
gmredi_ytransport.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
gmredi_ytransport.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
gmredi_ytransport.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
gmredi_ytransport.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
gmredi_ytransport.f: YC_MACROS.h
grad_sigma.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
grad_sigma.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
grad_sigma.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h
grad_sigma.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
grad_sigma.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
grad_sigma.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
grad_sigma.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
grad_sigma.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
grad_sigma.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
grad_sigma.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
grad_sigma.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
gsum.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h /usr/include/stdc-predef.h
gsum.f: CPP_EEMACROS.h CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h SIZE.h
gsw_teos10.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
gsw_teos10.f: CPP_OPTIONS.h
impldiff.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
impldiff.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
impldiff.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
impldiff.f: EEPARAMS.h FCORI_MACROS.h GAD.h GRID.h GRID_MACROS.h
impldiff.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
impldiff.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
impldiff.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
impldiff.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
impldiff.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
impldiff.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
impldiff.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
impldiff.f: YC_MACROS.h
ini_cartesian_grid.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
ini_cartesian_grid.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
ini_cartesian_grid.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
ini_cartesian_grid.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
ini_cartesian_grid.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
ini_cartesian_grid.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PARAMS.h
ini_cartesian_grid.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
ini_cartesian_grid.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
ini_cartesian_grid.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
ini_cartesian_grid.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
ini_cartesian_grid.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
ini_cartesian_grid.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
ini_cartesian_grid.f: YC_MACROS.h
ini_cg2d.f: /usr/include/stdc-predef.h CG2D.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_cg2d.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
ini_cg2d.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
ini_cg2d.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
ini_cg2d.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
ini_cg2d.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
ini_cg2d.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
ini_cg2d.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
ini_cg2d.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
ini_cg2d.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
ini_cg2d.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
ini_cg3d.f: /usr/include/stdc-predef.h CG3D.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_cg3d.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
ini_cg3d.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
ini_cg3d.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
ini_cg3d.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
ini_cg3d.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
ini_cg3d.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
ini_cg3d.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
ini_cg3d.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
ini_cg3d.f: RECIP_HFACW_MACROS.h SIZE.h SOLVE_FOR_PRESSURE3D.h SURFACE.h
ini_cg3d.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
ini_communication_patterns.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
ini_communication_patterns.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
ini_communication_patterns.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h EXCH.h
ini_communication_patterns.f: PACKAGES_CONFIG.h SIZE.h
ini_cori.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_cori.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
ini_cori.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
ini_cori.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
ini_cori.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h MNC_PARAMS.h
ini_cori.f: MONITOR.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
ini_cori.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
ini_cori.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
ini_cori.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
ini_cori.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
ini_cori.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h W2_EXCH2_SIZE.h
ini_cori.f: W2_EXCH2_TOPOLOGY.h XC_MACROS.h YC_MACROS.h
ini_curvilinear_grid.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
ini_curvilinear_grid.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
ini_curvilinear_grid.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
ini_curvilinear_grid.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
ini_curvilinear_grid.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
ini_curvilinear_grid.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
ini_curvilinear_grid.f: MASKW_MACROS.h MNC_PARAMS.h PACKAGES_CONFIG.h PARAMS.h
ini_curvilinear_grid.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
ini_curvilinear_grid.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
ini_curvilinear_grid.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
ini_curvilinear_grid.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
ini_curvilinear_grid.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
ini_curvilinear_grid.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
ini_curvilinear_grid.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
ini_curvilinear_grid.f: TANPHIATV_MACROS.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
ini_curvilinear_grid.f: XC_MACROS.h YC_MACROS.h
ini_cylinder_grid.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_cylinder_grid.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
ini_cylinder_grid.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
ini_cylinder_grid.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
ini_cylinder_grid.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
ini_cylinder_grid.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PARAMS.h
ini_cylinder_grid.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
ini_cylinder_grid.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
ini_cylinder_grid.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
ini_cylinder_grid.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
ini_cylinder_grid.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
ini_cylinder_grid.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
ini_cylinder_grid.f: YC_MACROS.h
ini_depths.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_depths.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
ini_depths.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h
ini_depths.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
ini_depths.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
ini_depths.f: MNC_PARAMS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
ini_depths.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
ini_depths.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
ini_depths.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
ini_depths.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
ini_depths.f: SIZE.h SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
ini_depths.f: XC_MACROS.h YC_MACROS.h
ini_dynvars.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_dynvars.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
ini_dynvars.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
ini_dynvars.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
ini_dynvars.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
ini_dynvars.f: MASKW_MACROS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
ini_dynvars.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
ini_dynvars.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
ini_dynvars.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
ini_dynvars.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
ini_dynvars.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
ini_eos.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_eos.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
ini_eos.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
ini_eos.f: EEPARAMS.h EOS.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
ini_eos.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
ini_eos.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
ini_eos.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
ini_eos.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
ini_eos.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
ini_eos.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
ini_eos.f: XC_MACROS.h YC_MACROS.h
ini_ffields.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_ffields.f: CPP_OPTIONS.h EEPARAMS.h FFIELDS.h PARAMS.h SIZE.h
ini_fields.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_fields.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
ini_forcing.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_forcing.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
ini_forcing.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
ini_forcing.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h FFIELDS.h GRID.h
ini_forcing.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
ini_forcing.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
ini_forcing.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
ini_forcing.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
ini_forcing.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
ini_forcing.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
ini_forcing.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
ini_forcing.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
ini_global_domain.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_global_domain.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
ini_global_domain.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
ini_global_domain.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
ini_global_domain.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
ini_global_domain.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
ini_global_domain.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
ini_global_domain.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
ini_global_domain.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
ini_global_domain.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
ini_global_domain.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
ini_global_domain.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
ini_global_domain.f: TANPHIATV_MACROS.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
ini_global_domain.f: XC_MACROS.h YC_MACROS.h
ini_grid.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_grid.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
ini_grid.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
ini_grid.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
ini_grid.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h MNC_PARAMS.h
ini_grid.f: MONITOR.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
ini_grid.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
ini_grid.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
ini_grid.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
ini_grid.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
ini_grid.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
ini_grid.f: YC_MACROS.h
ini_linear_phisurf.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
ini_linear_phisurf.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
ini_linear_phisurf.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
ini_linear_phisurf.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
ini_linear_phisurf.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
ini_linear_phisurf.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
ini_linear_phisurf.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
ini_linear_phisurf.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
ini_linear_phisurf.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
ini_linear_phisurf.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
ini_linear_phisurf.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
ini_linear_phisurf.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
ini_linear_phisurf.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
ini_local_grid.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_local_grid.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
ini_local_grid.f: SET_GRID.h SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
ini_local_grid.f: W2_OPTIONS.h
ini_masks_etc.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_masks_etc.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
ini_masks_etc.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
ini_masks_etc.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
ini_masks_etc.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
ini_masks_etc.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
ini_masks_etc.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
ini_masks_etc.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
ini_masks_etc.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
ini_masks_etc.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
ini_masks_etc.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
ini_masks_etc.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
ini_mixing.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_mixing.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
ini_mixing.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
ini_mixing.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GMREDI_OPTIONS.h GRID.h
ini_mixing.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
ini_mixing.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
ini_mixing.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
ini_mixing.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
ini_mixing.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
ini_mixing.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
ini_mixing.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
ini_mixing.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
ini_mnc_vars.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_mnc_vars.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
ini_mnc_vars.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
ini_mnc_vars.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
ini_mnc_vars.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
ini_mnc_vars.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
ini_mnc_vars.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
ini_mnc_vars.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
ini_mnc_vars.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
ini_mnc_vars.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
ini_mnc_vars.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
ini_mnc_vars.f: YC_MACROS.h
ini_model_io.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
ini_model_io.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_model_io.f: CPP_OPTIONS.h EEBUFF_SCPU.h EEPARAMS.h EESUPPORT.h
ini_model_io.f: PACKAGES_CONFIG.h PARAMS.h RESTART.h SIZE.h W2_EXCH2_PARAMS.h
ini_model_io.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
ini_nh_fields.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_nh_fields.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
ini_nh_fields.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
ini_nh_fields.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
ini_nh_fields.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
ini_nh_fields.f: MASKW_MACROS.h NH_VARS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
ini_nh_fields.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
ini_nh_fields.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
ini_nh_fields.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
ini_nh_fields.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
ini_nh_fields.f: RECIP_HFACW_MACROS.h RESTART.h SIZE.h TANPHIATU_MACROS.h
ini_nh_fields.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
ini_nh_vars.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_nh_vars.f: CPP_OPTIONS.h EEPARAMS.h NH_VARS.h PARAMS.h SIZE.h
ini_nlfs_vars.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_nlfs_vars.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
ini_nlfs_vars.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
ini_nlfs_vars.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
ini_nlfs_vars.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
ini_nlfs_vars.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
ini_nlfs_vars.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
ini_nlfs_vars.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
ini_nlfs_vars.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
ini_nlfs_vars.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
ini_nlfs_vars.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
ini_nlfs_vars.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
ini_p_ground.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_p_ground.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
ini_p_ground.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
ini_p_ground.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
ini_p_ground.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
ini_p_ground.f: MASKW_MACROS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
ini_p_ground.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
ini_p_ground.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
ini_p_ground.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
ini_p_ground.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
ini_p_ground.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
ini_parms.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_parms.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
ini_parms.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
ini_parms.f: EOS.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
ini_parms.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
ini_parms.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
ini_parms.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
ini_parms.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
ini_parms.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
ini_parms.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SET_GRID.h SIZE.h
ini_parms.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h W2_EXCH2_SIZE.h
ini_parms.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h XC_MACROS.h YC_MACROS.h
ini_pressure.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_pressure.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
ini_pressure.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
ini_pressure.f: DYU_MACROS.h EEPARAMS.h EOS.h FCORI_MACROS.h GRID.h
ini_pressure.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
ini_pressure.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
ini_pressure.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
ini_pressure.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
ini_pressure.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
ini_pressure.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
ini_pressure.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
ini_pressure.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
ini_procs.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
ini_procs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_procs.f: EEPARAMS.h EESUPPORT.h SIZE.h
ini_psurf.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_psurf.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
ini_psurf.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
ini_psurf.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
ini_psurf.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
ini_psurf.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
ini_psurf.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
ini_psurf.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
ini_psurf.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
ini_psurf.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
ini_psurf.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
ini_salt.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_salt.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
ini_salt.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
ini_salt.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
ini_salt.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
ini_salt.f: MNC_PARAMS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
ini_salt.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
ini_salt.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
ini_salt.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
ini_salt.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
ini_salt.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
ini_salt.f: YC_MACROS.h
ini_sigma_hfac.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_sigma_hfac.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
ini_sigma_hfac.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
ini_sigma_hfac.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
ini_sigma_hfac.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
ini_sigma_hfac.f: MASKW_MACROS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
ini_sigma_hfac.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
ini_sigma_hfac.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
ini_sigma_hfac.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
ini_sigma_hfac.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
ini_sigma_hfac.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
ini_sigma_hfac.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
ini_spherical_polar_grid.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
ini_spherical_polar_grid.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
ini_spherical_polar_grid.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
ini_spherical_polar_grid.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
ini_spherical_polar_grid.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
ini_spherical_polar_grid.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
ini_spherical_polar_grid.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
ini_spherical_polar_grid.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
ini_spherical_polar_grid.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
ini_spherical_polar_grid.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
ini_spherical_polar_grid.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
ini_spherical_polar_grid.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
ini_spherical_polar_grid.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
ini_spherical_polar_grid.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
ini_spherical_polar_grid.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
ini_theta.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_theta.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
ini_theta.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
ini_theta.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
ini_theta.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
ini_theta.f: MNC_PARAMS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
ini_theta.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
ini_theta.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
ini_theta.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
ini_theta.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
ini_theta.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
ini_theta.f: YC_MACROS.h
ini_threading_environment.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
ini_threading_environment.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
ini_threading_environment.f: CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h
ini_threading_environment.f: PACKAGES_CONFIG.h SIZE.h
ini_vel.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_vel.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
ini_vel.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
ini_vel.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
ini_vel.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
ini_vel.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
ini_vel.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
ini_vel.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
ini_vel.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
ini_vel.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
ini_vel.f: XC_MACROS.h YC_MACROS.h
ini_vertical_grid.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ini_vertical_grid.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
ini_vertical_grid.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
ini_vertical_grid.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
ini_vertical_grid.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
ini_vertical_grid.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PARAMS.h
ini_vertical_grid.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
ini_vertical_grid.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
ini_vertical_grid.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
ini_vertical_grid.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
ini_vertical_grid.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
ini_vertical_grid.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
ini_vertical_grid.f: YC_MACROS.h
initialise_fixed.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
initialise_fixed.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
initialise_varia.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
initialise_varia.f: CPP_OPTIONS.h DYNVARS.h EEPARAMS.h PACKAGES_CONFIG.h
initialise_varia.f: PARAMS.h SIZE.h SURFACE.h
integr_continuity.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
integr_continuity.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
integr_continuity.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
integr_continuity.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
integr_continuity.f: FFIELDS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
integr_continuity.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
integr_continuity.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
integr_continuity.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
integr_continuity.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
integr_continuity.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
integr_continuity.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
integr_continuity.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
integr_continuity.f: SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
integr_continuity.f: XC_MACROS.h YC_MACROS.h
integrate_for_w.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
integrate_for_w.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
integrate_for_w.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
integrate_for_w.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
integrate_for_w.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
integrate_for_w.f: MASKW_MACROS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
integrate_for_w.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
integrate_for_w.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
integrate_for_w.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
integrate_for_w.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
integrate_for_w.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
integrate_for_w.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
lef_zero.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
lef_zero.f: EEPARAMS.h SIZE.h
load_fields_driver.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
load_fields_driver.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h EXF_OPTIONS.h
load_fields_driver.f: FFIELDS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
load_grid_spacing.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
load_grid_spacing.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
load_grid_spacing.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
load_grid_spacing.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
load_grid_spacing.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
load_grid_spacing.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
load_grid_spacing.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
load_grid_spacing.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
load_grid_spacing.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
load_grid_spacing.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
load_grid_spacing.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
load_grid_spacing.f: RECIP_HFACW_MACROS.h SET_GRID.h SIZE.h TANPHIATU_MACROS.h
load_grid_spacing.f: TANPHIATV_MACROS.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
load_grid_spacing.f: W2_OPTIONS.h XC_MACROS.h YC_MACROS.h
load_ref_files.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
load_ref_files.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
load_ref_files.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
load_ref_files.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
load_ref_files.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
load_ref_files.f: MASKW_MACROS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
load_ref_files.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
load_ref_files.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
load_ref_files.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
load_ref_files.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
load_ref_files.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
load_ref_files.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
lsr.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h CPP_OPTIONS.h
lsr.f: DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
lsr.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
lsr.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
lsr.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
lsr.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
lsr.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
lsr.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
lsr.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SEAICE.h
lsr.f: SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
lsr.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
main.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h /usr/include/stdc-predef.h
main.f: CPP_EEMACROS.h CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
main.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
main.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h EESUPPORT.h FCORI_MACROS.h FFIELDS.h
main.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
main.f: MAIN_PDIRECTIVES1.h MAIN_PDIRECTIVES2.h MASKS_MACROS.h MASKW_MACROS.h
main.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
main.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
main.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
main.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
main.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIGREG.h SIZE.h SURFACE.h
main.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
main_do_loop.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
main_do_loop.f: CPP_OPTIONS.h EEPARAMS.h EXF_OPTIONS.h GAD_OPTIONS.h
main_do_loop.f: GMREDI_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h SEAICE_OPTIONS.h
main_do_loop.f: SIZE.h
master_cpu_io.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
master_cpu_io.f: EEPARAMS.h SIZE.h
master_cpu_thread.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
master_cpu_thread.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
master_cpu_thread.f: EEPARAMS.h EESUPPORT.h SIZE.h
mds_byteswapi4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mds_byteswapr4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mds_byteswapr8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mds_flush.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mds_flush.f: EEPARAMS.h
mds_reclen.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mds_reclen.f: EEPARAMS.h SIZE.h
mdsfindunit.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsfindunit.f: EEPARAMS.h
mdsio_buffertorl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_buffertors.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_check4file.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_check4file.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h
mdsio_check4file.f: PARAMS.h SIZE.h
mdsio_facef_read.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_facef_read.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h
mdsio_facef_read.f: SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
mdsio_gl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_gl.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h
mdsio_gl.f: PARAMS.h SIZE.h
mdsio_gl_slice.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_gl_slice.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h
mdsio_gl_slice.f: PARAMS.h SIZE.h
mdsio_pass_r4torl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_pass_r4torl.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h
mdsio_pass_r4torl.f: PACKAGES_CONFIG.h SIZE.h
mdsio_pass_r4tors.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_pass_r4tors.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h
mdsio_pass_r4tors.f: PACKAGES_CONFIG.h SIZE.h
mdsio_pass_r8torl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_pass_r8torl.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h
mdsio_pass_r8torl.f: PACKAGES_CONFIG.h SIZE.h
mdsio_pass_r8tors.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_pass_r8tors.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h
mdsio_pass_r8tors.f: PACKAGES_CONFIG.h SIZE.h
mdsio_rd_rec_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_rd_rec_rl.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h
mdsio_rd_rec_rl.f: PARAMS.h SIZE.h
mdsio_rd_rec_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_rd_rec_rs.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h
mdsio_rd_rec_rs.f: PARAMS.h SIZE.h
mdsio_read_field.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_read_field.f: CPP_OPTIONS.h EEBUFF_SCPU.h EEPARAMS.h MDSIO_BUFF_3D.h
mdsio_read_field.f: MDSIO_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
mdsio_read_field.f: W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
mdsio_read_meta.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_read_meta.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h
mdsio_read_meta.f: PARAMS.h SIZE.h
mdsio_read_section.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mdsio_read_section.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h
mdsio_read_section.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h W2_EXCH2_PARAMS.h
mdsio_read_section.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
mdsio_read_tape.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_read_tape.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h
mdsio_read_tape.f: PARAMS.h SIZE.h
mdsio_read_whalos.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_read_whalos.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h
mdsio_read_whalos.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
mdsio_readvec_loc.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_readvec_loc.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_BUFF_3D.h MDSIO_OPTIONS.h
mdsio_readvec_loc.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
mdsio_rw_field.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_rw_field.f: CPP_OPTIONS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
mdsio_rw_slice.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_rw_slice.f: CPP_OPTIONS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
mdsio_seg4torl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_seg4torl.f: CPP_OPTIONS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
mdsio_seg4tors.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_seg4tors.f: CPP_OPTIONS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
mdsio_seg8torl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_seg8torl.f: CPP_OPTIONS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
mdsio_seg8tors.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_seg8tors.f: CPP_OPTIONS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
mdsio_segxtorx_2d.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_segxtorx_2d.f: CPP_OPTIONS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
mdsio_wr_metafiles.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mdsio_wr_metafiles.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h
mdsio_wr_metafiles.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h W2_EXCH2_PARAMS.h
mdsio_wr_metafiles.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
mdsio_wr_rec_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_wr_rec_rl.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h
mdsio_wr_rec_rl.f: PARAMS.h SIZE.h
mdsio_wr_rec_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_wr_rec_rs.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h
mdsio_wr_rec_rs.f: PARAMS.h SIZE.h
mdsio_write_field.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_write_field.f: CPP_OPTIONS.h EEBUFF_SCPU.h EEPARAMS.h MDSIO_BUFF_3D.h
mdsio_write_field.f: MDSIO_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
mdsio_write_field.f: W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
mdsio_write_meta.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_write_meta.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h
mdsio_write_meta.f: SIZE.h
mdsio_write_section.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mdsio_write_section.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
mdsio_write_section.f: MDSIO_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
mdsio_write_section.f: W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
mdsio_write_tape.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_write_tape.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h PACKAGES_CONFIG.h
mdsio_write_tape.f: PARAMS.h SIZE.h
mdsio_write_whalos.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mdsio_write_whalos.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h MDSIO_OPTIONS.h
mdsio_write_whalos.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
mdsio_writelocal.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mdsio_writelocal.f: CPP_OPTIONS.h EEPARAMS.h MDSIO_BUFF_3D.h MDSIO_OPTIONS.h
mdsio_writelocal.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h W2_EXCH2_PARAMS.h
mdsio_writelocal.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
mdsio_writevec_loc.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mdsio_writevec_loc.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h MDSIO_BUFF_3D.h
mdsio_writevec_loc.f: MDSIO_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
memsync.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mnc_cw_citer.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mnc_cw_citer.f: CPP_OPTIONS.h EEPARAMS.h MNC_COMMON.h MNC_ID_HEADER.h
mnc_cw_citer.f: MNC_OPTIONS.h MNC_SIZE.h PACKAGES_CONFIG.h
mnc_cw_cvars.f: /nasa/netcdf/4.4.1.1_mpt/include/netcdf.inc
mnc_cw_cvars.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mnc_cw_cvars.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mnc_cw_cvars.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mnc_cw_cvars.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mnc_cw_cvars.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mnc_cw_cvars.f: MASKW_MACROS.h MNC_COMMON.h MNC_ID_HEADER.h MNC_OPTIONS.h
mnc_cw_cvars.f: MNC_SIZE.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
mnc_cw_cvars.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mnc_cw_cvars.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
mnc_cw_cvars.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mnc_cw_cvars.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
mnc_cw_cvars.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h W2_EXCH2_SIZE.h
mnc_cw_cvars.f: W2_EXCH2_TOPOLOGY.h XC_MACROS.h YC_MACROS.h
mnc_cw_init.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mnc_cw_init.f: CPP_OPTIONS.h EEPARAMS.h MNC_COMMON.h MNC_ID_HEADER.h
mnc_cw_init.f: MNC_OPTIONS.h MNC_SIZE.h PACKAGES_CONFIG.h
mnc_cw_missingvals.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mnc_cw_missingvals.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h MNC_COMMON.h
mnc_cw_missingvals.f: MNC_ID_HEADER.h MNC_OPTIONS.h MNC_SIZE.h
mnc_cw_missingvals.f: PACKAGES_CONFIG.h
mnc_cw_model_attr.f: /usr/include/stdc-predef.h BUILD_INFO.h CPP_EEMACROS.h
mnc_cw_model_attr.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h MNC_ID_HEADER.h
mnc_cw_model_attr.f: MNC_OPTIONS.h MNC_PARAMS.h PACKAGES_CONFIG.h PARAMS.h
mnc_cw_model_attr.f: SIZE.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
mnc_cw_udim.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mnc_cw_udim.f: CPP_OPTIONS.h EEPARAMS.h MNC_COMMON.h MNC_ID_HEADER.h
mnc_cw_udim.f: MNC_OPTIONS.h MNC_SIZE.h PACKAGES_CONFIG.h
mnc_cw_write_grid_info.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mnc_cw_write_grid_info.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
mnc_cw_write_grid_info.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
mnc_cw_write_grid_info.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
mnc_cw_write_grid_info.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
mnc_cw_write_grid_info.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mnc_cw_write_grid_info.f: MASKW_MACROS.h MNC_COMMON.h MNC_ID_HEADER.h
mnc_cw_write_grid_info.f: MNC_OPTIONS.h MNC_SIZE.h PACKAGES_CONFIG.h PARAMS.h
mnc_cw_write_grid_info.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mnc_cw_write_grid_info.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mnc_cw_write_grid_info.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mnc_cw_write_grid_info.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mnc_cw_write_grid_info.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mnc_cw_write_grid_info.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mnc_cw_write_grid_info.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mnc_cw_write_grid_info.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mnc_cwrapper.f: /nasa/netcdf/4.4.1.1_mpt/include/netcdf.inc
mnc_cwrapper.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mnc_cwrapper.f: CPP_OPTIONS.h EEPARAMS.h MNC_COMMON.h MNC_ID_HEADER.h
mnc_cwrapper.f: MNC_OPTIONS.h MNC_SIZE.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
mnc_cwrapper.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
mnc_dim.f: /nasa/netcdf/4.4.1.1_mpt/include/netcdf.inc
mnc_dim.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mnc_dim.f: CPP_OPTIONS.h EEPARAMS.h MNC_COMMON.h MNC_ID_HEADER.h MNC_OPTIONS.h
mnc_dim.f: MNC_SIZE.h PACKAGES_CONFIG.h
mnc_dump.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mnc_dump.f: CPP_OPTIONS.h MNC_COMMON.h MNC_ID_HEADER.h MNC_OPTIONS.h
mnc_dump.f: MNC_SIZE.h PACKAGES_CONFIG.h
mnc_file.f: /nasa/netcdf/4.4.1.1_mpt/include/netcdf.inc
mnc_file.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mnc_file.f: CPP_OPTIONS.h EEPARAMS.h MNC_COMMON.h MNC_ID_HEADER.h
mnc_file.f: MNC_OPTIONS.h MNC_SIZE.h PACKAGES_CONFIG.h
mnc_grid.f: /nasa/netcdf/4.4.1.1_mpt/include/netcdf.inc
mnc_grid.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mnc_grid.f: CPP_OPTIONS.h EEPARAMS.h MNC_COMMON.h MNC_ID_HEADER.h
mnc_grid.f: MNC_OPTIONS.h MNC_SIZE.h PACKAGES_CONFIG.h
mnc_init.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mnc_init.f: CPP_OPTIONS.h EEPARAMS.h MNC_COMMON.h MNC_ID_HEADER.h
mnc_init.f: MNC_OPTIONS.h MNC_PARAMS.h MNC_SIZE.h PACKAGES_CONFIG.h PARAMS.h
mnc_init.f: SIZE.h
mnc_readparms.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mnc_readparms.f: CPP_OPTIONS.h EEPARAMS.h MNC_COMMON.h MNC_ID_HEADER.h
mnc_readparms.f: MNC_OPTIONS.h MNC_PARAMS.h MNC_SIZE.h PACKAGES_CONFIG.h
mnc_readparms.f: PARAMS.h SIZE.h
mnc_update_time.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mnc_update_time.f: CPP_OPTIONS.h EEPARAMS.h MNC_ID_HEADER.h MNC_OPTIONS.h
mnc_update_time.f: MNC_PARAMS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
mnc_utils.f: /nasa/netcdf/4.4.1.1_mpt/include/netcdf.inc
mnc_utils.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mnc_utils.f: CPP_OPTIONS.h EEPARAMS.h MNC_COMMON.h MNC_ID_HEADER.h
mnc_utils.f: MNC_OPTIONS.h MNC_SIZE.h PACKAGES_CONFIG.h
mnc_var.f: /nasa/netcdf/4.4.1.1_mpt/include/netcdf.inc
mnc_var.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mnc_var.f: CPP_OPTIONS.h EEPARAMS.h MNC_COMMON.h MNC_ID_HEADER.h MNC_OPTIONS.h
mnc_var.f: MNC_SIZE.h PACKAGES_CONFIG.h
mom_calc_3d_strain.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mom_calc_3d_strain.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
mom_calc_3d_strain.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
mom_calc_3d_strain.f: DYG_MACROS.h DYNVARS.h DYU_MACROS.h EEPARAMS.h
mom_calc_3d_strain.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
mom_calc_3d_strain.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_calc_3d_strain.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h
mom_calc_3d_strain.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_calc_3d_strain.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_calc_3d_strain.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_calc_3d_strain.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_calc_3d_strain.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_calc_3d_strain.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_calc_3d_strain.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_calc_absvort3.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_calc_absvort3.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_calc_absvort3.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_calc_absvort3.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
mom_calc_absvort3.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_calc_absvort3.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_calc_absvort3.f: MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_calc_absvort3.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_calc_absvort3.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_calc_absvort3.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_calc_absvort3.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_calc_absvort3.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_calc_absvort3.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_calc_absvort3.f: YC_MACROS.h
mom_calc_hdiv.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_calc_hdiv.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_calc_hdiv.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_calc_hdiv.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_calc_hdiv.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_calc_hdiv.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h
mom_calc_hdiv.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_calc_hdiv.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_calc_hdiv.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_calc_hdiv.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_calc_hdiv.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_calc_hdiv.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_calc_hfacz.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_calc_hfacz.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_calc_hfacz.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_calc_hfacz.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_calc_hfacz.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_calc_hfacz.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h
mom_calc_hfacz.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_calc_hfacz.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_calc_hfacz.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_calc_hfacz.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_calc_hfacz.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_calc_hfacz.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h W2_EXCH2_SIZE.h
mom_calc_hfacz.f: W2_EXCH2_TOPOLOGY.h XC_MACROS.h YC_MACROS.h
mom_calc_ke.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_calc_ke.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_calc_ke.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_calc_ke.f: DYU_MACROS.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
mom_calc_ke.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_calc_ke.f: MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h RAS_MACROS.h
mom_calc_ke.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mom_calc_ke.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
mom_calc_ke.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_calc_ke.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
mom_calc_ke.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_calc_ke.f: YC_MACROS.h
mom_calc_relvort3.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_calc_relvort3.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_calc_relvort3.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_calc_relvort3.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
mom_calc_relvort3.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_calc_relvort3.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_calc_relvort3.f: MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_calc_relvort3.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_calc_relvort3.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_calc_relvort3.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_calc_relvort3.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_calc_relvort3.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_calc_relvort3.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h W2_EXCH2_SIZE.h
mom_calc_relvort3.f: W2_EXCH2_TOPOLOGY.h XC_MACROS.h YC_MACROS.h
mom_calc_rtrans.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_calc_rtrans.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_calc_rtrans.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_calc_rtrans.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
mom_calc_rtrans.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
mom_calc_rtrans.f: MASKS_MACROS.h MASKW_MACROS.h MOM_FLUXFORM.h
mom_calc_rtrans.f: MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_calc_rtrans.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_calc_rtrans.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_calc_rtrans.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_calc_rtrans.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_calc_rtrans.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
mom_calc_rtrans.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_calc_rtrans.f: YC_MACROS.h
mom_calc_smag_3d.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_calc_smag_3d.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_calc_smag_3d.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_calc_smag_3d.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
mom_calc_smag_3d.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
mom_calc_smag_3d.f: MASKS_MACROS.h MASKW_MACROS.h MOM_COMMON_OPTIONS.h
mom_calc_smag_3d.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
mom_calc_smag_3d.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mom_calc_smag_3d.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
mom_calc_smag_3d.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_calc_smag_3d.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_calc_smag_3d.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_calc_smag_3d.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_calc_strain.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_calc_strain.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_calc_strain.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_calc_strain.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_calc_strain.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_calc_strain.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h
mom_calc_strain.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_calc_strain.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_calc_strain.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_calc_strain.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_calc_strain.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_calc_strain.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_calc_strain.f: YC_MACROS.h
mom_calc_tension.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_calc_tension.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_calc_tension.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_calc_tension.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
mom_calc_tension.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
mom_calc_tension.f: MASKS_MACROS.h MASKW_MACROS.h MOM_COMMON_OPTIONS.h
mom_calc_tension.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
mom_calc_tension.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mom_calc_tension.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
mom_calc_tension.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_calc_tension.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_calc_tension.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_calc_tension.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_calc_visc.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_calc_visc.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_calc_visc.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_calc_visc.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_calc_visc.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_calc_visc.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h MOM_VISC.h
mom_calc_visc.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
mom_calc_visc.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mom_calc_visc.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
mom_calc_visc.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_calc_visc.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_calc_visc.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_calc_visc.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_diagnostics_init.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mom_diagnostics_init.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
mom_diagnostics_init.f: MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
mom_fluxform.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_fluxform.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_fluxform.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
mom_fluxform.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h FFIELDS.h GRID.h
mom_fluxform.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
mom_fluxform.f: MASKS_MACROS.h MASKW_MACROS.h MOM_COMMON_OPTIONS.h
mom_fluxform.f: MOM_FLUXFORM_OPTIONS.h MOM_VISC.h PACKAGES_CONFIG.h PARAMS.h
mom_fluxform.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_fluxform.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_fluxform.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_fluxform.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_fluxform.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
mom_fluxform.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_hdissip.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_hdissip.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_hdissip.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_hdissip.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_hdissip.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_hdissip.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_hdissip.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_hdissip.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_hdissip.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_hdissip.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_hdissip.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_hdissip.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_init_fixed.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_init_fixed.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_init_fixed.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_init_fixed.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_init_fixed.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_init_fixed.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h MOM_VISC.h
mom_init_fixed.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
mom_init_fixed.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mom_init_fixed.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
mom_init_fixed.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_init_fixed.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_init_fixed.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
mom_init_fixed.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_quasihydrostatic.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mom_quasihydrostatic.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
mom_quasihydrostatic.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
mom_quasihydrostatic.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
mom_quasihydrostatic.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
mom_quasihydrostatic.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_quasihydrostatic.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h
mom_quasihydrostatic.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_quasihydrostatic.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mom_quasihydrostatic.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_quasihydrostatic.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_quasihydrostatic.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_quasihydrostatic.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_quasihydrostatic.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_quasihydrostatic.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_u_adv_uu.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_u_adv_uu.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_u_adv_uu.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_u_adv_uu.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_u_adv_uu.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_u_adv_uu.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h
mom_u_adv_uu.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_u_adv_uu.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_u_adv_uu.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_u_adv_uu.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_u_adv_uu.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_u_adv_uu.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_u_adv_vu.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_u_adv_vu.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_u_adv_vu.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_u_adv_vu.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_u_adv_vu.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_u_adv_vu.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h
mom_u_adv_vu.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_u_adv_vu.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_u_adv_vu.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_u_adv_vu.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_u_adv_vu.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_u_adv_vu.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_u_adv_wu.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_u_adv_wu.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_u_adv_wu.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_u_adv_wu.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_u_adv_wu.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_u_adv_wu.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h
mom_u_adv_wu.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_u_adv_wu.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_u_adv_wu.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_u_adv_wu.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_u_adv_wu.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_u_adv_wu.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_u_botdrag_coeff.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mom_u_botdrag_coeff.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
mom_u_botdrag_coeff.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
mom_u_botdrag_coeff.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
mom_u_botdrag_coeff.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_u_botdrag_coeff.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_u_botdrag_coeff.f: MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_u_botdrag_coeff.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_u_botdrag_coeff.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mom_u_botdrag_coeff.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_u_botdrag_coeff.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_u_botdrag_coeff.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_u_botdrag_coeff.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_u_botdrag_coeff.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_u_botdrag_coeff.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_u_coriolis.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_u_coriolis.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_u_coriolis.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_u_coriolis.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_u_coriolis.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_u_coriolis.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h
mom_u_coriolis.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_u_coriolis.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_u_coriolis.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_u_coriolis.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_u_coriolis.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
mom_u_coriolis.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_u_coriolis.f: YC_MACROS.h
mom_u_coriolis_nh.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_u_coriolis_nh.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_u_coriolis_nh.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_u_coriolis_nh.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
mom_u_coriolis_nh.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_u_coriolis_nh.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_u_coriolis_nh.f: MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_u_coriolis_nh.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_u_coriolis_nh.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_u_coriolis_nh.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_u_coriolis_nh.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_u_coriolis_nh.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_u_coriolis_nh.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_u_coriolis_nh.f: YC_MACROS.h
mom_u_del2u.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_u_del2u.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_u_del2u.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_u_del2u.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_u_del2u.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_u_del2u.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h
mom_u_del2u.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_u_del2u.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_u_del2u.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_u_del2u.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_u_del2u.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
mom_u_del2u.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_u_implicit_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_u_implicit_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_u_implicit_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_u_implicit_r.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h FFIELDS.h
mom_u_implicit_r.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_u_implicit_r.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_u_implicit_r.f: MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_u_implicit_r.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_u_implicit_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_u_implicit_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_u_implicit_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_u_implicit_r.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_u_implicit_r.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_u_implicit_r.f: YC_MACROS.h
mom_u_metric_cylinder.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mom_u_metric_cylinder.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
mom_u_metric_cylinder.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
mom_u_metric_cylinder.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
mom_u_metric_cylinder.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
mom_u_metric_cylinder.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_u_metric_cylinder.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h
mom_u_metric_cylinder.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
mom_u_metric_cylinder.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mom_u_metric_cylinder.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_u_metric_cylinder.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_u_metric_cylinder.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_u_metric_cylinder.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_u_metric_cylinder.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_u_metric_cylinder.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_u_metric_nh.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_u_metric_nh.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_u_metric_nh.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_u_metric_nh.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_u_metric_nh.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_u_metric_nh.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h
mom_u_metric_nh.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_u_metric_nh.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_u_metric_nh.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_u_metric_nh.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_u_metric_nh.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_u_metric_nh.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_u_metric_nh.f: YC_MACROS.h
mom_u_metric_sphere.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mom_u_metric_sphere.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
mom_u_metric_sphere.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
mom_u_metric_sphere.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
mom_u_metric_sphere.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_u_metric_sphere.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_u_metric_sphere.f: MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_u_metric_sphere.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_u_metric_sphere.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mom_u_metric_sphere.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_u_metric_sphere.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_u_metric_sphere.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_u_metric_sphere.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_u_metric_sphere.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_u_metric_sphere.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_u_rviscflux.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_u_rviscflux.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_u_rviscflux.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_u_rviscflux.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_u_rviscflux.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_u_rviscflux.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h
mom_u_rviscflux.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_u_rviscflux.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_u_rviscflux.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_u_rviscflux.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_u_rviscflux.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_u_rviscflux.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_u_rviscflux.f: YC_MACROS.h
mom_u_sidedrag.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_u_sidedrag.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_u_sidedrag.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_u_sidedrag.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_u_sidedrag.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_u_sidedrag.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h
mom_u_sidedrag.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_u_sidedrag.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_u_sidedrag.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_u_sidedrag.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_u_sidedrag.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
mom_u_sidedrag.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_u_sidedrag.f: YC_MACROS.h
mom_u_xviscflux.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_u_xviscflux.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_u_xviscflux.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_u_xviscflux.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_u_xviscflux.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_u_xviscflux.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h
mom_u_xviscflux.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_u_xviscflux.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_u_xviscflux.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_u_xviscflux.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_u_xviscflux.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_u_xviscflux.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_u_xviscflux.f: YC_MACROS.h
mom_u_yviscflux.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_u_yviscflux.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_u_yviscflux.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_u_yviscflux.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_u_yviscflux.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_u_yviscflux.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h
mom_u_yviscflux.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_u_yviscflux.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_u_yviscflux.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_u_yviscflux.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_u_yviscflux.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_u_yviscflux.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_u_yviscflux.f: YC_MACROS.h
mom_uv_boundary.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_uv_boundary.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_uv_boundary.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_uv_boundary.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_uv_boundary.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_uv_boundary.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h
mom_uv_boundary.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_uv_boundary.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_uv_boundary.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_uv_boundary.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_uv_boundary.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_uv_boundary.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_uv_boundary.f: YC_MACROS.h
mom_uv_smag_3d.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_uv_smag_3d.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_uv_smag_3d.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_uv_smag_3d.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_uv_smag_3d.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_uv_smag_3d.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h
mom_uv_smag_3d.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_uv_smag_3d.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_uv_smag_3d.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_uv_smag_3d.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_uv_smag_3d.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_uv_smag_3d.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_uv_smag_3d.f: YC_MACROS.h
mom_v_adv_uv.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_v_adv_uv.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_v_adv_uv.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_v_adv_uv.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_v_adv_uv.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_v_adv_uv.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h
mom_v_adv_uv.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_v_adv_uv.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_v_adv_uv.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_v_adv_uv.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_v_adv_uv.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_v_adv_uv.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_v_adv_vv.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_v_adv_vv.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_v_adv_vv.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_v_adv_vv.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_v_adv_vv.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_v_adv_vv.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h
mom_v_adv_vv.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_v_adv_vv.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_v_adv_vv.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_v_adv_vv.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_v_adv_vv.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_v_adv_vv.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_v_adv_wv.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_v_adv_wv.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_v_adv_wv.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_v_adv_wv.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_v_adv_wv.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_v_adv_wv.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h
mom_v_adv_wv.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_v_adv_wv.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_v_adv_wv.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_v_adv_wv.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_v_adv_wv.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_v_adv_wv.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_v_botdrag_coeff.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mom_v_botdrag_coeff.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
mom_v_botdrag_coeff.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
mom_v_botdrag_coeff.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
mom_v_botdrag_coeff.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_v_botdrag_coeff.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_v_botdrag_coeff.f: MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_v_botdrag_coeff.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_v_botdrag_coeff.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mom_v_botdrag_coeff.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_v_botdrag_coeff.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_v_botdrag_coeff.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_v_botdrag_coeff.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_v_botdrag_coeff.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_v_botdrag_coeff.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_v_coriolis.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_v_coriolis.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_v_coriolis.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_v_coriolis.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_v_coriolis.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_v_coriolis.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h
mom_v_coriolis.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_v_coriolis.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_v_coriolis.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_v_coriolis.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_v_coriolis.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
mom_v_coriolis.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_v_coriolis.f: YC_MACROS.h
mom_v_coriolis_nh.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_v_coriolis_nh.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_v_coriolis_nh.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_v_coriolis_nh.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
mom_v_coriolis_nh.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_v_coriolis_nh.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_v_coriolis_nh.f: MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_v_coriolis_nh.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_v_coriolis_nh.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_v_coriolis_nh.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_v_coriolis_nh.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_v_coriolis_nh.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_v_coriolis_nh.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_v_coriolis_nh.f: YC_MACROS.h
mom_v_del2v.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_v_del2v.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_v_del2v.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_v_del2v.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_v_del2v.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_v_del2v.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h
mom_v_del2v.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_v_del2v.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_v_del2v.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_v_del2v.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_v_del2v.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
mom_v_del2v.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_v_implicit_r.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_v_implicit_r.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_v_implicit_r.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_v_implicit_r.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h FFIELDS.h
mom_v_implicit_r.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_v_implicit_r.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_v_implicit_r.f: MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_v_implicit_r.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_v_implicit_r.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_v_implicit_r.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_v_implicit_r.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_v_implicit_r.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_v_implicit_r.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_v_implicit_r.f: YC_MACROS.h
mom_v_metric_cylinder.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mom_v_metric_cylinder.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
mom_v_metric_cylinder.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
mom_v_metric_cylinder.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
mom_v_metric_cylinder.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
mom_v_metric_cylinder.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_v_metric_cylinder.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h
mom_v_metric_cylinder.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
mom_v_metric_cylinder.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mom_v_metric_cylinder.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_v_metric_cylinder.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_v_metric_cylinder.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_v_metric_cylinder.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_v_metric_cylinder.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_v_metric_cylinder.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_v_metric_nh.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_v_metric_nh.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_v_metric_nh.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_v_metric_nh.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_v_metric_nh.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_v_metric_nh.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h
mom_v_metric_nh.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_v_metric_nh.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_v_metric_nh.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_v_metric_nh.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_v_metric_nh.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_v_metric_nh.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_v_metric_nh.f: YC_MACROS.h
mom_v_metric_sphere.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mom_v_metric_sphere.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
mom_v_metric_sphere.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
mom_v_metric_sphere.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
mom_v_metric_sphere.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_v_metric_sphere.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_v_metric_sphere.f: MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_v_metric_sphere.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_v_metric_sphere.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mom_v_metric_sphere.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_v_metric_sphere.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_v_metric_sphere.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_v_metric_sphere.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_v_metric_sphere.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_v_metric_sphere.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_v_rviscflux.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_v_rviscflux.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_v_rviscflux.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_v_rviscflux.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_v_rviscflux.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_v_rviscflux.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h
mom_v_rviscflux.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_v_rviscflux.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_v_rviscflux.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_v_rviscflux.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_v_rviscflux.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_v_rviscflux.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_v_rviscflux.f: YC_MACROS.h
mom_v_sidedrag.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_v_sidedrag.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_v_sidedrag.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_v_sidedrag.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_v_sidedrag.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_v_sidedrag.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h
mom_v_sidedrag.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_v_sidedrag.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_v_sidedrag.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_v_sidedrag.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_v_sidedrag.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
mom_v_sidedrag.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_v_sidedrag.f: YC_MACROS.h
mom_v_xviscflux.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_v_xviscflux.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_v_xviscflux.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_v_xviscflux.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_v_xviscflux.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_v_xviscflux.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h
mom_v_xviscflux.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_v_xviscflux.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_v_xviscflux.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_v_xviscflux.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_v_xviscflux.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_v_xviscflux.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_v_xviscflux.f: YC_MACROS.h
mom_v_yviscflux.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_v_yviscflux.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_v_yviscflux.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_v_yviscflux.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_v_yviscflux.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_v_yviscflux.f: MASKW_MACROS.h MOM_FLUXFORM_OPTIONS.h PACKAGES_CONFIG.h
mom_v_yviscflux.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_v_yviscflux.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_v_yviscflux.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_v_yviscflux.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_v_yviscflux.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_v_yviscflux.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_v_yviscflux.f: YC_MACROS.h
mom_vecinv.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_vecinv.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_vecinv.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
mom_vecinv.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h FFIELDS.h GRID.h
mom_vecinv.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
mom_vecinv.f: MASKS_MACROS.h MASKW_MACROS.h MNC_PARAMS.h MOM_COMMON_OPTIONS.h
mom_vecinv.f: MOM_VECINV_OPTIONS.h MOM_VISC.h PACKAGES_CONFIG.h PARAMS.h
mom_vecinv.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_vecinv.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_vecinv.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_vecinv.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_vecinv.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
mom_vecinv.f: TANPHIATV_MACROS.h TIMEAVE_OPTIONS.h TIMEAVE_STATV.h XC_MACROS.h
mom_vecinv.f: YC_MACROS.h
mom_vi_coriolis.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_vi_coriolis.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_vi_coriolis.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_vi_coriolis.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_vi_coriolis.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_vi_coriolis.f: MASKW_MACROS.h MOM_VECINV_OPTIONS.h PACKAGES_CONFIG.h
mom_vi_coriolis.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_vi_coriolis.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_vi_coriolis.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_vi_coriolis.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_vi_coriolis.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_vi_coriolis.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_vi_coriolis.f: YC_MACROS.h
mom_vi_del2uv.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_vi_del2uv.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_vi_del2uv.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_vi_del2uv.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_vi_del2uv.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_vi_del2uv.f: MASKW_MACROS.h MOM_VECINV_OPTIONS.h PACKAGES_CONFIG.h
mom_vi_del2uv.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_vi_del2uv.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_vi_del2uv.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_vi_del2uv.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_vi_del2uv.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_vi_del2uv.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_vi_hdissip.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_vi_hdissip.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_vi_hdissip.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_vi_hdissip.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_vi_hdissip.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_vi_hdissip.f: MASKW_MACROS.h MOM_VECINV_OPTIONS.h PACKAGES_CONFIG.h
mom_vi_hdissip.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_vi_hdissip.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_vi_hdissip.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_vi_hdissip.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_vi_hdissip.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_vi_hdissip.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_vi_hdissip.f: YC_MACROS.h
mom_vi_u_coriolis.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_vi_u_coriolis.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_vi_u_coriolis.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_vi_u_coriolis.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
mom_vi_u_coriolis.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_vi_u_coriolis.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_vi_u_coriolis.f: MOM_VECINV_OPTIONS.h PACKAGES_CONFIG.h RAS_MACROS.h
mom_vi_u_coriolis.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_vi_u_coriolis.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_vi_u_coriolis.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_vi_u_coriolis.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_vi_u_coriolis.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_vi_u_coriolis.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_vi_u_coriolis.f: YC_MACROS.h
mom_vi_u_coriolis_c4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mom_vi_u_coriolis_c4.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
mom_vi_u_coriolis_c4.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
mom_vi_u_coriolis_c4.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
mom_vi_u_coriolis_c4.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
mom_vi_u_coriolis_c4.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_vi_u_coriolis_c4.f: MASKW_MACROS.h MOM_VECINV_OPTIONS.h PACKAGES_CONFIG.h
mom_vi_u_coriolis_c4.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_vi_u_coriolis_c4.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mom_vi_u_coriolis_c4.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_vi_u_coriolis_c4.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_vi_u_coriolis_c4.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_vi_u_coriolis_c4.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_vi_u_coriolis_c4.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_vi_u_coriolis_c4.f: TANPHIATV_MACROS.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
mom_vi_u_coriolis_c4.f: XC_MACROS.h YC_MACROS.h
mom_vi_u_grad_ke.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_vi_u_grad_ke.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_vi_u_grad_ke.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_vi_u_grad_ke.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
mom_vi_u_grad_ke.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
mom_vi_u_grad_ke.f: MASKS_MACROS.h MASKW_MACROS.h MOM_VECINV_OPTIONS.h
mom_vi_u_grad_ke.f: PACKAGES_CONFIG.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_vi_u_grad_ke.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_vi_u_grad_ke.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_vi_u_grad_ke.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_vi_u_grad_ke.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_vi_u_grad_ke.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_vi_u_grad_ke.f: YC_MACROS.h
mom_vi_u_vertshear.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mom_vi_u_vertshear.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
mom_vi_u_vertshear.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
mom_vi_u_vertshear.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
mom_vi_u_vertshear.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_vi_u_vertshear.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_vi_u_vertshear.f: MOM_VECINV_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_vi_u_vertshear.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_vi_u_vertshear.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_vi_u_vertshear.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_vi_u_vertshear.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_vi_u_vertshear.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_vi_u_vertshear.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_vi_u_vertshear.f: YC_MACROS.h
mom_vi_v_coriolis.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_vi_v_coriolis.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_vi_v_coriolis.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_vi_v_coriolis.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
mom_vi_v_coriolis.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_vi_v_coriolis.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_vi_v_coriolis.f: MOM_VECINV_OPTIONS.h PACKAGES_CONFIG.h RAS_MACROS.h
mom_vi_v_coriolis.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_vi_v_coriolis.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_vi_v_coriolis.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_vi_v_coriolis.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_vi_v_coriolis.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_vi_v_coriolis.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_vi_v_coriolis.f: YC_MACROS.h
mom_vi_v_coriolis_c4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mom_vi_v_coriolis_c4.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
mom_vi_v_coriolis_c4.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
mom_vi_v_coriolis_c4.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
mom_vi_v_coriolis_c4.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
mom_vi_v_coriolis_c4.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_vi_v_coriolis_c4.f: MASKW_MACROS.h MOM_VECINV_OPTIONS.h PACKAGES_CONFIG.h
mom_vi_v_coriolis_c4.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_vi_v_coriolis_c4.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mom_vi_v_coriolis_c4.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_vi_v_coriolis_c4.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_vi_v_coriolis_c4.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_vi_v_coriolis_c4.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_vi_v_coriolis_c4.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_vi_v_coriolis_c4.f: TANPHIATV_MACROS.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
mom_vi_v_coriolis_c4.f: XC_MACROS.h YC_MACROS.h
mom_vi_v_grad_ke.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_vi_v_grad_ke.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_vi_v_grad_ke.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_vi_v_grad_ke.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
mom_vi_v_grad_ke.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
mom_vi_v_grad_ke.f: MASKS_MACROS.h MASKW_MACROS.h MOM_VECINV_OPTIONS.h
mom_vi_v_grad_ke.f: PACKAGES_CONFIG.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_vi_v_grad_ke.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_vi_v_grad_ke.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_vi_v_grad_ke.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_vi_v_grad_ke.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_vi_v_grad_ke.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_vi_v_grad_ke.f: YC_MACROS.h
mom_vi_v_vertshear.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mom_vi_v_vertshear.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
mom_vi_v_vertshear.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
mom_vi_v_vertshear.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
mom_vi_v_vertshear.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_vi_v_vertshear.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_vi_v_vertshear.f: MOM_VECINV_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_vi_v_vertshear.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_vi_v_vertshear.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_vi_v_vertshear.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_vi_v_vertshear.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_vi_v_vertshear.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_vi_v_vertshear.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_vi_v_vertshear.f: YC_MACROS.h
mom_visc_qgl_limit.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mom_visc_qgl_limit.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
mom_visc_qgl_limit.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
mom_visc_qgl_limit.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
mom_visc_qgl_limit.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_visc_qgl_limit.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_visc_qgl_limit.f: MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_visc_qgl_limit.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_visc_qgl_limit.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_visc_qgl_limit.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_visc_qgl_limit.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_visc_qgl_limit.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_visc_qgl_limit.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_visc_qgl_limit.f: YC_MACROS.h
mom_visc_qgl_stretch.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mom_visc_qgl_stretch.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
mom_visc_qgl_stretch.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
mom_visc_qgl_stretch.f: DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
mom_visc_qgl_stretch.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_visc_qgl_stretch.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
mom_visc_qgl_stretch.f: MASKS_MACROS.h MASKW_MACROS.h MOM_COMMON_OPTIONS.h
mom_visc_qgl_stretch.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
mom_visc_qgl_stretch.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mom_visc_qgl_stretch.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_visc_qgl_stretch.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_visc_qgl_stretch.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mom_visc_qgl_stretch.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mom_visc_qgl_stretch.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mom_visc_qgl_stretch.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mom_w_coriolis_nh.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_w_coriolis_nh.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_w_coriolis_nh.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_w_coriolis_nh.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
mom_w_coriolis_nh.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
mom_w_coriolis_nh.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mom_w_coriolis_nh.f: MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mom_w_coriolis_nh.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mom_w_coriolis_nh.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mom_w_coriolis_nh.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mom_w_coriolis_nh.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_w_coriolis_nh.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_w_coriolis_nh.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_w_coriolis_nh.f: YC_MACROS.h
mom_w_metric_nh.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_w_metric_nh.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_w_metric_nh.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_w_metric_nh.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_w_metric_nh.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_w_metric_nh.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h
mom_w_metric_nh.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_w_metric_nh.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_w_metric_nh.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_w_metric_nh.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_w_metric_nh.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_w_metric_nh.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_w_metric_nh.f: YC_MACROS.h
mom_w_sidedrag.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_w_sidedrag.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_w_sidedrag.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_w_sidedrag.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_w_sidedrag.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_w_sidedrag.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h
mom_w_sidedrag.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_w_sidedrag.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_w_sidedrag.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_w_sidedrag.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_w_sidedrag.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
mom_w_sidedrag.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mom_w_sidedrag.f: YC_MACROS.h
mom_w_smag_3d.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mom_w_smag_3d.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mom_w_smag_3d.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mom_w_smag_3d.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mom_w_smag_3d.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mom_w_smag_3d.f: MASKW_MACROS.h MOM_COMMON_OPTIONS.h PACKAGES_CONFIG.h
mom_w_smag_3d.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mom_w_smag_3d.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mom_w_smag_3d.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mom_w_smag_3d.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mom_w_smag_3d.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mom_w_smag_3d.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
momentum_correction_step.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
momentum_correction_step.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DYNVARS.h EEPARAMS.h
momentum_correction_step.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
mon_advcfl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_advcfl.f: CPP_OPTIONS.h EEPARAMS.h MONITOR.h MONITOR_OPTIONS.h
mon_advcfl.f: PACKAGES_CONFIG.h SIZE.h
mon_advcflw.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_advcflw.f: CPP_OPTIONS.h EEPARAMS.h MONITOR.h MONITOR_OPTIONS.h
mon_advcflw.f: PACKAGES_CONFIG.h SIZE.h
mon_advcflw2.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_advcflw2.f: CPP_OPTIONS.h EEPARAMS.h MONITOR.h MONITOR_OPTIONS.h
mon_advcflw2.f: PACKAGES_CONFIG.h SIZE.h
mon_calc_advcfl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_calc_advcfl.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mon_calc_advcfl.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
mon_calc_advcfl.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mon_calc_advcfl.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mon_calc_advcfl.f: MASKW_MACROS.h MONITOR.h MONITOR_OPTIONS.h
mon_calc_advcfl.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
mon_calc_advcfl.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mon_calc_advcfl.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
mon_calc_advcfl.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mon_calc_advcfl.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mon_calc_advcfl.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
mon_calc_advcfl.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mon_calc_stats_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_calc_stats_rl.f: CPP_OPTIONS.h EEPARAMS.h MONITOR_OPTIONS.h
mon_calc_stats_rl.f: PACKAGES_CONFIG.h SIZE.h
mon_calc_stats_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_calc_stats_rs.f: CPP_OPTIONS.h EEPARAMS.h MONITOR_OPTIONS.h
mon_calc_stats_rs.f: PACKAGES_CONFIG.h SIZE.h
mon_init.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_init.f: CPP_OPTIONS.h EEPARAMS.h MONITOR.h MONITOR_OPTIONS.h
mon_init.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
mon_ke.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_ke.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
mon_ke.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
mon_ke.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
mon_ke.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mon_ke.f: MONITOR.h MONITOR_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
mon_ke.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
mon_ke.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
mon_ke.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
mon_ke.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
mon_ke.f: SIZE.h SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
mon_ke.f: YC_MACROS.h
mon_out.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_out.f: CPP_OPTIONS.h EEPARAMS.h MONITOR.h MONITOR_OPTIONS.h
mon_out.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
mon_printstats_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_printstats_rl.f: CPP_OPTIONS.h EEPARAMS.h MONITOR.h MONITOR_OPTIONS.h
mon_printstats_rl.f: PACKAGES_CONFIG.h SIZE.h
mon_printstats_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_printstats_rs.f: CPP_OPTIONS.h EEPARAMS.h MONITOR.h MONITOR_OPTIONS.h
mon_printstats_rs.f: PACKAGES_CONFIG.h SIZE.h
mon_set_iounit.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_set_iounit.f: CPP_OPTIONS.h EEPARAMS.h MONITOR.h MONITOR_OPTIONS.h
mon_set_iounit.f: PACKAGES_CONFIG.h SIZE.h
mon_set_pref.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_set_pref.f: CPP_OPTIONS.h EEPARAMS.h MONITOR.h MONITOR_OPTIONS.h
mon_set_pref.f: PACKAGES_CONFIG.h SIZE.h
mon_solution.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_solution.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mon_solution.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
mon_solution.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mon_solution.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mon_solution.f: MASKW_MACROS.h MONITOR.h MONITOR_OPTIONS.h PACKAGES_CONFIG.h
mon_solution.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mon_solution.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mon_solution.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mon_solution.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mon_solution.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
mon_solution.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mon_stats_latbnd_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
mon_stats_latbnd_rl.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
mon_stats_latbnd_rl.f: MONITOR_OPTIONS.h PACKAGES_CONFIG.h SIZE.h
mon_stats_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_stats_rl.f: CPP_OPTIONS.h EEPARAMS.h MONITOR_OPTIONS.h PACKAGES_CONFIG.h
mon_stats_rl.f: SIZE.h
mon_stats_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_stats_rs.f: CPP_OPTIONS.h EEPARAMS.h MONITOR_OPTIONS.h PACKAGES_CONFIG.h
mon_stats_rs.f: SIZE.h
mon_surfcor.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_surfcor.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
mon_surfcor.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
mon_surfcor.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
mon_surfcor.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
mon_surfcor.f: MASKW_MACROS.h MONITOR.h MONITOR_OPTIONS.h PACKAGES_CONFIG.h
mon_surfcor.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
mon_surfcor.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
mon_surfcor.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
mon_surfcor.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
mon_surfcor.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
mon_surfcor.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
mon_vort3.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_vort3.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
mon_vort3.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
mon_vort3.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
mon_vort3.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
mon_vort3.f: MONITOR.h MONITOR_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h
mon_vort3.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
mon_vort3.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
mon_vort3.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
mon_vort3.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
mon_vort3.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
mon_vort3.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h XC_MACROS.h YC_MACROS.h
mon_writestats_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_writestats_rl.f: CPP_OPTIONS.h EEPARAMS.h MONITOR.h MONITOR_OPTIONS.h
mon_writestats_rl.f: PACKAGES_CONFIG.h SIZE.h
mon_writestats_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
mon_writestats_rs.f: CPP_OPTIONS.h EEPARAMS.h MONITOR.h MONITOR_OPTIONS.h
mon_writestats_rs.f: PACKAGES_CONFIG.h SIZE.h
monitor.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
monitor.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
monitor.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
monitor.f: EEPARAMS.h FCORI_MACROS.h FFIELDS.h GRID.h GRID_MACROS.h
monitor.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
monitor.f: MASKW_MACROS.h MNC_PARAMS.h MONITOR.h MONITOR_OPTIONS.h
monitor.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
monitor.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
monitor.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
monitor.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
monitor.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
monitor.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
monitor_ad.f: /usr/include/stdc-predef.h AD_CONFIG.h CPP_EEMACROS.h
monitor_ad.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
monitor_ad.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
monitor_ad.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
monitor_ad.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
monitor_ad.f: MASKW_MACROS.h MNC_PARAMS.h MONITOR.h MONITOR_OPTIONS.h
monitor_ad.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
monitor_ad.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
monitor_ad.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
monitor_ad.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
monitor_ad.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
monitor_ad.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
monitor_g.f: /usr/include/stdc-predef.h AD_CONFIG.h CPP_EEMACROS.h
monitor_g.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
monitor_g.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
monitor_g.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h FFIELDS.h GRID.h
monitor_g.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
monitor_g.f: MASKS_MACROS.h MASKW_MACROS.h MNC_PARAMS.h MONITOR.h
monitor_g.f: MONITOR_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
monitor_g.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
monitor_g.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
monitor_g.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
monitor_g.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
monitor_g.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
monitor_g.f: YC_MACROS.h
nml_change_syntax.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
nml_change_syntax.f: EEPARAMS.h
nml_set_terminator.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
nml_set_terminator.f: CPP_EEOPTIONS.h EEPARAMS.h
open_copy_data_file.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
open_copy_data_file.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h
ostres.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
ostres.f: CPP_OPTIONS.h EEPARAMS.h FFIELDS.h PACKAGES_CONFIG.h PARAMS.h
ostres.f: SEAICE.h SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
packages_boot.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
packages_boot.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
packages_check.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
packages_check.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
packages_error_msg.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
packages_error_msg.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h SIZE.h
packages_init_fixed.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
packages_init_fixed.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
packages_init_fixed.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
packages_init_variables.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
packages_init_variables.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
packages_init_variables.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
packages_print_msg.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
packages_print_msg.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h SIZE.h
packages_readparms.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
packages_readparms.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
packages_readparms.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
packages_unused_msg.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
packages_unused_msg.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h SIZE.h
packages_write_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
packages_write_pickup.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
packages_write_pickup.f: PACKAGES_CONFIG.h PARAMS.h RESTART.h SIZE.h
plot_field.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
plot_field.f: CPP_OPTIONS.h EEPARAMS.h PARAMS.h SIZE.h
port_rand.f: /usr/include/stdc-predef.h
post_cg3d.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
post_cg3d.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
post_cg3d.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
post_cg3d.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
post_cg3d.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
post_cg3d.f: NH_VARS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
post_cg3d.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
post_cg3d.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
post_cg3d.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
post_cg3d.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
post_cg3d.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
pre_cg3d.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
pre_cg3d.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
pre_cg3d.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
pre_cg3d.f: EEPARAMS.h FCORI_MACROS.h FFIELDS.h GRID.h GRID_MACROS.h
pre_cg3d.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
pre_cg3d.f: MASKW_MACROS.h NH_VARS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
pre_cg3d.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
pre_cg3d.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
pre_cg3d.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
pre_cg3d.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
pre_cg3d.f: SIZE.h SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
pre_cg3d.f: YC_MACROS.h
pressure_for_eos.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
pressure_for_eos.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
pressure_for_eos.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
pressure_for_eos.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
pressure_for_eos.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
pressure_for_eos.f: MASKS_MACROS.h MASKW_MACROS.h NH_VARS.h PARAMS.h
pressure_for_eos.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
pressure_for_eos.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
pressure_for_eos.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
pressure_for_eos.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
pressure_for_eos.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
pressure_for_eos.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
pressure_for_eos.f: YC_MACROS.h
print.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h /usr/include/stdc-predef.h
print.f: CPP_EEMACROS.h CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h SIZE.h
read_fld_xy_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
read_fld_xy_rl.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
read_fld_xy_rl.f: RW_OPTIONS.h SIZE.h
read_fld_xy_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
read_fld_xy_rs.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
read_fld_xy_rs.f: RW_OPTIONS.h SIZE.h
read_fld_xyz_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
read_fld_xyz_rl.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
read_fld_xyz_rl.f: RW_OPTIONS.h SIZE.h
read_fld_xyz_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
read_fld_xyz_rs.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
read_fld_xyz_rs.f: RW_OPTIONS.h SIZE.h
read_glvec_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
read_glvec_rl.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
read_glvec_rl.f: RW_OPTIONS.h SIZE.h
read_glvec_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
read_glvec_rs.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
read_glvec_rs.f: RW_OPTIONS.h SIZE.h
read_mflds.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
read_mflds.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h RW_MFLDS.h
read_mflds.f: RW_OPTIONS.h SIZE.h
read_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
read_pickup.f: CPP_OPTIONS.h DYNVARS.h EEPARAMS.h FFIELDS.h GAD.h MNC_PARAMS.h
read_pickup.f: NH_VARS.h PACKAGES_CONFIG.h PARAMS.h RESTART.h SIZE.h SURFACE.h
read_rec.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
read_rec.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h RW_OPTIONS.h
read_rec.f: SIZE.h
remove_mean.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
remove_mean.f: CPP_OPTIONS.h EEPARAMS.h PARAMS.h SIZE.h
reset_halo.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
reset_halo.f: EEPARAMS.h SIZE.h
reset_nlfs_vars.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
reset_nlfs_vars.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
reset_nlfs_vars.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
reset_nlfs_vars.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
reset_nlfs_vars.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
reset_nlfs_vars.f: MASKW_MACROS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
reset_nlfs_vars.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
reset_nlfs_vars.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
reset_nlfs_vars.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
reset_nlfs_vars.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
reset_nlfs_vars.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
reset_nlfs_vars.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
rotate_spherical_polar_grid.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
rotate_spherical_polar_grid.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
rotate_spherical_polar_grid.f: PARAMS.h SIZE.h
rotate_uv2en.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
rotate_uv2en.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
rotate_uv2en.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
rotate_uv2en.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
rotate_uv2en.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
rotate_uv2en.f: MASKW_MACROS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
rotate_uv2en.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
rotate_uv2en.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
rotate_uv2en.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
rotate_uv2en.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
rotate_uv2en.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
rw_get_suffix.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
rw_get_suffix.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
rw_get_suffix.f: RW_OPTIONS.h SIZE.h
salt_fill.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
salt_fill.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
salt_fill.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
salt_fill.f: FCORI_MACROS.h GAD_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
salt_fill.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
salt_fill.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
salt_fill.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
salt_fill.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
salt_fill.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
salt_fill.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
salt_fill.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
salt_integrate.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
salt_integrate.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
salt_integrate.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
salt_integrate.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h
salt_integrate.f: GAD_OPTIONS.h GAD_SOM_VARS.h GRID.h GRID_MACROS.h
salt_integrate.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
salt_integrate.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
salt_integrate.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
salt_integrate.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
salt_integrate.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
salt_integrate.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
salt_integrate.f: RECIP_HFACW_MACROS.h RESTART.h SIZE.h TANPHIATU_MACROS.h
salt_integrate.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
scatter_2d_r4.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
scatter_2d_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
scatter_2d_r4.f: EEPARAMS.h EESUPPORT.h PACKAGES_CONFIG.h SIZE.h
scatter_2d_r4.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
scatter_2d_r8.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
scatter_2d_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
scatter_2d_r8.f: EEPARAMS.h EESUPPORT.h PACKAGES_CONFIG.h SIZE.h
scatter_2d_r8.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
scatter_2d_wh_r4.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
scatter_2d_wh_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
scatter_2d_wh_r4.f: EEPARAMS.h EESUPPORT.h PACKAGES_CONFIG.h SIZE.h
scatter_2d_wh_r8.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
scatter_2d_wh_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
scatter_2d_wh_r8.f: EEPARAMS.h EESUPPORT.h PACKAGES_CONFIG.h SIZE.h
scatter_vec_r4.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
scatter_vec_r4.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
scatter_vec_r4.f: EEPARAMS.h EESUPPORT.h SIZE.h
scatter_vec_r8.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
scatter_vec_r8.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
scatter_vec_r8.f: EEPARAMS.h EESUPPORT.h SIZE.h
scatter_xz.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
scatter_xz.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
scatter_xz.f: EEPARAMS.h EESUPPORT.h SIZE.h
scatter_yz.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
scatter_yz.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
scatter_yz.f: EEPARAMS.h EESUPPORT.h SIZE.h
seaice_ad_dump.f: /usr/include/stdc-predef.h AD_CONFIG.h CPP_EEMACROS.h
seaice_ad_dump.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
seaice_ad_dump.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
seaice_ad_dump.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
seaice_ad_dump.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
seaice_ad_dump.f: MASKS_MACROS.h MASKW_MACROS.h MNC_PARAMS.h PACKAGES_CONFIG.h
seaice_ad_dump.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
seaice_ad_dump.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
seaice_ad_dump.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
seaice_ad_dump.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
seaice_ad_dump.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SEAICE_OPTIONS.h
seaice_ad_dump.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h TANPHIATU_MACROS.h
seaice_ad_dump.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_advdiff.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_advdiff.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_advdiff.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_advdiff.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
seaice_advdiff.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_advdiff.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
seaice_advdiff.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
seaice_advdiff.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_advdiff.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
seaice_advdiff.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_advdiff.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_advdiff.f: SEAICE_PARAMS.h SEAICE_SIZE.h SEAICE_TRACER.h SIZE.h
seaice_advdiff.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_advdiff.f: YC_MACROS.h
seaice_advection.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_advection.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_advection.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_advection.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h
seaice_advection.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
seaice_advection.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
seaice_advection.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
seaice_advection.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_advection.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_advection.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_advection.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_advection.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_advection.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h TANPHIATU_MACROS.h
seaice_advection.f: TANPHIATV_MACROS.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
seaice_advection.f: XC_MACROS.h YC_MACROS.h
seaice_bottomdrag_coeffs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_bottomdrag_coeffs.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
seaice_bottomdrag_coeffs.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
seaice_bottomdrag_coeffs.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
seaice_bottomdrag_coeffs.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
seaice_bottomdrag_coeffs.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
seaice_bottomdrag_coeffs.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
seaice_bottomdrag_coeffs.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
seaice_bottomdrag_coeffs.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
seaice_bottomdrag_coeffs.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
seaice_bottomdrag_coeffs.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_bottomdrag_coeffs.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
seaice_bottomdrag_coeffs.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
seaice_bottomdrag_coeffs.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
seaice_bottomdrag_coeffs.f: SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h
seaice_bottomdrag_coeffs.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
seaice_bottomdrag_coeffs.f: XC_MACROS.h YC_MACROS.h
seaice_budget_ocean.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_budget_ocean.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h FFIELDS.h
seaice_budget_ocean.f: PACKAGES_CONFIG.h SEAICE_OPTIONS.h SIZE.h
seaice_calc_ice_strength.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_calc_ice_strength.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
seaice_calc_ice_strength.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
seaice_calc_ice_strength.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_calc_ice_strength.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
seaice_calc_ice_strength.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
seaice_calc_ice_strength.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
seaice_calc_ice_strength.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
seaice_calc_ice_strength.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
seaice_calc_ice_strength.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
seaice_calc_ice_strength.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_calc_ice_strength.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
seaice_calc_ice_strength.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
seaice_calc_ice_strength.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SEAICE.h
seaice_calc_ice_strength.f: SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h
seaice_calc_ice_strength.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
seaice_calc_ice_strength.f: XC_MACROS.h YC_MACROS.h
seaice_calc_lhs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_calc_lhs.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_calc_lhs.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_calc_lhs.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
seaice_calc_lhs.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_calc_lhs.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
seaice_calc_lhs.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
seaice_calc_lhs.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_calc_lhs.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
seaice_calc_lhs.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
seaice_calc_lhs.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SEAICE.h
seaice_calc_lhs.f: SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_calc_lhs.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_calc_lhs.f: YC_MACROS.h
seaice_calc_residual.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_calc_residual.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
seaice_calc_residual.f: PACKAGES_CONFIG.h SEAICE.h SEAICE_OPTIONS.h
seaice_calc_residual.f: SEAICE_SIZE.h SIZE.h
seaice_calc_rhs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_calc_rhs.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_calc_rhs.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_calc_rhs.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
seaice_calc_rhs.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
seaice_calc_rhs.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
seaice_calc_rhs.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
seaice_calc_rhs.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_calc_rhs.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
seaice_calc_rhs.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
seaice_calc_rhs.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SEAICE.h
seaice_calc_rhs.f: SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_calc_rhs.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_calc_rhs.f: YC_MACROS.h
seaice_calc_strainrates.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_calc_strainrates.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
seaice_calc_strainrates.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
seaice_calc_strainrates.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
seaice_calc_strainrates.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
seaice_calc_strainrates.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_calc_strainrates.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
seaice_calc_strainrates.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
seaice_calc_strainrates.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_calc_strainrates.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_calc_strainrates.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
seaice_calc_strainrates.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_calc_strainrates.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_calc_strainrates.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_calc_strainrates.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_calc_strainrates.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_calc_strainrates.f: YC_MACROS.h
seaice_calc_stressdiv.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_calc_stressdiv.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
seaice_calc_stressdiv.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
seaice_calc_stressdiv.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
seaice_calc_stressdiv.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
seaice_calc_stressdiv.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_calc_stressdiv.f: MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
seaice_calc_stressdiv.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
seaice_calc_stressdiv.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
seaice_calc_stressdiv.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_calc_stressdiv.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
seaice_calc_stressdiv.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
seaice_calc_stressdiv.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
seaice_calc_stressdiv.f: SEAICE_OPTIONS.h SIZE.h TANPHIATU_MACROS.h
seaice_calc_stressdiv.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_calc_viscosities.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_calc_viscosities.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
seaice_calc_viscosities.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
seaice_calc_viscosities.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
seaice_calc_viscosities.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
seaice_calc_viscosities.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_calc_viscosities.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
seaice_calc_viscosities.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
seaice_calc_viscosities.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_calc_viscosities.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_calc_viscosities.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
seaice_calc_viscosities.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_calc_viscosities.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_calc_viscosities.f: RECIP_HFACW_MACROS.h SEAICE_OPTIONS.h
seaice_calc_viscosities.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_calc_viscosities.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_calc_viscosities.f: YC_MACROS.h
seaice_check.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_check.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_check.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_check.f: DYU_MACROS.h EEPARAMS.h EXF_OPTIONS.h EXF_PARAM.h
seaice_check.f: FCORI_MACROS.h GAD.h GRID.h GRID_MACROS.h HFACC_MACROS.h
seaice_check.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
seaice_check.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
seaice_check.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_check.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_check.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_check.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
seaice_check.f: SEAICE.h SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h
seaice_check.f: SEAICE_TRACER.h SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
seaice_check.f: XC_MACROS.h YC_MACROS.h
seaice_check_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_check_pickup.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
seaice_check_pickup.f: PACKAGES_CONFIG.h PARAMS.h SEAICE.h SEAICE_OPTIONS.h
seaice_check_pickup.f: SEAICE_PARAMS.h SEAICE_SIZE.h SEAICE_TRACER.h SIZE.h
seaice_cost_accumulate_mean.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_cost_accumulate_mean.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
seaice_cost_accumulate_mean.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
seaice_cost_accumulate_mean.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_cost_accumulate_mean.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h
seaice_cost_accumulate_mean.f: FCORI_MACROS.h GRID.h GRID_MACROS.h
seaice_cost_accumulate_mean.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
seaice_cost_accumulate_mean.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
seaice_cost_accumulate_mean.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
seaice_cost_accumulate_mean.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_cost_accumulate_mean.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_cost_accumulate_mean.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
seaice_cost_accumulate_mean.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_cost_accumulate_mean.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_cost_accumulate_mean.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_cost_accumulate_mean.f: SEAICE_SIZE.h SIZE.h TANPHIATU_MACROS.h
seaice_cost_accumulate_mean.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_cost_areasst.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_cost_areasst.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
seaice_cost_areasst.f: PACKAGES_CONFIG.h PARAMS.h SEAICE.h SEAICE_COST.h
seaice_cost_areasst.f: SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_cost_areasst.f: cal.h
seaice_cost_concentration.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_cost_concentration.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
seaice_cost_concentration.f: PACKAGES_CONFIG.h PARAMS.h SEAICE_OPTIONS.h
seaice_cost_concentration.f: SIZE.h cal.h
seaice_cost_driver.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_cost_driver.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
seaice_cost_driver.f: PACKAGES_CONFIG.h SEAICE_OPTIONS.h
seaice_cost_export.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_cost_export.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
seaice_cost_export.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
seaice_cost_export.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
seaice_cost_export.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
seaice_cost_export.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
seaice_cost_export.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
seaice_cost_export.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_cost_export.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_cost_export.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_cost_export.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_cost_export.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_COST.h
seaice_cost_export.f: SEAICE_OPTIONS.h SEAICE_SIZE.h SIZE.h TANPHIATU_MACROS.h
seaice_cost_export.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_cost_final.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_cost_final.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
seaice_cost_final.f: SEAICE_COST.h SEAICE_OPTIONS.h SEAICE_PARAMS.h
seaice_cost_final.f: SEAICE_SIZE.h SIZE.h
seaice_cost_init_fixed.f: /usr/include/stdc-predef.h AD_CONFIG.h
seaice_cost_init_fixed.f: CPP_EEMACROS.h CPP_EEOPTIONS.h CPP_OPTIONS.h
seaice_cost_init_fixed.f: DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
seaice_cost_init_fixed.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h
seaice_cost_init_fixed.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
seaice_cost_init_fixed.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
seaice_cost_init_fixed.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
seaice_cost_init_fixed.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
seaice_cost_init_fixed.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_cost_init_fixed.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_cost_init_fixed.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
seaice_cost_init_fixed.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_cost_init_fixed.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_cost_init_fixed.f: RECIP_HFACW_MACROS.h SEAICE_OPTIONS.h SIZE.h
seaice_cost_init_fixed.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_cost_init_fixed.f: YC_MACROS.h cal.h
seaice_cost_init_varia.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_cost_init_varia.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
seaice_cost_init_varia.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
seaice_cost_init_varia.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
seaice_cost_init_varia.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
seaice_cost_init_varia.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_cost_init_varia.f: MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
seaice_cost_init_varia.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
seaice_cost_init_varia.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
seaice_cost_init_varia.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_cost_init_varia.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
seaice_cost_init_varia.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
seaice_cost_init_varia.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
seaice_cost_init_varia.f: SEAICE_OPTIONS.h SIZE.h TANPHIATU_MACROS.h
seaice_cost_init_varia.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_cost_sensi.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_cost_sensi.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
seaice_cost_sensi.f: SEAICE_OPTIONS.h SIZE.h
seaice_cost_sss.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_cost_sss.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
seaice_cost_sss.f: SEAICE_OPTIONS.h SIZE.h cal.h
seaice_cost_sst.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_cost_sst.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
seaice_cost_sst.f: SEAICE_OPTIONS.h SIZE.h cal.h
seaice_cost_weights.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_cost_weights.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
seaice_cost_weights.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
seaice_cost_weights.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
seaice_cost_weights.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
seaice_cost_weights.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
seaice_cost_weights.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
seaice_cost_weights.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_cost_weights.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_cost_weights.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
seaice_cost_weights.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_cost_weights.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_cost_weights.f: RECIP_HFACW_MACROS.h SEAICE_COST.h SEAICE_OPTIONS.h
seaice_cost_weights.f: SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
seaice_cost_weights.f: XC_MACROS.h YC_MACROS.h
seaice_ctrl_map_ini.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_ctrl_map_ini.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
seaice_ctrl_map_ini.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
seaice_ctrl_map_ini.f: DYG_MACROS.h DYNVARS.h DYU_MACROS.h EEPARAMS.h
seaice_ctrl_map_ini.f: FCORI_MACROS.h FFIELDS.h GRID.h GRID_MACROS.h
seaice_ctrl_map_ini.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
seaice_ctrl_map_ini.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
seaice_ctrl_map_ini.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
seaice_ctrl_map_ini.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_ctrl_map_ini.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_ctrl_map_ini.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
seaice_ctrl_map_ini.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_ctrl_map_ini.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_ctrl_map_ini.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_ctrl_map_ini.f: SEAICE_SIZE.h SIZE.h TANPHIATU_MACROS.h
seaice_ctrl_map_ini.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_diagnostics_init.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_diagnostics_init.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
seaice_diagnostics_init.f: PACKAGES_CONFIG.h SEAICE_OPTIONS.h SEAICE_PARAMS.h
seaice_diagnostics_init.f: SEAICE_SIZE.h SEAICE_TRACER.h SIZE.h
seaice_diagnostics_state.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_diagnostics_state.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
seaice_diagnostics_state.f: PACKAGES_CONFIG.h PARAMS.h SEAICE.h
seaice_diagnostics_state.f: SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h
seaice_diagnostics_state.f: SEAICE_TRACER.h SIZE.h
seaice_diffusion.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_diffusion.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_diffusion.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_diffusion.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
seaice_diffusion.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
seaice_diffusion.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
seaice_diffusion.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
seaice_diffusion.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_diffusion.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
seaice_diffusion.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
seaice_diffusion.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SEAICE_OPTIONS.h
seaice_diffusion.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h TANPHIATU_MACROS.h
seaice_diffusion.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_do_ridging.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_do_ridging.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_do_ridging.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_do_ridging.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
seaice_do_ridging.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
seaice_do_ridging.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
seaice_do_ridging.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
seaice_do_ridging.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_do_ridging.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_do_ridging.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_do_ridging.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_do_ridging.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_do_ridging.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h TANPHIATU_MACROS.h
seaice_do_ridging.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_dynsolver.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_dynsolver.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_dynsolver.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_dynsolver.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h FFIELDS.h
seaice_dynsolver.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
seaice_dynsolver.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
seaice_dynsolver.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
seaice_dynsolver.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_dynsolver.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_dynsolver.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_dynsolver.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_dynsolver.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_dynsolver.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h SURFACE.h
seaice_dynsolver.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_dynsolver.f: YC_MACROS.h
seaice_evp.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_evp.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_evp.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
seaice_evp.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
seaice_evp.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_evp.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
seaice_evp.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_evp.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_evp.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_evp.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
seaice_evp.f: SEAICE.h SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_evp.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_fake.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_fake.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_fake.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
seaice_fake.f: DYU_MACROS.h EEPARAMS.h EXF_FIELDS.h EXF_OPTIONS.h EXF_PARAM.h
seaice_fake.f: FCORI_MACROS.h FFIELDS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
seaice_fake.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
seaice_fake.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
seaice_fake.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_fake.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_fake.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_fake.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
seaice_fake.f: SEAICE.h SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_fake.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_fgmres.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
seaice_fgmres.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_fgmres.f: CPP_OPTIONS.h EEPARAMS.h EESUPPORT.h PACKAGES_CONFIG.h
seaice_fgmres.f: SEAICE.h SEAICE_OPTIONS.h SEAICE_SIZE.h SIZE.h
seaice_freedrift.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_freedrift.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_freedrift.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_freedrift.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
seaice_freedrift.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
seaice_freedrift.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
seaice_freedrift.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
seaice_freedrift.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_freedrift.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
seaice_freedrift.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
seaice_freedrift.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SEAICE.h
seaice_freedrift.f: SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_freedrift.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_freedrift.f: YC_MACROS.h
seaice_get_dynforcing.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_get_dynforcing.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
seaice_get_dynforcing.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
seaice_get_dynforcing.f: DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
seaice_get_dynforcing.f: EEPARAMS.h EXF_FIELDS.h EXF_OPTIONS.h EXF_PARAM.h
seaice_get_dynforcing.f: FCORI_MACROS.h FFIELDS.h GRID.h GRID_MACROS.h
seaice_get_dynforcing.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
seaice_get_dynforcing.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
seaice_get_dynforcing.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
seaice_get_dynforcing.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_get_dynforcing.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_get_dynforcing.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
seaice_get_dynforcing.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_get_dynforcing.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_get_dynforcing.f: RECIP_HFACW_MACROS.h SEAICE_OPTIONS.h SEAICE_PARAMS.h
seaice_get_dynforcing.f: SEAICE_SIZE.h SIZE.h TANPHIATU_MACROS.h
seaice_get_dynforcing.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_growth.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_growth.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_growth.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
seaice_growth.f: DYU_MACROS.h EEPARAMS.h EXF_FIELDS.h EXF_OPTIONS.h
seaice_growth.f: EXF_PARAM.h FCORI_MACROS.h FFIELDS.h GRID.h GRID_MACROS.h
seaice_growth.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_growth.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
seaice_growth.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
seaice_growth.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_growth.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
seaice_growth.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_growth.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_growth.f: SEAICE_PARAMS.h SEAICE_SIZE.h SEAICE_TRACER.h SIZE.h
seaice_growth.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_growth_adx.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_growth_adx.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_growth_adx.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_growth_adx.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h EXF_FIELDS.h
seaice_growth_adx.f: EXF_OPTIONS.h EXF_PARAM.h FCORI_MACROS.h FFIELDS.h GRID.h
seaice_growth_adx.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
seaice_growth_adx.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
seaice_growth_adx.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
seaice_growth_adx.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_growth_adx.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_growth_adx.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_growth_adx.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_growth_adx.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_growth_adx.f: SEAICE_PARAMS.h SEAICE_SIZE.h SEAICE_TRACER.h SIZE.h
seaice_growth_adx.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_growth_adx.f: YC_MACROS.h
seaice_init_fixed.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_init_fixed.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_init_fixed.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_init_fixed.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h FFIELDS.h GRID.h
seaice_init_fixed.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
seaice_init_fixed.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
seaice_init_fixed.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
seaice_init_fixed.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_init_fixed.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_init_fixed.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_init_fixed.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_init_fixed.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_init_fixed.f: SEAICE_PARAMS.h SEAICE_SIZE.h SEAICE_TRACER.h SIZE.h
seaice_init_fixed.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_init_fixed.f: YC_MACROS.h
seaice_init_varia.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_init_varia.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_init_varia.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_init_varia.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
seaice_init_varia.f: FFIELDS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
seaice_init_varia.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_init_varia.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
seaice_init_varia.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
seaice_init_varia.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_init_varia.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
seaice_init_varia.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
seaice_init_varia.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SEAICE.h
seaice_init_varia.f: SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h
seaice_init_varia.f: SEAICE_TAVE.h SEAICE_TRACER.h SIZE.h TANPHIATU_MACROS.h
seaice_init_varia.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_itd_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_itd_pickup.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SEAICE.h
seaice_itd_pickup.f: SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_itd_redist.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_itd_redist.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SEAICE.h
seaice_itd_redist.f: SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_itd_remap.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_itd_remap.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
seaice_itd_remap.f: SEAICE.h SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h
seaice_itd_remap.f: SIZE.h
seaice_itd_sum.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_itd_sum.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SEAICE.h
seaice_itd_sum.f: SEAICE_OPTIONS.h SEAICE_SIZE.h SIZE.h
seaice_jacvec.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_jacvec.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_jacvec.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
seaice_jacvec.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
seaice_jacvec.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_jacvec.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
seaice_jacvec.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
seaice_jacvec.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_jacvec.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
seaice_jacvec.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_jacvec.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_jacvec.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h TANPHIATU_MACROS.h
seaice_jacvec.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_jfnk.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_jfnk.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_jfnk.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
seaice_jfnk.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
seaice_jfnk.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_jfnk.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
seaice_jfnk.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_jfnk.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_jfnk.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_jfnk.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
seaice_jfnk.f: SEAICE.h SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_jfnk.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_krylov.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_krylov.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_krylov.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
seaice_krylov.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
seaice_krylov.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_krylov.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
seaice_krylov.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
seaice_krylov.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_krylov.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
seaice_krylov.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_krylov.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_krylov.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h TANPHIATU_MACROS.h
seaice_krylov.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_lsr.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_lsr.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_lsr.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
seaice_lsr.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
seaice_lsr.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_lsr.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
seaice_lsr.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_lsr.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_lsr.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_lsr.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
seaice_lsr.f: SEAICE.h SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_lsr.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_map_thsice.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_map_thsice.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SEAICE.h
seaice_map_thsice.f: SEAICE_OPTIONS.h SEAICE_SIZE.h SIZE.h THSICE_OPTIONS.h
seaice_map_thsice.f: THSICE_VARS.h
seaice_mnc_init.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_mnc_init.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
seaice_mnc_init.f: SEAICE_OPTIONS.h SIZE.h
seaice_model.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_model.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_model.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
seaice_model.f: DYU_MACROS.h EEPARAMS.h EXF_FIELDS.h EXF_OPTIONS.h
seaice_model.f: FCORI_MACROS.h FFIELDS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
seaice_model.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
seaice_model.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
seaice_model.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_model.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_model.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_model.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
seaice_model.f: SEAICE.h SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h
seaice_model.f: SEAICE_TRACER.h SIZE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
seaice_model.f: XC_MACROS.h YC_MACROS.h
seaice_mom_advection.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_mom_advection.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
seaice_mom_advection.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
seaice_mom_advection.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
seaice_mom_advection.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
seaice_mom_advection.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_mom_advection.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
seaice_mom_advection.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
seaice_mom_advection.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
seaice_mom_advection.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_mom_advection.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
seaice_mom_advection.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
seaice_mom_advection.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
seaice_mom_advection.f: SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_mom_advection.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_mom_advection.f: YC_MACROS.h
seaice_monitor.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_monitor.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_monitor.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_monitor.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
seaice_monitor.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_monitor.f: MASKW_MACROS.h MONITOR.h PACKAGES_CONFIG.h PARAMS.h
seaice_monitor.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
seaice_monitor.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_monitor.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
seaice_monitor.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_monitor.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_monitor.f: SEAICE_PARAMS.h SEAICE_SIZE.h SEAICE_TRACER.h SIZE.h
seaice_monitor.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_monitor.f: YC_MACROS.h
seaice_monitor_ad.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_monitor_ad.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_monitor_ad.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_monitor_ad.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
seaice_monitor_ad.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
seaice_monitor_ad.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h MONITOR.h
seaice_monitor_ad.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
seaice_monitor_ad.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_monitor_ad.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_monitor_ad.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_monitor_ad.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_monitor_ad.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_monitor_ad.f: SEAICE_PARAMS.h SEAICE_SIZE.h SEAICE_TRACER.h SIZE.h
seaice_monitor_ad.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_monitor_ad.f: YC_MACROS.h
seaice_obcs_output.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_obcs_output.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
seaice_obcs_output.f: PACKAGES_CONFIG.h PARAMS.h SEAICE_OPTIONS.h SIZE.h
seaice_ocean_stress.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_ocean_stress.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
seaice_ocean_stress.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
seaice_ocean_stress.f: DYG_MACROS.h DYNVARS.h DYU_MACROS.h EEPARAMS.h
seaice_ocean_stress.f: FCORI_MACROS.h FFIELDS.h GRID.h GRID_MACROS.h
seaice_ocean_stress.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
seaice_ocean_stress.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
seaice_ocean_stress.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
seaice_ocean_stress.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_ocean_stress.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_ocean_stress.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
seaice_ocean_stress.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_ocean_stress.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_ocean_stress.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_ocean_stress.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h TANPHIATU_MACROS.h
seaice_ocean_stress.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_oceandrag_coeffs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_oceandrag_coeffs.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
seaice_oceandrag_coeffs.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
seaice_oceandrag_coeffs.f: DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
seaice_oceandrag_coeffs.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
seaice_oceandrag_coeffs.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
seaice_oceandrag_coeffs.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
seaice_oceandrag_coeffs.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
seaice_oceandrag_coeffs.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_oceandrag_coeffs.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_oceandrag_coeffs.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
seaice_oceandrag_coeffs.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_oceandrag_coeffs.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_oceandrag_coeffs.f: RECIP_HFACW_MACROS.h SEAICE_OPTIONS.h
seaice_oceandrag_coeffs.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_oceandrag_coeffs.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_oceandrag_coeffs.f: YC_MACROS.h
seaice_output.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_output.f: CPP_OPTIONS.h EEPARAMS.h EXF_FIELDS.h EXF_OPTIONS.h FFIELDS.h
seaice_output.f: PACKAGES_CONFIG.h PARAMS.h SEAICE.h SEAICE_OPTIONS.h
seaice_output.f: SEAICE_PARAMS.h SEAICE_SIZE.h SEAICE_TAVE.h SEAICE_TRACER.h
seaice_output.f: SIZE.h
seaice_preconditioner.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_preconditioner.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
seaice_preconditioner.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
seaice_preconditioner.f: DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
seaice_preconditioner.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
seaice_preconditioner.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
seaice_preconditioner.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
seaice_preconditioner.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
seaice_preconditioner.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_preconditioner.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_preconditioner.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
seaice_preconditioner.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_preconditioner.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_preconditioner.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_preconditioner.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_preconditioner.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_preconditioner.f: YC_MACROS.h
seaice_prepare_ridging.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_prepare_ridging.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
seaice_prepare_ridging.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
seaice_prepare_ridging.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
seaice_prepare_ridging.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
seaice_prepare_ridging.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_prepare_ridging.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
seaice_prepare_ridging.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
seaice_prepare_ridging.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_prepare_ridging.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_prepare_ridging.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
seaice_prepare_ridging.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_prepare_ridging.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_prepare_ridging.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_prepare_ridging.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_prepare_ridging.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_prepare_ridging.f: YC_MACROS.h
seaice_read_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_read_pickup.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
seaice_read_pickup.f: PACKAGES_CONFIG.h PARAMS.h SEAICE.h SEAICE_OPTIONS.h
seaice_read_pickup.f: SEAICE_PARAMS.h SEAICE_SIZE.h SEAICE_TRACER.h SIZE.h
seaice_readparms.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_readparms.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_readparms.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_readparms.f: DYU_MACROS.h EEPARAMS.h EXF_CONSTANTS.h FCORI_MACROS.h
seaice_readparms.f: GAD.h GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
seaice_readparms.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h MNC_PARAMS.h
seaice_readparms.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
seaice_readparms.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_readparms.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_readparms.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_readparms.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_readparms.f: RECIP_HFACW_MACROS.h SEAICE_OPTIONS.h SEAICE_PARAMS.h
seaice_readparms.f: SEAICE_SIZE.h SEAICE_TRACER.h SIZE.h TANPHIATU_MACROS.h
seaice_readparms.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_reg_ridge.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_reg_ridge.f: CPP_OPTIONS.h EEPARAMS.h EXF_FIELDS.h EXF_OPTIONS.h
seaice_reg_ridge.f: PACKAGES_CONFIG.h PARAMS.h SEAICE.h SEAICE_OPTIONS.h
seaice_reg_ridge.f: SEAICE_PARAMS.h SEAICE_SIZE.h SEAICE_TRACER.h SIZE.h
seaice_solve4temp.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_solve4temp.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
seaice_solve4temp.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
seaice_solve4temp.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h EXF_FIELDS.h
seaice_solve4temp.f: EXF_OPTIONS.h FCORI_MACROS.h FFIELDS.h GRID.h
seaice_solve4temp.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
seaice_solve4temp.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
seaice_solve4temp.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
seaice_solve4temp.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_solve4temp.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
seaice_solve4temp.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_solve4temp.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_solve4temp.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_solve4temp.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h TANPHIATU_MACROS.h
seaice_solve4temp.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
seaice_solve4temp_adx.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_solve4temp_adx.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
seaice_solve4temp_adx.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
seaice_solve4temp_adx.f: DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
seaice_solve4temp_adx.f: EEPARAMS.h EXF_FIELDS.h EXF_OPTIONS.h FCORI_MACROS.h
seaice_solve4temp_adx.f: FFIELDS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
seaice_solve4temp_adx.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
seaice_solve4temp_adx.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
seaice_solve4temp_adx.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
seaice_solve4temp_adx.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
seaice_solve4temp_adx.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
seaice_solve4temp_adx.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
seaice_solve4temp_adx.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
seaice_solve4temp_adx.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
seaice_solve4temp_adx.f: RECIP_HFACW_MACROS.h SEAICE.h SEAICE_OPTIONS.h
seaice_solve4temp_adx.f: SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_solve4temp_adx.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
seaice_solve4temp_adx.f: YC_MACROS.h
seaice_summary.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_summary.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
seaice_summary.f: SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_tracer_phys.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_tracer_phys.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DYNVARS.h EEPARAMS.h
seaice_tracer_phys.f: FFIELDS.h PACKAGES_CONFIG.h PARAMS.h SEAICE.h
seaice_tracer_phys.f: SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h
seaice_tracer_phys.f: SEAICE_TRACER.h SIZE.h
seaice_turnoff_io.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seaice_turnoff_io.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h
seaice_turnoff_io.f: SEAICE_OPTIONS.h SEAICE_PARAMS.h SEAICE_SIZE.h SIZE.h
seaice_write_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
seaice_write_pickup.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
seaice_write_pickup.f: PACKAGES_CONFIG.h PARAMS.h SEAICE.h SEAICE_OPTIONS.h
seaice_write_pickup.f: SEAICE_PARAMS.h SEAICE_SIZE.h SEAICE_TRACER.h SIZE.h
seawater.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
seawater.f: CPP_OPTIONS.h
set_defaults.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
set_defaults.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h SET_GRID.h
set_defaults.f: SIZE.h W2_EXCH2_SIZE.h
set_grid_factors.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
set_grid_factors.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
set_grid_factors.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
set_grid_factors.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
set_grid_factors.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
set_grid_factors.f: MASKS_MACROS.h MASKW_MACROS.h PARAMS.h RAS_MACROS.h
set_grid_factors.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
set_grid_factors.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
set_grid_factors.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
set_grid_factors.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
set_grid_factors.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
set_grid_factors.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
set_grid_factors.f: YC_MACROS.h
set_parms.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
set_parms.f: CPP_OPTIONS.h EEPARAMS.h EOS.h MOM_COMMON_OPTIONS.h MOM_VISC.h
set_parms.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
set_ref_state.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
set_ref_state.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
set_ref_state.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
set_ref_state.f: DYU_MACROS.h EEPARAMS.h EOS.h FCORI_MACROS.h GRID.h
set_ref_state.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
set_ref_state.f: MASKS_MACROS.h MASKW_MACROS.h PARAMS.h RAS_MACROS.h
set_ref_state.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
set_ref_state.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
set_ref_state.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
set_ref_state.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
set_ref_state.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
set_ref_state.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
set_write_global_fld.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
set_write_global_fld.f: CPP_EEOPTIONS.h
solve_for_pressure.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
solve_for_pressure.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
solve_for_pressure.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
solve_for_pressure.f: DYG_MACROS.h DYNVARS.h DYU_MACROS.h EEPARAMS.h
solve_for_pressure.f: FCORI_MACROS.h FFIELDS.h GRID.h GRID_MACROS.h
solve_for_pressure.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
solve_for_pressure.f: MASKS_MACROS.h MASKW_MACROS.h NH_VARS.h
solve_for_pressure.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
solve_for_pressure.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
solve_for_pressure.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
solve_for_pressure.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
solve_for_pressure.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
solve_for_pressure.f: RECIP_HFACW_MACROS.h SIZE.h SOLVE_FOR_PRESSURE.h
solve_for_pressure.f: SOLVE_FOR_PRESSURE3D.h SURFACE.h TANPHIATU_MACROS.h
solve_for_pressure.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
solve_pentadiagonal.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
solve_pentadiagonal.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h SIZE.h
solve_tridiagonal.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
solve_tridiagonal.f: CPP_OPTIONS.h EEPARAMS.h SIZE.h
solve_uv_tridiago.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
solve_uv_tridiago.f: CPP_OPTIONS.h EEPARAMS.h SIZE.h
state_summary.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
state_summary.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
state_summary.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
state_summary.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
state_summary.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
state_summary.f: MASKW_MACROS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
state_summary.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
state_summary.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
state_summary.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
state_summary.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
state_summary.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
stop_if_error.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
stop_if_error.f: EEPARAMS.h SIZE.h
submeso_calc_psi.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
submeso_calc_psi.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
submeso_calc_psi.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
submeso_calc_psi.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GMREDI.h
submeso_calc_psi.f: GMREDI_OPTIONS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
submeso_calc_psi.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
submeso_calc_psi.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
submeso_calc_psi.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
submeso_calc_psi.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
submeso_calc_psi.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
submeso_calc_psi.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
submeso_calc_psi.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
submeso_calc_psi.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
submeso_calc_psi.f: YC_MACROS.h
swfrac.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
swfrac.f: CPP_OPTIONS.h PACKAGES_CONFIG.h
taueddy_init_varia.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
taueddy_init_varia.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h FFIELDS.h
taueddy_init_varia.f: PARAMS.h SIZE.h
taueddy_tendency_apply.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
taueddy_tendency_apply.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
taueddy_tendency_apply.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
taueddy_tendency_apply.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
taueddy_tendency_apply.f: FCORI_MACROS.h FFIELDS.h GMREDI.h GMREDI_OPTIONS.h
taueddy_tendency_apply.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
taueddy_tendency_apply.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
taueddy_tendency_apply.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
taueddy_tendency_apply.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
taueddy_tendency_apply.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
taueddy_tendency_apply.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
taueddy_tendency_apply.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
taueddy_tendency_apply.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
taueddy_tendency_apply.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
taueddy_tendency_apply.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
temp_integrate.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
temp_integrate.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
temp_integrate.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
temp_integrate.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h
temp_integrate.f: GAD_OPTIONS.h GAD_SOM_VARS.h GRID.h GRID_MACROS.h
temp_integrate.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
temp_integrate.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
temp_integrate.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
temp_integrate.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
temp_integrate.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
temp_integrate.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
temp_integrate.f: RECIP_HFACW_MACROS.h RESTART.h SIZE.h TANPHIATU_MACROS.h
temp_integrate.f: TANPHIATV_MACROS.h TIMEAVE_OPTIONS.h TIMEAVE_STATV.h
temp_integrate.f: XC_MACROS.h YC_MACROS.h
the_main_loop.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
the_main_loop.f: CPP_OPTIONS.h EEPARAMS.h EXF_OPTIONS.h GAD_OPTIONS.h
the_main_loop.f: GMREDI_OPTIONS.h PACKAGES_CONFIG.h PARAMS.h SEAICE_OPTIONS.h
the_main_loop.f: SIZE.h
the_model_main.f: /usr/include/stdc-predef.h AD_CONFIG.h CPP_EEMACROS.h
the_model_main.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DYNVARS.h EEPARAMS.h
the_model_main.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h
thermodynamics.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thermodynamics.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
thermodynamics.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
thermodynamics.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h FFIELDS.h
thermodynamics.f: GAD.h GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
thermodynamics.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
thermodynamics.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
thermodynamics.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
thermodynamics.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
thermodynamics.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
thermodynamics.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
thermodynamics.f: RECIP_HFACW_MACROS.h RESTART.h SIZE.h SURFACE.h
thermodynamics.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
thermodynamics.f: YC_MACROS.h
thsice_advdiff.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_advdiff.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
thsice_advdiff.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
thsice_advdiff.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h
thsice_advdiff.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
thsice_advdiff.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
thsice_advdiff.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
thsice_advdiff.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
thsice_advdiff.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
thsice_advdiff.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
thsice_advdiff.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
thsice_advdiff.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
thsice_advdiff.f: TANPHIATV_MACROS.h THSICE_DEBUG.h THSICE_OPTIONS.h
thsice_advdiff.f: THSICE_PARAMS.h THSICE_SIZE.h THSICE_VARS.h XC_MACROS.h
thsice_advdiff.f: YC_MACROS.h
thsice_advection.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_advection.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
thsice_advection.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
thsice_advection.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GAD.h GAD_OPTIONS.h
thsice_advection.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
thsice_advection.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
thsice_advection.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
thsice_advection.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
thsice_advection.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
thsice_advection.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
thsice_advection.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
thsice_advection.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
thsice_advection.f: TANPHIATV_MACROS.h THSICE_OPTIONS.h THSICE_SIZE.h
thsice_advection.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h XC_MACROS.h
thsice_advection.f: YC_MACROS.h
thsice_albedo.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_albedo.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h THSICE_OPTIONS.h
thsice_albedo.f: THSICE_PARAMS.h
thsice_ave.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_ave.f: CPP_OPTIONS.h EEPARAMS.h FFIELDS.h PACKAGES_CONFIG.h PARAMS.h
thsice_ave.f: SIZE.h THSICE_OPTIONS.h THSICE_PARAMS.h THSICE_TAVE.h
thsice_ave.f: THSICE_VARS.h
thsice_balance_frw.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
thsice_balance_frw.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
thsice_balance_frw.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
thsice_balance_frw.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
thsice_balance_frw.f: FFIELDS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
thsice_balance_frw.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
thsice_balance_frw.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
thsice_balance_frw.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
thsice_balance_frw.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
thsice_balance_frw.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
thsice_balance_frw.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
thsice_balance_frw.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
thsice_balance_frw.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h THSICE_OPTIONS.h
thsice_balance_frw.f: THSICE_PARAMS.h THSICE_SIZE.h THSICE_VARS.h XC_MACROS.h
thsice_balance_frw.f: YC_MACROS.h
thsice_calc_thickn.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
thsice_calc_thickn.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
thsice_calc_thickn.f: PACKAGES_CONFIG.h SIZE.h THSICE_DEBUG.h THSICE_OPTIONS.h
thsice_calc_thickn.f: THSICE_PARAMS.h THSICE_SIZE.h
thsice_check.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_check.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
thsice_check.f: THSICE_OPTIONS.h THSICE_PARAMS.h THSICE_SIZE.h
thsice_check_conserv.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
thsice_check_conserv.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
thsice_check_conserv.f: PACKAGES_CONFIG.h SIZE.h THSICE_DEBUG.h
thsice_check_conserv.f: THSICE_OPTIONS.h THSICE_PARAMS.h THSICE_SIZE.h
thsice_check_conserv.f: THSICE_TAVE.h THSICE_VARS.h
thsice_cost_driver.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
thsice_cost_driver.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
thsice_cost_driver.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
thsice_cost_driver.f: DYG_MACROS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
thsice_cost_driver.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
thsice_cost_driver.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
thsice_cost_driver.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
thsice_cost_driver.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
thsice_cost_driver.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
thsice_cost_driver.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
thsice_cost_driver.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
thsice_cost_driver.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
thsice_cost_driver.f: TANPHIATV_MACROS.h THSICE_OPTIONS.h XC_MACROS.h
thsice_cost_driver.f: YC_MACROS.h
thsice_cost_final.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_cost_final.f: CPP_OPTIONS.h DYNVARS.h EEPARAMS.h PACKAGES_CONFIG.h
thsice_cost_final.f: PARAMS.h SIZE.h THSICE_OPTIONS.h THSICE_PARAMS.h
thsice_cost_init_varia.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
thsice_cost_init_varia.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
thsice_cost_init_varia.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
thsice_cost_init_varia.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
thsice_cost_init_varia.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
thsice_cost_init_varia.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
thsice_cost_init_varia.f: MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
thsice_cost_init_varia.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
thsice_cost_init_varia.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
thsice_cost_init_varia.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
thsice_cost_init_varia.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
thsice_cost_init_varia.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
thsice_cost_init_varia.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
thsice_cost_init_varia.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h
thsice_cost_init_varia.f: THSICE_OPTIONS.h XC_MACROS.h YC_MACROS.h
thsice_cost_test.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_cost_test.f: CPP_OPTIONS.h PACKAGES_CONFIG.h THSICE_OPTIONS.h
thsice_diagnostics_init.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
thsice_diagnostics_init.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
thsice_diagnostics_init.f: PACKAGES_CONFIG.h THSICE_OPTIONS.h THSICE_SIZE.h
thsice_diagnostics_state.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
thsice_diagnostics_state.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
thsice_diagnostics_state.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h THSICE_OPTIONS.h
thsice_diagnostics_state.f: THSICE_PARAMS.h THSICE_VARS.h
thsice_diffusion.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_diffusion.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
thsice_diffusion.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
thsice_diffusion.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
thsice_diffusion.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
thsice_diffusion.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
thsice_diffusion.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
thsice_diffusion.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
thsice_diffusion.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
thsice_diffusion.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
thsice_diffusion.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
thsice_diffusion.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h THSICE_OPTIONS.h
thsice_diffusion.f: THSICE_PARAMS.h THSICE_SIZE.h THSICE_VARS.h XC_MACROS.h
thsice_diffusion.f: YC_MACROS.h
thsice_do_advect.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_do_advect.f: CPP_OPTIONS.h EEPARAMS.h FFIELDS.h PACKAGES_CONFIG.h
thsice_do_advect.f: PARAMS.h SIZE.h THSICE_OPTIONS.h THSICE_PARAMS.h
thsice_do_advect.f: THSICE_SIZE.h THSICE_VARS.h
thsice_do_exch.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_do_exch.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
thsice_do_exch.f: THSICE_OPTIONS.h THSICE_PARAMS.h THSICE_VARS.h
thsice_extend.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_extend.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
thsice_extend.f: THSICE_DEBUG.h THSICE_OPTIONS.h THSICE_PARAMS.h THSICE_SIZE.h
thsice_get_bulkf.f: /usr/include/stdc-predef.h BULKF.h BULKF_PARAMS.h
thsice_get_bulkf.f: BULK_FORCE_OPTIONS.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_get_bulkf.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
thsice_get_bulkf.f: THSICE_OPTIONS.h
thsice_get_exf.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_get_exf.f: CPP_OPTIONS.h EEPARAMS.h EXF_CONSTANTS.h EXF_FIELDS.h
thsice_get_exf.f: EXF_OPTIONS.h EXF_PARAM.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
thsice_get_exf.f: THSICE_DEBUG.h THSICE_OPTIONS.h
thsice_get_ocean.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_get_ocean.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
thsice_get_ocean.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
thsice_get_ocean.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
thsice_get_ocean.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
thsice_get_ocean.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
thsice_get_ocean.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
thsice_get_ocean.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
thsice_get_ocean.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
thsice_get_ocean.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
thsice_get_ocean.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SEAICE.h
thsice_get_ocean.f: SEAICE_OPTIONS.h SEAICE_SIZE.h SIZE.h SURFACE.h
thsice_get_ocean.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h THSICE_OPTIONS.h
thsice_get_ocean.f: THSICE_SIZE.h THSICE_VARS.h XC_MACROS.h YC_MACROS.h
thsice_get_precip.f: /usr/include/stdc-predef.h BULKF.h BULKF_PARAMS.h
thsice_get_precip.f: BULK_FORCE_OPTIONS.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_get_precip.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
thsice_get_precip.f: SIZE.h THSICE_OPTIONS.h
thsice_get_velocity.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
thsice_get_velocity.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
thsice_get_velocity.f: PACKAGES_CONFIG.h PARAMS.h SEAICE.h SEAICE_OPTIONS.h
thsice_get_velocity.f: SEAICE_SIZE.h SIZE.h THSICE_OPTIONS.h
thsice_impl_temp.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_impl_temp.f: CPP_OPTIONS.h EEPARAMS.h FFIELDS.h PACKAGES_CONFIG.h
thsice_impl_temp.f: PARAMS.h SIZE.h THSICE_DEBUG.h THSICE_OPTIONS.h
thsice_impl_temp.f: THSICE_PARAMS.h THSICE_SIZE.h THSICE_VARS.h
thsice_ini_vars.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_ini_vars.f: CPP_OPTIONS.h EEPARAMS.h FFIELDS.h PACKAGES_CONFIG.h
thsice_ini_vars.f: PARAMS.h SIZE.h THSICE_OPTIONS.h THSICE_PARAMS.h
thsice_ini_vars.f: THSICE_VARS.h
thsice_init_fixed.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_init_fixed.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
thsice_init_fixed.f: SIZE.h THSICE_OPTIONS.h
thsice_main.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_main.f: CPP_OPTIONS.h EEPARAMS.h FFIELDS.h PACKAGES_CONFIG.h PARAMS.h
thsice_main.f: SIZE.h THSICE_OPTIONS.h THSICE_PARAMS.h THSICE_SIZE.h
thsice_main.f: THSICE_VARS.h
thsice_map_exf.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_map_exf.f: CPP_OPTIONS.h EEPARAMS.h EXF_CONSTANTS.h EXF_FIELDS.h
thsice_map_exf.f: EXF_OPTIONS.h EXF_PARAM.h FFIELDS.h PACKAGES_CONFIG.h
thsice_map_exf.f: PARAMS.h SIZE.h THSICE_OPTIONS.h
thsice_mnc_init.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_mnc_init.f: CPP_OPTIONS.h PACKAGES_CONFIG.h THSICE_OPTIONS.h
thsice_monitor.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_monitor.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
thsice_monitor.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
thsice_monitor.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
thsice_monitor.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
thsice_monitor.f: MASKW_MACROS.h MONITOR.h PACKAGES_CONFIG.h PARAMS.h
thsice_monitor.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
thsice_monitor.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
thsice_monitor.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
thsice_monitor.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
thsice_monitor.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
thsice_monitor.f: TANPHIATV_MACROS.h THSICE_OPTIONS.h THSICE_PARAMS.h
thsice_monitor.f: THSICE_VARS.h XC_MACROS.h YC_MACROS.h
thsice_output.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_output.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
thsice_output.f: THSICE_OPTIONS.h THSICE_PARAMS.h THSICE_TAVE.h THSICE_VARS.h
thsice_read_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
thsice_read_pickup.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
thsice_read_pickup.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h THSICE_OPTIONS.h
thsice_read_pickup.f: THSICE_PARAMS.h THSICE_VARS.h
thsice_readparms.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_readparms.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
thsice_readparms.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
thsice_readparms.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
thsice_readparms.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
thsice_readparms.f: MASKS_MACROS.h MASKW_MACROS.h MNC_PARAMS.h
thsice_readparms.f: PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
thsice_readparms.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
thsice_readparms.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
thsice_readparms.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
thsice_readparms.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
thsice_readparms.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
thsice_readparms.f: TANPHIATV_MACROS.h THSICE_OPTIONS.h THSICE_PARAMS.h
thsice_readparms.f: XC_MACROS.h YC_MACROS.h
thsice_reshape_layers.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
thsice_reshape_layers.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
thsice_reshape_layers.f: PACKAGES_CONFIG.h THSICE_OPTIONS.h THSICE_PARAMS.h
thsice_salt_plume.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_salt_plume.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
thsice_salt_plume.f: SIZE.h THSICE_OPTIONS.h THSICE_PARAMS.h
thsice_slab_ocean.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_slab_ocean.f: CPP_OPTIONS.h EEPARAMS.h FFIELDS.h PACKAGES_CONFIG.h
thsice_slab_ocean.f: PARAMS.h SIZE.h THSICE_OPTIONS.h THSICE_PARAMS.h
thsice_slab_ocean.f: THSICE_TAVE.h THSICE_VARS.h
thsice_solve4temp.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_solve4temp.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
thsice_solve4temp.f: THSICE_DEBUG.h THSICE_OPTIONS.h THSICE_PARAMS.h
thsice_step_fwd.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_step_fwd.f: CPP_OPTIONS.h EEPARAMS.h FFIELDS.h PACKAGES_CONFIG.h
thsice_step_fwd.f: PARAMS.h SIZE.h THSICE_DEBUG.h THSICE_OPTIONS.h
thsice_step_fwd.f: THSICE_PARAMS.h THSICE_SIZE.h THSICE_TAVE.h THSICE_VARS.h
thsice_step_temp.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_step_temp.f: CPP_OPTIONS.h EEPARAMS.h FFIELDS.h PACKAGES_CONFIG.h
thsice_step_temp.f: PARAMS.h SIZE.h THSICE_DEBUG.h THSICE_OPTIONS.h
thsice_step_temp.f: THSICE_PARAMS.h THSICE_SIZE.h THSICE_TAVE.h THSICE_VARS.h
thsice_turnoff_io.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
thsice_turnoff_io.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
thsice_turnoff_io.f: THSICE_OPTIONS.h THSICE_PARAMS.h
thsice_write_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
thsice_write_pickup.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h
thsice_write_pickup.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h THSICE_OPTIONS.h
thsice_write_pickup.f: THSICE_PARAMS.h THSICE_VARS.h
timeave_cumul_1k1t.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
timeave_cumul_1k1t.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h
timeave_cumul_1t.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
timeave_cumul_1t.f: EEPARAMS.h SIZE.h
timeave_cumul_1vfc.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
timeave_cumul_1vfc.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h
timeave_cumul_2v.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
timeave_cumul_2v.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
timeave_cumul_2v.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
timeave_cumul_2v.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
timeave_cumul_2v.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
timeave_cumul_2v.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
timeave_cumul_2v.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
timeave_cumul_2v.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
timeave_cumul_2v.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
timeave_cumul_2v.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
timeave_cumul_2v.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
timeave_cumul_2v.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h TIMEAVE_OPTIONS.h
timeave_cumul_2v.f: XC_MACROS.h YC_MACROS.h
timeave_cumul_2vfc.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
timeave_cumul_2vfc.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h
timeave_cumul_dif_1t.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
timeave_cumul_dif_1t.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
timeave_cumul_dif_1t.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
timeave_cumul_dif_1t.f: DYF_MACROS.h DYG_MACROS.h DYU_MACROS.h EEPARAMS.h
timeave_cumul_dif_1t.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
timeave_cumul_dif_1t.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
timeave_cumul_dif_1t.f: MASKW_MACROS.h PACKAGES_CONFIG.h RAS_MACROS.h
timeave_cumul_dif_1t.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
timeave_cumul_dif_1t.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
timeave_cumul_dif_1t.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
timeave_cumul_dif_1t.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
timeave_cumul_dif_1t.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
timeave_cumul_dif_1t.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
timeave_cumul_dif_1t.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h
timeave_cumul_dif_1t.f: TIMEAVE_OPTIONS.h XC_MACROS.h YC_MACROS.h
timeave_cumulate.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
timeave_cumulate.f: EEPARAMS.h SIZE.h
timeave_init_fixed.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
timeave_init_fixed.f: CPP_EEOPTIONS.h CPP_OPTIONS.h EEPARAMS.h MNC_PARAMS.h
timeave_init_fixed.f: PACKAGES_CONFIG.h PARAMS.h SIZE.h TIMEAVE_OPTIONS.h
timeave_norma_2v.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
timeave_norma_2v.f: EEPARAMS.h SIZE.h
timeave_normalize.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
timeave_normalize.f: EEPARAMS.h SIZE.h
timeave_reset.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
timeave_reset.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
timeave_reset.f: TIMEAVE_OPTIONS.h
timeave_statv_write.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
timeave_statv_write.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
timeave_statv_write.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
timeave_statv_write.f: DYG_MACROS.h DYNVARS.h DYU_MACROS.h EEPARAMS.h
timeave_statv_write.f: FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
timeave_statv_write.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
timeave_statv_write.f: MASKW_MACROS.h MNC_PARAMS.h PACKAGES_CONFIG.h PARAMS.h
timeave_statv_write.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
timeave_statv_write.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
timeave_statv_write.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
timeave_statv_write.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
timeave_statv_write.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
timeave_statv_write.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
timeave_statv_write.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
timeave_statv_write.f: TANPHIATV_MACROS.h TIMEAVE_OPTIONS.h TIMEAVE_STATV.h
timeave_statv_write.f: XC_MACROS.h YC_MACROS.h
timeave_statvars.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
timeave_statvars.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
timeave_statvars.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
timeave_statvars.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
timeave_statvars.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
timeave_statvars.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
timeave_statvars.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
timeave_statvars.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
timeave_statvars.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
timeave_statvars.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
timeave_statvars.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
timeave_statvars.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h TIMEAVE_OPTIONS.h
timeave_statvars.f: TIMEAVE_STATV.h XC_MACROS.h YC_MACROS.h
timeave_surf_flux.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
timeave_surf_flux.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
timeave_surf_flux.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
timeave_surf_flux.f: DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
timeave_surf_flux.f: FFIELDS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
timeave_surf_flux.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
timeave_surf_flux.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
timeave_surf_flux.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
timeave_surf_flux.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
timeave_surf_flux.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
timeave_surf_flux.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
timeave_surf_flux.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
timeave_surf_flux.f: SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
timeave_surf_flux.f: TIMEAVE_OPTIONS.h TIMEAVE_STATV.h XC_MACROS.h YC_MACROS.h
timers.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h /usr/include/stdc-predef.h
timers.f: CPP_EEMACROS.h CPP_EEOPTIONS.h EEPARAMS.h EESUPPORT.h SIZE.h
timestep.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
timestep.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h
timestep.f: DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
timestep.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h HFACC_MACROS.h
timestep.f: HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h
timestep.f: NH_VARS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
timestep.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
timestep.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
timestep.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
timestep.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
timestep.f: RESTART.h SIZE.h SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
timestep.f: XC_MACROS.h YC_MACROS.h
timestep_tracer.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
timestep_tracer.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
timestep_tracer.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
timestep_tracer.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
timestep_tracer.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
timestep_tracer.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
timestep_tracer.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
timestep_tracer.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
timestep_tracer.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
timestep_tracer.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
timestep_tracer.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
timestep_tracer.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
timestep_tracer.f: YC_MACROS.h
timestep_wvel.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
timestep_wvel.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
timestep_wvel.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
timestep_wvel.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
timestep_wvel.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
timestep_wvel.f: MASKW_MACROS.h NH_VARS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
timestep_wvel.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
timestep_wvel.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
timestep_wvel.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
timestep_wvel.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
timestep_wvel.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
timestep_wvel.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
tracers_correction_step.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
tracers_correction_step.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DYNVARS.h EEPARAMS.h
tracers_correction_step.f: GAD.h PACKAGES_CONFIG.h PARAMS.h SIZE.h
tracers_iigw_correction.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
tracers_iigw_correction.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h
tracers_iigw_correction.f: DXF_MACROS.h DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h
tracers_iigw_correction.f: DYF_MACROS.h DYG_MACROS.h DYNVARS.h DYU_MACROS.h
tracers_iigw_correction.f: EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
tracers_iigw_correction.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
tracers_iigw_correction.f: MASKS_MACROS.h MASKW_MACROS.h NH_VARS.h PARAMS.h
tracers_iigw_correction.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
tracers_iigw_correction.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
tracers_iigw_correction.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
tracers_iigw_correction.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
tracers_iigw_correction.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
tracers_iigw_correction.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
tracers_iigw_correction.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
tracers_iigw_correction.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
turnoff_model_io.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
turnoff_model_io.f: CPP_OPTIONS.h EEPARAMS.h EXF_PARAM.h PACKAGES_CONFIG.h
turnoff_model_io.f: PARAMS.h SIZE.h
update_cg2d.f: /usr/include/stdc-predef.h CG2D.h CPP_EEMACROS.h
update_cg2d.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
update_cg2d.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h
update_cg2d.f: DYG_MACROS.h DYNVARS.h DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h
update_cg2d.f: GRID.h GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h
update_cg2d.f: HFACW_MACROS.h MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h
update_cg2d.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
update_cg2d.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
update_cg2d.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
update_cg2d.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
update_cg2d.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
update_cg2d.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
update_etah.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
update_etah.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
update_etah.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
update_etah.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
update_etah.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
update_etah.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
update_etah.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
update_etah.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
update_etah.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
update_etah.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
update_etah.f: SIZE.h SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
update_etah.f: XC_MACROS.h YC_MACROS.h
update_etaws.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
update_etaws.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
update_etaws.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
update_etaws.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
update_etaws.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
update_etaws.f: MASKW_MACROS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
update_etaws.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
update_etaws.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
update_etaws.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
update_etaws.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
update_etaws.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
update_masks_etc.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
update_masks_etc.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
update_masks_etc.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
update_masks_etc.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h
update_masks_etc.f: GRID_MACROS.h HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h
update_masks_etc.f: MASKS_MACROS.h MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h
update_masks_etc.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
update_masks_etc.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
update_masks_etc.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
update_masks_etc.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
update_masks_etc.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
update_masks_etc.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h
update_masks_etc.f: YC_MACROS.h
update_r_star.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
update_r_star.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
update_r_star.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
update_r_star.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
update_r_star.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
update_r_star.f: MASKW_MACROS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
update_r_star.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
update_r_star.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
update_r_star.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
update_r_star.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h SURFACE.h
update_r_star.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
update_sigma.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
update_sigma.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
update_sigma.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
update_sigma.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
update_sigma.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
update_sigma.f: MASKW_MACROS.h PACKAGES_CONFIG.h PARAMS.h RAS_MACROS.h
update_sigma.f: RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
update_sigma.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
update_sigma.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
update_sigma.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h
update_sigma.f: SIZE.h SURFACE.h TANPHIATU_MACROS.h TANPHIATV_MACROS.h
update_sigma.f: XC_MACROS.h YC_MACROS.h
update_surf_dr.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
update_surf_dr.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
update_surf_dr.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
update_surf_dr.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
update_surf_dr.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
update_surf_dr.f: MASKW_MACROS.h PARAMS.h RAS_MACROS.h RAW_MACROS.h
update_surf_dr.f: RA_MACROS.h RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h
update_surf_dr.f: RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h
update_surf_dr.f: RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h
update_surf_dr.f: RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
update_surf_dr.f: RECIP_HFACW_MACROS.h SIZE.h SURFACE.h TANPHIATU_MACROS.h
update_surf_dr.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
utils.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h EEPARAMS.h
utils.f: SIZE.h
w2_cumulsum_z_tile.f: /nasa/hpe/mpt/2.25_rhel79/include/mpif.h
w2_cumulsum_z_tile.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
w2_cumulsum_z_tile.f: CPP_EEOPTIONS.h CUMULSUM.h EEPARAMS.h EESUPPORT.h SIZE.h
w2_cumulsum_z_tile.f: W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
w2_cumulsum_z_tile.f: W2_OPTIONS.h
w2_e2setup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
w2_e2setup.f: EEPARAMS.h PACKAGES_CONFIG.h SIZE.h W2_EXCH2_PARAMS.h
w2_e2setup.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
w2_eeboot.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
w2_eeboot.f: EEPARAMS.h SIZE.h W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h
w2_eeboot.f: W2_EXCH2_TOPOLOGY.h
w2_map_procs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
w2_map_procs.f: EEPARAMS.h SIZE.h W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h
w2_map_procs.f: W2_EXCH2_TOPOLOGY.h
w2_print_comm_sequence.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
w2_print_comm_sequence.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_PARAMS.h
w2_print_comm_sequence.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
w2_print_e2setup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
w2_print_e2setup.f: EEPARAMS.h SIZE.h W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h
w2_print_e2setup.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
w2_readparms.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
w2_readparms.f: EEPARAMS.h SIZE.h W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h
w2_readparms.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
w2_set_cs6_facets.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
w2_set_cs6_facets.f: EEPARAMS.h SIZE.h W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h
w2_set_cs6_facets.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
w2_set_f2f_index.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
w2_set_f2f_index.f: EEPARAMS.h SIZE.h W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h
w2_set_f2f_index.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
w2_set_gen_facets.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
w2_set_gen_facets.f: EEPARAMS.h SIZE.h W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h
w2_set_gen_facets.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
w2_set_map_cumsum.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
w2_set_map_cumsum.f: EEPARAMS.h SIZE.h W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h
w2_set_map_cumsum.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
w2_set_map_tiles.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
w2_set_map_tiles.f: EEPARAMS.h SIZE.h W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h
w2_set_map_tiles.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
w2_set_myown_facets.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
w2_set_myown_facets.f: CPP_EEOPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h SIZE.h
w2_set_myown_facets.f: W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h
w2_set_myown_facets.f: W2_OPTIONS.h
w2_set_single_facet.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
w2_set_single_facet.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h W2_EXCH2_PARAMS.h
w2_set_single_facet.f: W2_EXCH2_SIZE.h W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
w2_set_tile2tiles.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
w2_set_tile2tiles.f: EEPARAMS.h SIZE.h W2_EXCH2_PARAMS.h W2_EXCH2_SIZE.h
w2_set_tile2tiles.f: W2_EXCH2_TOPOLOGY.h W2_OPTIONS.h
write_fld_3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_fld_3d_rl.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
write_fld_3d_rl.f: RW_OPTIONS.h SIZE.h
write_fld_3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_fld_3d_rs.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
write_fld_3d_rs.f: RW_OPTIONS.h SIZE.h
write_fld_s3d_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_fld_s3d_rl.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
write_fld_s3d_rl.f: RW_OPTIONS.h SIZE.h
write_fld_s3d_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_fld_s3d_rs.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
write_fld_s3d_rs.f: RW_OPTIONS.h SIZE.h
write_fld_xy_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_fld_xy_rl.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
write_fld_xy_rl.f: RW_OPTIONS.h SIZE.h
write_fld_xy_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_fld_xy_rs.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
write_fld_xy_rs.f: RW_OPTIONS.h SIZE.h
write_fld_xyz_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_fld_xyz_rl.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
write_fld_xyz_rl.f: RW_OPTIONS.h SIZE.h
write_fld_xyz_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_fld_xyz_rs.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
write_fld_xyz_rs.f: RW_OPTIONS.h SIZE.h
write_fullarray_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
write_fullarray_rl.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h
write_fullarray_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h
write_fullarray_rs.f: CPP_EEOPTIONS.h EEPARAMS.h SIZE.h
write_glvec_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_glvec_rl.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
write_glvec_rl.f: RW_OPTIONS.h SIZE.h
write_glvec_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_glvec_rs.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
write_glvec_rs.f: RW_OPTIONS.h SIZE.h
write_grid.f: /usr/include/stdc-predef.h AD_CONFIG.h CPP_EEMACROS.h
write_grid.f: CPP_EEOPTIONS.h CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h
write_grid.f: DXG_MACROS.h DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h
write_grid.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
write_grid.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
write_grid.f: MASKW_MACROS.h MNC_PARAMS.h PACKAGES_CONFIG.h PARAMS.h
write_grid.f: RAS_MACROS.h RAW_MACROS.h RA_MACROS.h RECIP_DXC_MACROS.h
write_grid.f: RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h RECIP_DXV_MACROS.h
write_grid.f: RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h RECIP_DYG_MACROS.h
write_grid.f: RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h RECIP_HFACS_MACROS.h
write_grid.f: RECIP_HFACW_MACROS.h SIZE.h TANPHIATU_MACROS.h
write_grid.f: TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
write_local_rl.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_local_rl.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
write_local_rl.f: RW_OPTIONS.h SIZE.h
write_local_rs.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_local_rs.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h
write_local_rs.f: RW_OPTIONS.h SIZE.h
write_pickup.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_pickup.f: CPP_OPTIONS.h DYNVARS.h EEPARAMS.h FFIELDS.h GAD.h
write_pickup.f: MNC_PARAMS.h NH_VARS.h PACKAGES_CONFIG.h PARAMS.h RESTART.h
write_pickup.f: SIZE.h SURFACE.h
write_rec.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_rec.f: CPP_OPTIONS.h EEPARAMS.h PACKAGES_CONFIG.h PARAMS.h RW_OPTIONS.h
write_rec.f: SIZE.h
write_state.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_state.f: CPP_OPTIONS.h DXC_MACROS.h DXF_MACROS.h DXG_MACROS.h
write_state.f: DXV_MACROS.h DYC_MACROS.h DYF_MACROS.h DYG_MACROS.h DYNVARS.h
write_state.f: DYU_MACROS.h EEPARAMS.h FCORI_MACROS.h GRID.h GRID_MACROS.h
write_state.f: HFACC_MACROS.h HFACS_MACROS.h HFACW_MACROS.h MASKS_MACROS.h
write_state.f: MASKW_MACROS.h MNC_PARAMS.h NH_VARS.h PACKAGES_CONFIG.h
write_state.f: PARAMS.h RAS_MACROS.h RAW_MACROS.h RA_MACROS.h
write_state.f: RECIP_DXC_MACROS.h RECIP_DXF_MACROS.h RECIP_DXG_MACROS.h
write_state.f: RECIP_DXV_MACROS.h RECIP_DYC_MACROS.h RECIP_DYF_MACROS.h
write_state.f: RECIP_DYG_MACROS.h RECIP_DYU_MACROS.h RECIP_HFACC_MACROS.h
write_state.f: RECIP_HFACS_MACROS.h RECIP_HFACW_MACROS.h SIZE.h
write_state.f: TANPHIATU_MACROS.h TANPHIATV_MACROS.h XC_MACROS.h YC_MACROS.h
write_utils.f: /usr/include/stdc-predef.h CPP_EEMACROS.h CPP_EEOPTIONS.h
write_utils.f: EEPARAMS.h SIZE.h
