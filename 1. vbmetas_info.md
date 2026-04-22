11:59:41 inscrutable@inscrutable Desktop → /home/inscrutable/android_development/los_22_2/external/avb/avbtool.py info_image --image /home/inscrutable/android_development/reference_devices/xiaomi_water/firmware/vbmeta.img
Minimum libavb version:   1.0
Header Block:             256 bytes
Authentication Block:     320 bytes
Auxiliary Block:          2752 bytes
Public key (sha1):        b2a02f1e56e366d727a1a8e089762fe0b91bbc84
Algorithm:                SHA256_RSA2048
Rollback Index:           0
Flags:                    0
Rollback Index Location:  0
Release String:           'avbtool 1.2.0'
Descriptors:
    Chain Partition descriptor:
      Partition Name:          boot
      Rollback Index Location: 3
      Public key (sha1):       b2a02f1e56e366d727a1a8e089762fe0b91bbc84
      Flags:                   0
    Chain Partition descriptor:
      Partition Name:          vbmeta_system
      Rollback Index Location: 2
      Public key (sha1):       b2a02f1e56e366d727a1a8e089762fe0b91bbc84
      Flags:                   0
    Chain Partition descriptor:
      Partition Name:          vbmeta_vendor
      Rollback Index Location: 4
      Public key (sha1):       b2a02f1e56e366d727a1a8e089762fe0b91bbc84
      Flags:                   0
    Prop: com.android.build.dtbo.fingerprint -> 'Redmi/water_global/water:12/SP1A.210812.016/V14.0.44.0.TGOMIXM:user/release-keys'
    Hash descriptor:
      Image Size:            75280 bytes
      Hash Algorithm:        sha256
      Partition Name:        dtbo
      Salt:                  0348bf53b630741be54950c3543096624dd8e32ce2ef4cf487b0722d4050338c
      Digest:                34590ca1557e09a2ce5e951d21de607fc6595c9e186ffc8a217e14b3b12d94c4
      Flags:                 0

12:00:46 inscrutable@inscrutable Desktop → /home/inscrutable/android_development/los_22_2/external/avb/avbtool.py info_image --image /home/inscrutable/android_development/reference_devices/xiaomi_water/firmware/vbmeta_system.img
Minimum libavb version:   1.0
Header Block:             256 bytes
Authentication Block:     320 bytes
Auxiliary Block:          1664 bytes
Public key (sha1):        b2a02f1e56e366d727a1a8e089762fe0b91bbc84
Algorithm:                SHA256_RSA2048
Rollback Index:           0
Flags:                    0
Rollback Index Location:  0
Release String:           'avbtool 1.2.0'
Descriptors:
    Prop: com.android.build.system.os_version -> '13'
    Prop: com.android.build.system.fingerprint -> 'Redmi/missi/missi:13/TP1A.220624.014/V14.0.44.0.TGOMIXM:user/release-keys'
    Prop: com.android.build.system.security_patch -> '2025-11-01'
    Prop: com.android.build.product.os_version -> '13'
    Prop: com.android.build.product.fingerprint -> 'Redmi/missi/missi:13/TP1A.220624.014/V14.0.44.0.TGOMIXM:user/release-keys'
    Prop: com.android.build.product.security_patch -> '2025-11-01'
    Hashtree descriptor:
      Version of dm-verity:  1
      Image Size:            1219424256 bytes
      Tree Offset:           1219424256
      Tree Size:             9609216 bytes
      Data Block Size:       4096 bytes
      Hash Block Size:       4096 bytes
      FEC num roots:         2
      FEC offset:            1229033472
      FEC size:              9715712 bytes
      Hash Algorithm:        sha256
      Partition Name:        product
      Salt:                  73c733b6fe37400e6e8fd5b7c20c7424f91d0c887cb974936a7bc092d1ea941f
      Root Digest:           00d06b6411443589c83f9e329c53fa0dbbf73042f998760f457de4f8dce2395e
      Flags:                 0
    Hashtree descriptor:
      Version of dm-verity:  1
      Image Size:            1545539584 bytes
      Tree Offset:           1545539584
      Tree Size:             12177408 bytes
      Data Block Size:       4096 bytes
      Hash Block Size:       4096 bytes
      FEC num roots:         2
      FEC offset:            1557716992
      FEC size:              12320768 bytes
      Hash Algorithm:        sha256
      Partition Name:        system
      Salt:                  e7d65c4dd0fe3dc02cc7e12607904c99fe60d16978ed57273ff88337b95a194f
      Root Digest:           65c221d0eb487f33d8300a59948f018c52529c79861b3f9a9b1236e48afc2e03
      Flags:                 0

12:01:14 inscrutable@inscrutable Desktop → /home/inscrutable/android_development/los_22_2/external/avb/avbtool.py info_image --image /home/inscrutable/android_development/reference_devices/xiaomi_water/firmware/vbmeta_vendor.img
Minimum libavb version:   1.0
Header Block:             256 bytes
Authentication Block:     320 bytes
Auxiliary Block:          1088 bytes
Public key (sha1):        b2a02f1e56e366d727a1a8e089762fe0b91bbc84
Algorithm:                SHA256_RSA2048
Rollback Index:           0
Flags:                    0
Rollback Index Location:  0
Release String:           'avbtool 1.2.0'
Descriptors:
    Prop: com.android.build.vendor.fingerprint -> 'Redmi/water_global/water:12/SP1A.210812.016/V14.0.44.0.TGOMIXM:user/release-keys'
    Prop: com.android.build.vendor.os_version -> '12'
    Prop: com.android.build.vendor.security_patch -> '2025-11-01'
    Hashtree descriptor:
      Version of dm-verity:  1
      Image Size:            180121600 bytes
      Tree Offset:           180121600
      Tree Size:             1425408 bytes
      Data Block Size:       4096 bytes
      Hash Block Size:       4096 bytes
      FEC num roots:         2
      FEC offset:            181547008
      FEC size:              1441792 bytes
      Hash Algorithm:        sha256
      Partition Name:        vendor
      Salt:                  2c5f8a8aecd83ab488666286062740fc29d3f2588c22690a8fe355fbd1fc2c46
      Root Digest:           48cb9e68b46328c7c113a47f7dd9e0710472677298c745b9c52b8bc295fe693f
      Flags:                 0
12:01:21 inscrutable@inscrutable Desktop →
