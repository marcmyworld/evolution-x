### Maintainer - @xeon_man


#### Dt source update : 26.09.2024

-   Fix VoNR ✅
-   Add Viper4AndroidFX
-   Add camera sensors to allowlist (fixes gpay qr not working) ✅
-   Remove micro distortions with Dolby
-   Implement a new Dolby multi device profile switching algorithm
-   Add Bokeh support in Leica Portrait modes
-   Fix VoIP audio management (call disconnect in whatsapp after 15 sec) ✅
-   Align status bar centrally with camera pill
-   Implement a possible Fix Bluetooth audio dropouts
-   Disable volume leveller by default

  

#### Dt source update : 19.09.2024

-   Add Enhanced HDR support
-   Improve auto brightness levels
-   Fix brightness suddenly changing
-   Fix the full slider brightness sudden jump

  

#### Dt source update : 14.09.2024

Based on initial trees by : @SMGReborn

Below are changes introduced by : @xeon_man aka marc

#### Display and Power

-   FIXED RANDOM REBOOT ✅
-   FIXED CRASHES IN WIFI/HOTSPOT ✅
-   FIXED BUG CHANGING COLOR PROFILES ✅
-   SMOOTH BRIGHTNESS SLIDER📱 - make slider match the 3000 nits brightness.
-   NEW Power profiles - install civi's power estimation map.
-   FIX Pixel Pitch to match the display.
-   FIX Secure NFC support for Indian devices.
-   Correct Fingerprint circle overlay
-   FIX Double tap to wake ✅
-   FIX Screen-off-fingerprint on display ✅

#### Multimedia

-   Add Spatial Audio - Externally add spatial audio support in audio poicy.
-   Add Supported codecs - install all the media codecs supported by device.
-   Add Advanced Dolby Atmos 🔉- professionally tuned and modified dolby version by @xeon_man

#### Radio Interface Layer

-   Improve Carrier services 📡️- reallocate the network reception configurations to match the device antennas
-   Fix Carrier Video Call 📺️- fix broken front camera in 4/5G video calls and other bugs.
-   New Wifi configuration 🛜 - change the wifi configuration to match the device.
-   Fix Location service 🌍 - fixed GNSS/GPS

#### Leica Camera

-   Front camera ✅
-   Pro | Video | Photo ✅
-   Portrait mode and (leica portrait / master portrait : swirly bokeh, soft focus) ✅
-   Dual Video | Pocket mirror ✅
-   Slow motion | Movie mode ✅
