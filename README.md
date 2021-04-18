# 10th-Gen-Intel-Core-i5-Hackintosh
The objective is to build a video editing and coding Hackintosh. Build must be able to use Airdrop, Continuity, Handoff and Airpods Pro seamlessly.

# Hardware
Part | Model
-----|------
CPU  | Intel Core I5 10500ES
CPU Fan | Cooler Master i30
GPU | Intel UHD 630
Motherboard | Asrock B460M Pro4
Memory | ADATA 4GB DDR4 2666mhz x2
Storage | Sandisk 3D Utra 250GB
Network | Fenvi FV-T919
Casing | Tecware Nexus Air M2

# Not Working
- HDMI Audio Output.
- App Store cause randomly log out system.
- Sleep sometime will not able to wake.

# Opencore 0.6.8 + macOS Catalina Version 10.15.7
* Opencore 0.6.8: [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
* macOS Catalina Version 10.15.7

# Replace the PlatformInfo
replace this part to your build.
```
<dict>
    <key>AdviseWindows</key>
    <false/>
    <key>MaxBIOSVersion</key>
    <false/>
    <key>MLB</key>
    <string>xxxxxxxxxxxxxxx</string>
    <key>ProcessorType</key>
    <integer>0</integer>
    <key>ROM</key>
    <data>ESIzRFVm</data>
    <key>SpoofVendor</key>
    <true/>
    <key>SystemMemoryStatus</key>
    <string>Auto</string>
    <key>SystemProductName</key>
    <string>iMac20,1</string>
    <key>SystemSerialNumber</key>
    <string>xxxxxxxxxxx</string>
    <key>SystemUUID</key>
    <string>xxxxxxxx-xxxxx-xxxxx-xxxx-xxxxxxxx</string>
</dict>
```
