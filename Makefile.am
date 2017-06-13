SUBDIRS = webrtc

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = webrtc-audio-processing.pc

webrtcincludedir = $(includedir)/webrtc_audio_processing
nobase_webrtcinclude_HEADERS = webrtc/base/arraysize.h \
			       webrtc/base/checks.h \
			       webrtc/base/constructormagic.h \
			       webrtc/base/basictypes.h \
			       webrtc/base/maybe.h \
			       webrtc/base/platform_file.h \
			       webrtc/common.h \
			       webrtc/common_types.h \
			       webrtc/typedefs.h \
			       webrtc/modules/audio_processing/beamformer/array_util.h \
			       webrtc/modules/audio_processing/include/audio_processing.h \
			       webrtc/modules/interface/module_common_types.h \
			       webrtc/system_wrappers/include/trace.h \
						 webrtc/common_audio/channel_buffer.h \
						 webrtc/base/scoped_ptr.h \
						 webrtc/base/template_util.h \
						 webrtc/common_audio/include/audio_util.h \
						 webrtc/modules/audio_processing/beamformer/nonlinear_beamformer.h \
						 webrtc/common_audio/lapped_transform.h \
						 webrtc/common_audio/blocker.h \
						 webrtc/common_audio/audio_ring_buffer.h \
						 webrtc/common_audio/real_fourier.h \
						 webrtc/system_wrappers/include/aligned_malloc.h \
						 webrtc/system_wrappers/include/aligned_array.h \
						 webrtc/modules/audio_processing/beamformer/beamformer.h \
						 webrtc/modules/audio_processing/beamformer/complex_matrix.h \
						 webrtc/modules/audio_processing/beamformer/matrix.h \
						 webrtc/system_wrappers/include/scoped_vector.h \
						 webrtc/system_wrappers/include/stl_util.h

EXTRA_DIST = NEWS \
	     README.md \
	     UPDATING.md
