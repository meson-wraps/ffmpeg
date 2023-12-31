#### --- GENERATED --- ####

libavutil_sources = files(
  'adler32.c',
  'aes.c',
  'aes_ctr.c',
  'ambient_viewing_environment.c',
  'audio_fifo.c',
  'avstring.c',
  'avsscanf.c',
  'base64.c',
  'blowfish.c',
  'bprint.c',
  'buffer.c',
  'cast5.c',
  'camellia.c',
  'channel_layout.c',
  'cpu.c',
  'crc.c',
  'csp.c',
  'des.c',
  'detection_bbox.c',
  'dict.c',
  'display.c',
  'dovi_meta.c',
  'downmix_info.c',
  'encryption_info.c',
  'error.c',
  'eval.c',
  'fifo.c',
  'file.c',
  'file_open.c',
  'float_dsp.c',
  'fixed_dsp.c',
  'frame.c',
  'hash.c',
  'hdr_dynamic_metadata.c',
  'hdr_dynamic_vivid_metadata.c',
  'hmac.c',
  'hwcontext.c',
  'imgutils.c',
  'integer.c',
  'intmath.c',
  'lfg.c',
  'lls.c',
  'log.c',
  'log2_tab.c',
  'lzo.c',
  'mathematics.c',
  'mastering_display_metadata.c',
  'md5.c',
  'mem.c',
  'murmur3.c',
  'opt.c',
  'parseutils.c',
  'pixdesc.c',
  'pixelutils.c',
  'random_seed.c',
  'rational.c',
  'reverse.c',
  'rc4.c',
  'ripemd.c',
  'samplefmt.c',
  'sha.c',
  'sha512.c',
  'slicethread.c',
  'spherical.c',
  'stereo3d.c',
  'threadmessage.c',
  'time.c',
  'timecode.c',
  'tree.c',
  'twofish.c',
  'utils.c',
  'xga_font_data.c',
  'xtea.c',
  'tea.c',
  'tx.c',
  'tx_float.c',
  'tx_double.c',
  'tx_int32.c',
  'uuid.c',
  'version.c',
  'video_enc_params.c',
  'film_grain_params.c',
)

libavutil_headers = files(
  'adler32.h',
  'aes.h',
  'aes_ctr.h',
  'ambient_viewing_environment.h',
  'attributes.h',
  'audio_fifo.h',
  'avassert.h',
  'avstring.h',
  'avutil.h',
  'base64.h',
  'blowfish.h',
  'bprint.h',
  'bswap.h',
  'buffer.h',
  'cast5.h',
  'camellia.h',
  'channel_layout.h',
  'common.h',
  'cpu.h',
  'crc.h',
  'csp.h',
  'des.h',
  'detection_bbox.h',
  'dict.h',
  'display.h',
  'dovi_meta.h',
  'downmix_info.h',
  'encryption_info.h',
  'error.h',
  'eval.h',
  'fifo.h',
  'file.h',
  'frame.h',
  'hash.h',
  'hdr_dynamic_metadata.h',
  'hdr_dynamic_vivid_metadata.h',
  'hmac.h',
  'hwcontext.h',
  'hwcontext_cuda.h',
  'hwcontext_d3d11va.h',
  'hwcontext_drm.h',
  'hwcontext_dxva2.h',
  'hwcontext_qsv.h',
  'hwcontext_mediacodec.h',
  'hwcontext_opencl.h',
  'hwcontext_vaapi.h',
  'hwcontext_videotoolbox.h',
  'hwcontext_vdpau.h',
  'hwcontext_vulkan.h',
  'imgutils.h',
  'intfloat.h',
  'intreadwrite.h',
  'lfg.h',
  'log.h',
  'lzo.h',
  'macros.h',
  'mathematics.h',
  'mastering_display_metadata.h',
  'md5.h',
  'mem.h',
  'motion_vector.h',
  'murmur3.h',
  'opt.h',
  'parseutils.h',
  'pixdesc.h',
  'pixelutils.h',
  'pixfmt.h',
  'random_seed.h',
  'rc4.h',
  'rational.h',
  'replaygain.h',
  'ripemd.h',
  'samplefmt.h',
  'sha.h',
  'sha512.h',
  'spherical.h',
  'stereo3d.h',
  'threadmessage.h',
  'time.h',
  'timecode.h',
  'timestamp.h',
  'tree.h',
  'twofish.h',
  'uuid.h',
  'version.h',
  'video_enc_params.h',
  'xtea.h',
  'tea.h',
  'tx.h',
  'film_grain_params.h',
)

libavutil_optional_sources = {
  'cuda' : files('hwcontext_cuda.c'),
  'd3d11va' : files('hwcontext_d3d11va.c'),
  'dxva2' : files('hwcontext_dxva2.c'),
  'libdrm' : files('hwcontext_drm.c'),
  'macos_kperf' : files('macos_kperf.c'),
  'mediacodec' : files('hwcontext_mediacodec.c'),
  'opencl' : files('hwcontext_opencl.c'),
  'qsv' : files('hwcontext_qsv.c'),
  'vaapi' : files('hwcontext_vaapi.c'),
  'vdpau' : files('hwcontext_vdpau.c'),
  'videotoolbox' : files('hwcontext_videotoolbox.c'),
  'vulkan' : files('hwcontext_vulkan.c','hwcontext_stub.c'),
}

libavutil_x86asm_optional_sources = {
}

libavutil_armv5te_optional_sources = {
}

libavutil_armv6_optional_sources = {
}

libavutil_armv8_optional_sources = {
}

libavutil_neon_optional_sources = {
}

libavutil_vfp_optional_sources = {
}

libavutil_mmx_optional_sources = {
}

libavutil_shlib_optional_sources = {
}

libavutil_slib_optional_sources = {
}

libavutil_tests = [
  ['adler32', files('tests/adler32.c')],
  ['aes', files('tests/aes.c')],
  ['aes_ctr', files('tests/aes_ctr.c')],
  ['audio_fifo', files('tests/audio_fifo.c')],
  ['avstring', files('tests/avstring.c')],
  ['base64', files('tests/base64.c')],
  ['blowfish', files('tests/blowfish.c')],
  ['bprint', files('tests/bprint.c')],
  ['cast5', files('tests/cast5.c')],
  ['camellia', files('tests/camellia.c')],
  ['channel_layout', files('tests/channel_layout.c')],
  ['color_utils', files('tests/color_utils.c')],
  ['cpu', files('tests/cpu.c')],
  ['crc', files('tests/crc.c')],
  ['des', files('tests/des.c')],
  ['dict', files('tests/dict.c')],
  ['display', files('tests/display.c')],
  ['encryption_info', files('tests/encryption_info.c')],
  ['error', files('tests/error.c')],
  ['eval', files('tests/eval.c')],
  ['file', files('tests/file.c')],
  ['fifo', files('tests/fifo.c')],
  ['hash', files('tests/hash.c')],
  ['hmac', files('tests/hmac.c')],
  ['hwdevice', files('tests/hwdevice.c')],
  ['integer', files('tests/integer.c')],
  ['imgutils', files('tests/imgutils.c')],
  ['lfg', files('tests/lfg.c')],
  ['lls', files('tests/lls.c')],
  ['log', files('tests/log.c')],
  ['md5', files('tests/md5.c')],
  ['murmur3', files('tests/murmur3.c')],
  ['opt', files('tests/opt.c')],
  ['pca', files('tests/pca.c')],
  ['parseutils', files('tests/parseutils.c')],
  ['pixdesc', files('tests/pixdesc.c')],
  # MANUAL ['pixelutils', files('tests/pixelutils.c')],
  ['pixfmt_best', files('tests/pixfmt_best.c')],
  ['random_seed', files('tests/random_seed.c')],
  ['rational', files('tests/rational.c')],
  ['ripemd', files('tests/ripemd.c')],
  ['sha', files('tests/sha.c')],
  ['sha512', files('tests/sha512.c')],
  ['softfloat', files('tests/softfloat.c')],
  ['tree', files('tests/tree.c')],
  ['twofish', files('tests/twofish.c')],
  # MANUAL ['utf8', files('tests/utf8.c')],
  ['uuid', files('tests/uuid.c')],
  ['xtea', files('tests/xtea.c')],
  ['tea', files('tests/tea.c')],
]

libavutil_optional_tests = {
  # This test is meant to be run manually (it uses argv unchecked)
  # 'lzo1x_999_compress' : [
  #   ['lzo', files('tests/lzo.c'), {
  #     'extra_libs': ['lzo2'], # MANUAL
  #   }],
  # ],
  'threads' : [
    ['cpu_init', files('tests/cpu_init.c'), {
      'extra_libs': ['threads'],  # MANUAL
    }],
  ],
  'pixelutils': [
    ['pixelutils', files('tests/pixelutils.c'), {}] # MANUAL
  ],
}

#### --- END GENERATED --- ####

install_headers(libavutil_headers, subdir: 'libavutil')

# Lavu configuration file
lavu_conf = configuration_data()
foreach config: have_list_pub
  lavu_conf.set('AV_HAVE_@0@'.format(config.to_upper()), conf.get(config.to_lower()))
endforeach

configure_file(
  output: 'avconfig.h',
  configuration: lavu_conf,
  install_dir: join_paths(get_option('includedir'), 'libavutil'),
  install: true,
)

kwargs = {'prefix': '#include "libavutil/version.h"'} + get_version_define_kwargs

libavutil_majorver = cc.get_define('LIBAVUTIL_VERSION_MAJOR', kwargs: kwargs)
minorver = cc.get_define('LIBAVUTIL_VERSION_MINOR', kwargs: kwargs)
microver = cc.get_define('LIBAVUTIL_VERSION_MICRO', kwargs: kwargs)

libavutil_version = f'@libavutil_majorver@.@minorver@.@microver@'

# Version file
ver_conf = configuration_data()
ver_conf.set('majorver', libavutil_majorver)
ver_conf.set('minorver', minorver)
ver_conf.set('microver', microver)

configure_file(
  input: 'libavutil.v.in',
  output: 'libavutil.ver',
  configuration: ver_conf,
)

ffversion_h = custom_target('ffversion.h',
  output: 'ffversion.h',
  build_always_stale: true,
  command: [
    find_program('version.py', required: true),
    '--git',
    find_program('git', required: true),
    meson.project_source_root(),
    '@OUTPUT@',
    ''
  ],
  build_by_default: true,
  install_dir: join_paths(get_option('includedir'), 'libavutil'),
  install: true,
)

subdir('aarch64')
subdir('arm')
subdir('x86')

libavutil_sources += compat_objs
