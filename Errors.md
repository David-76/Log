FAILED: /home/david-black/twrp3/out/target/product/odin/obj/ETC/sepolicy_neverallows_intermediates/sepolicy_neverallows 
/bin/bash -c "(rm -f /home/david-black/twrp3/out/target/product/odin/obj/ETC/sepolicy_neverallows_intermediates/sepolicy_neverallows ) && (ASAN_OPTIONS=detect_leaks=0 /home/david-black/twrp3/out/host/linux-x86/bin/checkpolicy -M -c 		30 -o /home/david-black/twrp3/out/target/product/odin/obj/ETC/sepolicy_neverallows_intermediates/sepolicy_neverallows /home/david-black/twrp3/out/target/product/odin/obj/ETC/sepolicy_neverallows_intermediates/policy.conf )"
device/sony/fusion3-common/sepolicy/mediaserver.te:3:ERROR 'attribute hal_lineage_camera_motor_client is not declared' at token ';' on line 42272:
typeattribute mediaserver hal_lineage_camera_motor_client;
#line 3
checkpolicy:  error(s) encountered while parsing configuration
