# Asrock-B460M-Pro4-Hackintosh
The objective is to build a video editing and coding Hackintosh. Build must be able to use Airdrop, Continuity, Handoff and Airpods Pro seamlessly.

# Hardware
Part | Model
-----|------
CPU  | Intel Core I5 10500 ES
CPU Fan | Cooler Master i30
GPU | Intel UHD 630
Motherboard | Asrock B460M Pro4
Memory | ADATA 4GB DDR4 2666mhz x2
Storage | Sandisk 3D Utra 250GB
Network | Fenvi FV-T919
Casing | Tecware Nexus Air M2

# Not Working
- ~~HDMI Audio Output.~~ (fixed by patching the BusID)
- ~~App Store cause randomly log out system.~~ (Fixed after updated to Big Sur)
- ~~Sleep sometime will not able to wake.~~ (Fixed after updated to Big Sur)

# Opencore 0.6.8 + macOS Big Sur Version 11.3
* Opencore 0.6.8: [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
* macOS Big Sur Version 11.3

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
