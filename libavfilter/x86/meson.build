#### --- GENERATED --- ####

libavfilter_x86_optional_sources = {
  'afir_filter' : files('af_afir_init.c'),
  'anlmdn_filter' : files('af_anlmdn_init.c'),
  'atadenoise_filter' : files('vf_atadenoise_init.c'),
  'blend_filter' : files('vf_blend_init.c'),
  'bwdif_filter' : files('vf_bwdif_init.c'),
  'colorspace_filter' : files('colorspacedsp_init.c'),
  'convolution_filter' : files('vf_convolution_init.c'),
  'eq_filter' : files('vf_eq_init.c'),
  'framerate_filter' : files('vf_framerate_init.c'),
  'fspp_filter' : files('vf_fspp_init.c'),
  'gblur_filter' : files('vf_gblur_init.c'),
  'gradfun_filter' : files('vf_gradfun_init.c'),
  'hflip_filter' : files('vf_hflip_init.c'),
  'hqdn3d_filter' : files('vf_hqdn3d_init.c'),
  'idet_filter' : files('vf_idet_init.c'),
  'interlace_filter' : files('vf_tinterlace_init.c'),
  'limiter_filter' : files('vf_limiter_init.c'),
  'lut3d_filter' : files('vf_lut3d_init.c'),
  'maskedclamp_filter' : files('vf_maskedclamp_init.c'),
  'maskedmerge_filter' : files('vf_maskedmerge_init.c'),
  'nlmeans_filter' : files('vf_nlmeans_init.c'),
  'noise_filter' : files('vf_noise.c'),
  'overlay_filter' : files('vf_overlay_init.c'),
  'pp7_filter' : files('vf_pp7_init.c'),
  'psnr_filter' : files('vf_psnr_init.c'),
  'pullup_filter' : files('vf_pullup_init.c'),
  'removegrain_filter' : files('vf_removegrain_init.c'),
  'scene_sad' : files('scene_sad_init.c'),
  'showcqt_filter' : files('avf_showcqt_init.c'),
  'spp_filter' : files('vf_spp.c'),
  'ssim_filter' : files('vf_ssim_init.c'),
  'stereo3d_filter' : files('vf_stereo3d_init.c'),
  'tblend_filter' : files('vf_blend_init.c'),
  'threshold_filter' : files('vf_threshold_init.c'),
  'tinterlace_filter' : files('vf_tinterlace_init.c'),
  'transpose_filter' : files('vf_transpose_init.c'),
  'v360_filter' : files('vf_v360_init.c'),
  'volume_filter' : files('af_volume_init.c'),
  'w3fdif_filter' : files('vf_w3fdif_init.c'),
  'yadif_filter' : files('vf_yadif_init.c'),
}

libavfilter_x86_x86asm_optional_sources = {
  'afir_filter' : files('af_afir.asm'),
  'anlmdn_filter' : files('af_anlmdn.asm'),
  'atadenoise_filter' : [], # MANUAL
  'blend_filter' : files('vf_blend.asm'),
  'bwdif_filter' : files('vf_bwdif.asm'),
  'colorspace_filter' : files('colorspacedsp.asm'),
  'convolution_filter' : files('vf_convolution.asm'),
  'eq_filter' : files('vf_eq.asm'),
  'framerate_filter' : files('vf_framerate.asm'),
  'fspp_filter' : files('vf_fspp.asm'),
  'gblur_filter' : files('vf_gblur.asm'),
  'gradfun_filter' : files('vf_gradfun.asm'),
  'hflip_filter' : files('vf_hflip.asm'),
  'hqdn3d_filter' : files('vf_hqdn3d.asm'),
  'idet_filter' : files('vf_idet.asm'),
  'interlace_filter' : files('vf_interlace.asm'),
  'limiter_filter' : files('vf_limiter.asm'),
  'lut3d_filter' : files('vf_lut3d.asm'),
  'maskedclamp_filter' : files('vf_maskedclamp.asm'),
  'maskedmerge_filter' : files('vf_maskedmerge.asm'),
  'nlmeans_filter' : [], # MANUAL
  'overlay_filter' : files('vf_overlay.asm'),
  'pp7_filter' : files('vf_pp7.asm'),
  'psnr_filter' : files('vf_psnr.asm'),
  'pullup_filter' : files('vf_pullup.asm'),
  'removegrain_filter' : files('vf_removegrain.asm'),
  'scene_sad' : files('scene_sad.asm'),
  'showcqt_filter' : files('avf_showcqt.asm'),
  'ssim_filter' : files('vf_ssim.asm'),
  'stereo3d_filter' : files('vf_stereo3d.asm'),
  'tblend_filter' : files('vf_blend.asm'),
  'threshold_filter' : files('vf_threshold.asm'),
  'tinterlace_filter' : files('vf_interlace.asm'),
  'transpose_filter' : files('vf_transpose.asm'),
  'v360_filter' : files('vf_v360.asm'),
  'volume_filter' : files('af_volume.asm'),
  'w3fdif_filter' : files('vf_w3fdif.asm'),
  'yadif_filter' : files('vf_yadif.asm','yadif-16.asm','yadif-10.asm'),
}

libavfilter_x86_armv5te_optional_sources = {
}

libavfilter_x86_armv6_optional_sources = {
}

libavfilter_x86_armv8_optional_sources = {
}

libavfilter_x86_neon_optional_sources = {
}

libavfilter_x86_vfp_optional_sources = {
}

libavfilter_x86_mmx_optional_sources = {
}

libavfilter_x86_shlib_optional_sources = {
}

libavfilter_x86_slib_optional_sources = {
}

libavfilter_x86_optional_tests = {
}

#### --- END GENERATED --- ####

# This file results in empty codegen and empty PDB generation otherwise.
# https://bugzilla.nasm.us/show_bug.cgi?id=3392738
# https://developercommunity.visualstudio.com/t/MSVC-Hangs-when-compiling-ffmpeg-When-l/10233953
if conf.get('x86_64', 0) == 1
  # Alternatively,
  # panic: ../libavcodec/x86/simple_idct10.asm: assertion cv8_state.source_files != NULL failed at output/codeview.c:512
  libavfilter_x86_x86asm_optional_sources += {
    'atadenoise_filter': libavfilter_x86_x86asm_optional_sources ['atadenoise_filter'] + files('vf_atadenoise.asm'),
  }
  libavfilter_x86_x86asm_optional_sources += {
    'nlmeans_filter': libavfilter_x86_x86asm_optional_sources ['nlmeans_filter'] + files('vf_nlmeans.asm'),
  }
endif
