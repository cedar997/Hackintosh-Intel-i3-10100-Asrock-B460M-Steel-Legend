# Hackintosh-Intel-i3-10100-Asrock-B460M-Steel-Legend

# Info PC
```
Main: Asrock b460m steel legend
CPU: Intel® Core™ i3-10100
Ram: 16GB
VGA: UHD 630
PSU: 450W
SSD: Samsung 860 evo 
DISPLAY: hdmi 120hz lcd
```

# Thanks for 
- https://github.com/ducnm9/Hackintosh-Intel-i5-10400-Asrock-B460M-Steel-Legend
- But the hdmi port don't work well,so I fixed it use hackintools .

# Thing Works
- Onboard HDMI port 
- Sleep
- Wake
- Audio (select internal speakers)
- Ethernet
- All USB ports (Full 3.0 + 2.0 + type C)
# About this computer
![image](images/about.png)
# Fix NetWork
![image](images/net.png)

# Note For You
The file config.plist. Please change MLB, SystemSerialNumber, SystemUUID into your code

```
<dict>
    <key>AdviseWindows</key>
    <false/>
    <key>MLB</key>
    <string>xxxxxxxxxxxxxxx</string>
    <key>ROM</key>
    <data>ESIzRFVm</data>
    <key>SpoofVendor</key>
    <true/>
    <key>SystemProductName</key>
    <string>iMac19,1</string>
    <key>SystemSerialNumber</key>
    <string>xxxxxxxxxxx</string>
    <key>SystemUUID</key>
    <string>xxxxxxxx-xxxxx-xxxxx-xxxx-xxxxxxxx</string>
</dict>
```
