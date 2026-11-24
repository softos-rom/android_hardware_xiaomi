# hardware/xiaomi

## Soong options

| Namespace | Variable | Description | Default |
| --------- | -------- | ----------- | ------- |
| XIAOMI_BIOMETRICS_FINGERPRINT | RUN_32BIT | Opt to run service in 32-bit mode only | false |
| XIAOMI_BIOMETRICS_FINGERPRINT | IMPL_VER | Fingerprint implementation version | V1 |
| XIAOMI_TOUCH | HIGH_TOUCH_POLLING_PATH | HighTouchPollingRate feature control path | |
| XIAOMI_TOUCH | KEY_DISABLER_CONTROL_PATH | KeyDisabler feature control path | |
| XIAOMI_TOUCH | KEY_SWAPPER_CONTROL_PATH | KeySwapper feature control path | |

## SoftOS fork

Fork of [xiaomi17-pudding-dev/android_hardware_xiaomi](https://github.com/xiaomi17-pudding-dev/android_hardware_xiaomi)
(`pudding/fingerprint-modules`, history kept; based on [LineageOS/android_hardware_xiaomi](https://github.com/LineageOS/android_hardware_xiaomi))
used by SoftOS for the Xiaomi 17 Pro Max (`popsicle`). Change: the `goodix_us2` ultrasonic fingerprint
module is added to the fingerprint HAL. Bu çatal SoftOS (Xiaomi 17 Pro Max) içindir. License: Apache-2.0.
