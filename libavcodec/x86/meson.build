#### --- GENERATED --- ####

libavcodec_x86_sources = files(
  'constants.c',
)

libavcodec_x86_optional_sources = {
  'aac_decoder' : files('aacpsdsp_init.c','sbrdsp_init.c'),
  'aac_encoder' : files('aacencdsp_init.c'),
  'ac3dsp' : files('ac3dsp_init.c'),
  'adpcm_g722_decoder' : files('g722dsp_init.c'),
  'adpcm_g722_encoder' : files('g722dsp_init.c'),
  'alac_decoder' : files('alacdsp_init.c'),
  'apng_decoder' : files('pngdsp_init.c'),
  'audiodsp' : files('audiodsp_init.c'),
  'blockdsp' : files('blockdsp_init.c'),
  'bswapdsp' : files('bswapdsp_init.c'),
  'cavs_decoder' : files('cavsdsp.c'),
  'cfhd_decoder' : files('cfhddsp_init.c'),
  'cfhd_encoder' : files('cfhdencdsp_init.c'),
  'dca_decoder' : files('dcadsp_init.c','synth_filter_init.c'),
  'dct' : files('dct_init.c'),
  'dirac_decoder' : files('diracdsp_init.c','dirac_dwt_init.c'),
  'dnxhd_encoder' : files('dnxhdenc_init.c'),
  'exr_decoder' : files('exrdsp_init.c'),
  'fdctdsp' : files('fdctdsp_init.c'),
  'fft' : files('fft_init.c'),
  'flac_decoder' : files('flacdsp_init.c'),
  'flac_encoder' : files('flacencdsp_init.c'),
  'fmtconvert' : files('fmtconvert_init.c'),
  'h263dsp' : files('h263dsp_init.c'),
  'h264chroma' : files('h264chroma_init.c'),
  'h264dsp' : files('h264dsp_init.c'),
  'h264pred' : files('h264_intrapred_init.c'),
  'h264qpel' : files('h264_qpel.c'),
  'hevc_decoder' : files('hevcdsp_init.c'),
  'hpeldsp' : files('hpeldsp_init.c'),
  'huffyuvdsp' : files('huffyuvdsp_init.c'),
  'huffyuvencdsp' : files('huffyuvencdsp_init.c'),
  'idctdsp' : files('idctdsp_init.c'),
  'jpeg2000_decoder' : files('jpeg2000dsp_init.c'),
  'llauddsp' : files('lossless_audiodsp_init.c'),
  'llviddsp' : files('lossless_videodsp_init.c'),
  'llvidencdsp' : files('lossless_videoencdsp_init.c'),
  'lpc' : files('lpc_init.c'),
  'lscr_decoder' : files('pngdsp_init.c'),
  'me_cmp' : files('me_cmp_init.c'),
  'mlp_decoder' : files('mlpdsp_init.c'),
  'mpeg4_decoder' : files('mpeg4videodsp.c','xvididct_init.c'),
  'mpegaudiodsp' : files('mpegaudiodsp.c'),
  'mpegvideo' : files('mpegvideo.c'),
  'mpegvideoenc' : files('mpegvideoenc.c','mpegvideoencdsp_init.c'),
  'opus_decoder' : files('opusdsp_init.c'),
  'opus_encoder' : files('celt_pvq_init.c'),
  'pixblockdsp' : files('pixblockdsp_init.c'),
  'png_decoder' : files('pngdsp_init.c'),
  'prores_decoder' : files('proresdsp_init.c'),
  'prores_lgpl_decoder' : files('proresdsp_init.c'),
  'qpeldsp' : files('qpeldsp_init.c'),
  'rv34dsp' : files('rv34dsp_init.c'),
  'rv40_decoder' : files('rv40dsp_init.c'),
  'sbc_encoder' : files('sbcdsp_init.c'),
  'svq1_encoder' : files('svq1enc_init.c'),
  'tak_decoder' : files('takdsp_init.c'),
  'truehd_decoder' : files('mlpdsp_init.c'),
  'tta_decoder' : files('ttadsp_init.c'),
  'tta_encoder' : files('ttaencdsp_init.c'),
  'utvideo_decoder' : files('utvideodsp_init.c'),
  'v210_decoder' : files('v210-init.c'),
  'v210_encoder' : files('v210enc_init.c'),
  'vc1dsp' : files('vc1dsp_init.c'),
  'videodsp' : files('videodsp_init.c'),
  'vorbis_decoder' : files('vorbisdsp_init.c'),
  'vp3dsp' : files('vp3dsp_init.c'),
  'vp3_decoder' : files('hpeldsp_vp3_init.c'),
  'vp6_decoder' : files('vp6dsp_init.c'),
  'vp8dsp' : files('vp8dsp_init.c'),
  'vp9_decoder' : files('vp9dsp_init.c','vp9dsp_init_10bpp.c','vp9dsp_init_12bpp.c','vp9dsp_init_16bpp.c'),
  'webp_decoder' : files('vp8dsp_init.c'),
  'xmm_clobber_test' : files('w64xmmtest.c'),
}

libavcodec_x86_x86asm_optional_sources = {
  'aac_decoder' : files('aacpsdsp.asm','sbrdsp.asm'),
  'aac_encoder' : files('aacencdsp.asm'),
  'ac3dsp' : files('ac3dsp.asm','ac3dsp_downmix.asm'),
  'adpcm_g722_decoder' : files('g722dsp.asm'),
  'adpcm_g722_encoder' : files('g722dsp.asm'),
  'alac_decoder' : files('alacdsp.asm'),
  'apng_decoder' : files('pngdsp.asm'),
  'audiodsp' : files('audiodsp.asm'),
  'blockdsp' : files('blockdsp.asm'),
  'bswapdsp' : files('bswapdsp.asm'),
  'cavs_decoder' : files('cavsidct.asm'),
  'cfhd_decoder' : files('cfhddsp.asm'),
  'cfhd_encoder' : [], # MANUAL
  'dca_decoder' : files('dcadsp.asm','synth_filter.asm'),
  'dct' : files('dct32.asm'),
  'dirac_decoder' : files('diracdsp.asm','dirac_dwt.asm'),
  'dnxhd_encoder' : files('dnxhdenc.asm'),
  'exr_decoder' : files('exrdsp.asm'),
  'fft' : files('fft.asm'),
  'flac_decoder' : files('flacdsp.asm'),
  'flac_encoder' : files('flac_dsp_gpl.asm'),
  'fmtconvert' : files('fmtconvert.asm'),
  'h263dsp' : files('h263_loopfilter.asm'),
  'h264chroma' : files('h264_chromamc.asm','h264_chromamc_10bit.asm'),
  'h264dsp' : files('h264_deblock.asm','h264_deblock_10bit.asm','h264_idct.asm','h264_idct_10bit.asm','h264_weight.asm','h264_weight_10bit.asm'),
  'h264pred' : files('h264_intrapred.asm','h264_intrapred_10bit.asm'),
  'h264qpel' : files('h264_qpel_8bit.asm','h264_qpel_10bit.asm','fpel.asm','qpel.asm'),
  'hevc_decoder' : files('hevc_add_res.asm','hevc_deblock.asm','hevc_idct.asm','hevc_mc.asm','hevc_sao.asm','hevc_sao_10bit.asm'),
  'hpeldsp' : files('fpel.asm','hpeldsp.asm'),
  'huffyuvdsp' : files('huffyuvdsp.asm'),
  'huffyuvencdsp' : files('huffyuvencdsp.asm'),
  'idctdsp' : files('idctdsp.asm'), # MANUAL
  'jpeg2000_decoder' : files('jpeg2000dsp.asm'),
  'llauddsp' : files('lossless_audiodsp.asm'),
  'llviddsp' : files('lossless_videodsp.asm'),
  'llvidencdsp' : files('lossless_videoencdsp.asm'),
  'lpc' : files('lpc.asm'),
  'lscr_decoder' : files('pngdsp.asm'),
  'me_cmp' : files('me_cmp.asm'),
  'mlp_decoder' : [], # MANUAL 
  'mpeg4_decoder' : files('xvididct.asm'),
  'mpegaudiodsp' : files('imdct36.asm'),
  'mpegvideoenc' : files('mpegvideoencdsp.asm'),
  'opus_decoder' : files('opusdsp.asm'),
  'opus_encoder' : files('celt_pvq_search.asm'),
  'pixblockdsp' : files('pixblockdsp.asm'),
  'png_decoder' : files('pngdsp.asm'),
  'prores_decoder' : [], # MANUAL
  'prores_lgpl_decoder' : [], # MANUAL
  'qpeldsp' : files('qpeldsp.asm','fpel.asm','qpel.asm'),
  'rv34dsp' : files('rv34dsp.asm'),
  'rv40_decoder' : files('rv40dsp.asm'),
  'sbc_encoder' : files('sbcdsp.asm'),
  'svq1_encoder' : files('svq1enc.asm'),
  'tak_decoder' : files('takdsp.asm'),
  'truehd_decoder' : [], # MANUAL
  'tta_decoder' : files('ttadsp.asm'),
  'tta_encoder' : files('ttaencdsp.asm'),
  'utvideo_decoder' : files('utvideodsp.asm'),
  'v210_decoder' : files('v210.asm'),
  'v210_encoder' : files('v210enc.asm'),
  'vc1dsp' : files('vc1dsp_loopfilter.asm','vc1dsp_mc.asm'),
  'videodsp' : files('videodsp.asm'),
  'vorbis_decoder' : files('vorbisdsp.asm'),
  'vp3dsp' : files('vp3dsp.asm'),
  'vp3_decoder' : files('hpeldsp_vp3.asm'),
  'vp6_decoder' : files('vp6dsp.asm'),
  'vp8dsp' : files('vp8dsp.asm','vp8dsp_loopfilter.asm'),
  'vp9_decoder' : files('vp9intrapred.asm','vp9intrapred_16bpp.asm','vp9itxfm.asm','vp9itxfm_16bpp.asm','vp9lpf.asm','vp9lpf_16bpp.asm','vp9mc.asm','vp9mc_16bpp.asm'),
  'webp_decoder' : files('vp8dsp.asm'),
}

libavcodec_x86_armv5te_optional_sources = {
}

libavcodec_x86_armv6_optional_sources = {
}

libavcodec_x86_armv8_optional_sources = {
}

libavcodec_x86_neon_optional_sources = {
}

libavcodec_x86_vfp_optional_sources = {
}

libavcodec_x86_mmx_optional_sources = {
  'fdctdsp' : files('fdct.c'),
  'snow_decoder' : files('snowdsp.c'),
  'snow_encoder' : files('snowdsp.c'),
  'vc1dsp' : files('vc1dsp_mmx.c'),
}

libavcodec_x86_shlib_optional_sources = {
}

libavcodec_x86_slib_optional_sources = {
}

libavcodec_x86_optional_tests = {
}

#### --- END GENERATED --- ####

# This file results in empty codegen and empty PDB generation otherwise.
# https://bugzilla.nasm.us/show_bug.cgi?id=3392738
# https://developercommunity.visualstudio.com/t/MSVC-Hangs-when-compiling-ffmpeg-When-l/10233953
if conf.get('x86_32', 0) == 1
  libavcodec_x86_x86asm_optional_sources += {
    'idctdsp': libavcodec_x86_x86asm_optional_sources ['idctdsp'] + files('simple_idct.asm')
  }
elif conf.get('x86_64', 0) == 1
  # Alternatively,
  # panic: ../libavcodec/x86/simple_idct10.asm: assertion cv8_state.source_files != NULL failed at output/codeview.c:512
  libavcodec_x86_x86asm_optional_sources += {
    'idctdsp': libavcodec_x86_x86asm_optional_sources ['idctdsp'] + files('simple_idct10.asm'),
    'mlp_decoder': libavcodec_x86_x86asm_optional_sources ['mlp_decoder'] + files('mlpdsp.asm'),
    'cfhd_encoder': libavcodec_x86_x86asm_optional_sources ['cfhd_encoder'] + files('cfhdencdsp.asm'),
    'prores_decoder': libavcodec_x86_x86asm_optional_sources ['prores_decoder'] + files('proresdsp.asm'),
    'prores_lgpl_decoder': libavcodec_x86_x86asm_optional_sources ['prores_lgpl_decoder'] + files('proresdsp.asm'),
    'truehd_decoder': libavcodec_x86_x86asm_optional_sources ['truehd_decoder'] + files('mlpdsp.asm'),
  }
endif
