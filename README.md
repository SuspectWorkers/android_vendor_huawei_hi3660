# android_vendor_huawei_hi3660

Proprietary vendor blobs for Kirin 960 (`hi3660` / HUAWEI MediaPad M5 `CMR-W09`), adapted from `Huawei-Dev/android_vendor_huawei_hi3660` (`android@13`) for clean **AOSP 13** builds.

## Changes vs upstream

- Dropped prebuilt GrapheneOS `Camera` package from `hi3660-vendor.mk` (`vendor-hi3660-aosp.patch`) so the ROM builds cleanly with `GoogleCameraGo`.
- Paired with [`SuspectWorkers/aosp13-m5`](https://github.com/SuspectWorkers/aosp13-m5) and [`SuspectWorkers/android_device_huawei_hi3660`](https://github.com/SuspectWorkers/android_device_huawei_hi3660).
