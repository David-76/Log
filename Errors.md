[ 61% 19326/31360] Install: /home/david-76/crdroid9/out/host/linux-x86/bin/tune2fs
[ 61% 19327/31360] //system/core/debuggerd:tombstoned clang++ tombstoned/tombstoned.cpp
FAILED: /home/david-76/crdroid9/out/soong/.intermediates/system/core/debuggerd/tombstoned/android_arm_armv7-a-neon_krait_core/obj/system/core/debuggerd/tombstoned/tombstoned.o 
PWD=/proc/self/cwd /usr/bin/ccache prebuilts/clang/host/linux-x86/clang-4691093/bin/clang++ -c -Isystem/core/debuggerd/include -Isystem/core/debuggerd -mthumb -Os -fomit-frame-pointer -DANDROID -fmessage-length=0 -W -Wall -Wno-unused -Winit-self -Wpointer-arith -no-canonical-prefixes -DNDEBUG -UDEBUG -fno-exceptions -Wno-multichar -O2 -g -fno-strict-aliasing -fdebug-prefix-map=/proc/self/cwd= -D__compiler_offsetof=__builtin_offsetof -Werror=int-conversion -Wno-reserved-id-macro -Wno-format-pedantic -Wno-unused-command-line-argument -fcolor-diagnostics -Wno-expansion-to-defined -Wno-zero-as-null-pointer-constant -fdebug-prefix-map=$PWD/= -ffunction-sections -fdata-sections -fno-short-enums -funwind-tables -fstack-protector-strong -Wa,--noexecstack -D_FORTIFY_SOURCE=2 -Wstrict-aliasing=2 -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Werror=date-time -Werror=format-security -nostdlibinc -msoft-float -march=armv7-a -mfloat-abi=softfp -mfpu=neon -mcpu=krait -mfpu=neon-vfpv4 -D__ARM_FEATURE_LPAE=1 -Isystem/core/debuggerd/common/include -Isystem/core/base/include -Isystem/core/libcutils/include -Iexternal/libevent/include -Isystem/core/liblog/include -Iexternal/libcxx/include -Iexternal/libcxxabi/include -Ibionic/libc/system_properties/include -Isystem/core/property_service/libpropertyinfoparser/include -Isystem/core/include -Isystem/media/audio/include -Ihardware/libhardware/include -Ihardware/libhardware_legacy/include -Ihardware/ril/include -Ilibnativehelper/include -Iframeworks/native/include -Iframeworks/native/opengl/include -Iframeworks/av/include -isystem bionic/libc/include -isystem bionic/libc/kernel/uapi -isystem bionic/libc/kernel/uapi/asm-arm -isystem bionic/libc/kernel/android/scsi -isystem bionic/libc/kernel/android/uapi -Ilibnativehelper/include_jni -Wall -Wextra -Werror -Wno-unused-argument -Wno-unused-function -Wno-nullability-completeness -Os -target arm-linux-androideabi -Bprebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/arm-linux-androideabi/bin -DANDROID_STRICT -fPIE -D_USING_LIBCXX -std=gnu++1z -Wsign-promo -Wno-inconsistent-missing-override -Wno-null-dereference -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS -Wno-thread-safety-negative -Wno-gnu-include-next -fvisibility-inlines-hidden -fno-rtti  -Werror=int-to-pointer-cast -Werror=pointer-to-int-cast -Werror=address-of-temporary -Werror=return-type -Wno-tautological-constant-compare -Wno-null-pointer-arithmetic -Wno-enum-compare -Wno-enum-compare-switch -MD -MF /home/david-76/crdroid9/out/soong/.intermediates/system/core/debuggerd/tombstoned/android_arm_armv7-a-neon_krait_core/obj/system/core/debuggerd/tombstoned/tombstoned.o.d -o /home/david-76/crdroid9/out/soong/.intermediates/system/core/debuggerd/tombstoned/android_arm_armv7-a-neon_krait_core/obj/system/core/debuggerd/tombstoned/tombstoned.o system/core/debuggerd/tombstoned/tombstoned.cpp
system/core/debuggerd/tombstoned/tombstoned.cpp:115:92: error: 'openat' has superfluous mode bits; missing O_CREAT? [-Werror,-Wuser-defined-warnings]
    unique_fd result(openat(dir_fd_, ".", O_WRONLY | O_APPEND | O_TMPFILE | O_CLOEXEC, 0640));
                                                                                           ^
bionic/libc/include/bits/fortify/fcntl.h:91:9: note: from 'diagnose_if' attribute on 'openat':
        __clang_warning_if(!__open_modes_useful(flags) && modes,
        ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
bionic/libc/include/sys/cdefs.h:165:56: note: expanded from macro '__clang_warning_if'
#  define __clang_warning_if(cond, msg) __attribute__((diagnose_if(cond, msg, "warning")))
                                                       ^           ~~~~
1 error generated.
[ 61% 19328/31360] //system/timezone/tzdatacheck:tzdatacheck clang++ tzdatacheck.cpp
[ 61% 19329/31360] //external/e2fsprogs/misc:tune2fs clang tune2fs.c
[ 61% 19330/31360] //system/timezone/tzdatacheck:tzdatacheck clang++ tzdatacheck.cpp [linux_glibc]
[ 61% 19331/31360] target R.java/Manifest.java: Snap (/home/david-76/crdroid9/out/target/common/obj/APPS/Snap_intermediates/src/R.stamp)
warning: string 'pref_camera_flashmode_label' has no default translation.
[ 61% 19332/31360] AAPT2 link /home/david-76/crdroid9/out/target/product/odin/obj/APPS/Settings_intermediates/package-res.apk
packages/apps/crDroidSettings/res/layout/view_app_list.xml:24: warn: generated id 'android:id/icon' for external package 'android'.
packages/apps/crDroidSettings/res/layout/view_app_list.xml:51: warn: generated id 'android:id/message' for external package 'android'.
packages/apps/crDroidSettings/res/layout/view_app_list.xml:43: warn: generated id 'android:id/title' for external package 'android'.
packages/apps/crDroidSettings/res/layout/view_app_list.xml:17: warn: generated id 'android:id/widget_frame' for external package 'android'.
warn: removing resource com.android.settings:string/accent_amber without required default value.
warn: removing resource com.android.settings:string/accent_black without required default value.
warn: removing resource com.android.settings:string/accent_blue without required default value.
warn: removing resource com.android.settings:string/accent_brown without required default value.
warn: removing resource com.android.settings:string/accent_cyan without required default value.
warn: removing resource com.android.settings:string/accent_demon without required default value.
warn: removing resource com.android.settings:string/accent_denim without required default value.
warn: removing resource com.android.settings:string/accent_gold without required default value.
warn: removing resource com.android.settings:string/accent_green without required default value.
warn: removing resource com.android.settings:string/accent_grey without required default value.
warn: removing resource com.android.settings:string/accent_orange without required default value.
warn: removing resource com.android.settings:string/accent_oxygen without required default value.
warn: removing resource com.android.settings:string/accent_pink without required default value.
warn: removing resource com.android.settings:string/accent_purple without required default value.
warn: removing resource com.android.settings:string/accent_red without required default value.
warn: removing resource com.android.settings:string/accent_teal without required default value.
warn: removing resource com.android.settings:string/accent_turquoise without required default value.
warn: removing resource com.android.settings:string/accent_yellow without required default value.
warn: removing resource com.android.settings:string/berry_dark_shade_black without required default value.
warn: removing resource com.android.settings:string/berry_dark_shade_stock without required default value.
warn: removing resource com.android.settings:string/berry_dark_shade_title without required default value.
warn: removing resource com.android.settings:string/display_cutout_emulation_none without required default value.
warn: removing resource com.android.settings:string/fab_reset without required default value.
warn: removing resource com.android.settings:string/force_ambient_for_media_off without required default value.
warn: removing resource com.android.settings:string/force_ambient_for_media_on without required default value.
warn: removing resource com.android.settings:string/force_ambient_for_media_on_forced without required default value.
warn: removing resource com.android.settings:string/force_ambient_for_media_on_forced_clean without required default value.
warn: removing resource com.android.settings:string/navabar_settings_summary without required default value.
warn: removing resource com.android.settings:string/style_accent_configuration_not_supported without required default value.
warn: removing resource com.android.settings:string/style_accent_configuration_positive without required default value.
warn: removing resource com.android.settings:string/style_accent_default_name without required default value.
warn: removing resource com.android.settings:string/style_accent_title without required default value.
warn: removing resource com.android.settings:string/style_automagic_description without required default value.
warn: removing resource com.android.settings:string/style_automagic_dialog_content without required default value.
warn: removing resource com.android.settings:string/style_automagic_dialog_positive without required default value.
warn: removing resource com.android.settings:string/style_automagic_title without required default value.
warn: removing resource com.android.settings:string/style_global_entry_app without required default value.
warn: removing resource com.android.settings:string/style_permission_error without required default value.
ninja: build stopped: subcommand failed.
00:47:03 ninja failed with: exit status 1

#### failed to build some targets (39:50 (mm:ss)) ####
