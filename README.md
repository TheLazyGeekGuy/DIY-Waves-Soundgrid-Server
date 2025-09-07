# SoundGrid Studio Update - November 2024
Waves has announced a major update for StudioRack and SoundGrid Studio, with significant changes affecting SoundGrid Studio. Notably, the SoundGrid server will no longer be supported in future versions of StudioRack. For full details, visit the official [announcement](https://www.waves.com/2024-update-studiorack-soundgrid-studio).
In short : Waves studio is no longer supported (Jun 2024)

# DIY Waves Soundgrid Server
This page is a compilation on what you'll find on [Groupdiy](https://groupdiy.com/threads/diy-compatible-waves-soundgrid-server.71385/) [GearSpace](https://gearspace.com/board/music-computers/1311451-diy-waves-soundgrid-server-2020-edition.html) thanks to `krabbencutter` or [facebook](https://www.facebook.com/groups/842878673081651) thanks to `Kalfelz Wusik William`.
No source code will be provided.

> # [SUBMIT A NEW CONFIGURATION HERE](https://github.com/TheLazyGeekGuy/DIY-Waves-Soundgrid-Server/issues/new?assignees=TheLazyGeekGuy&labels=enhancement&template=report-a-working-configuration.md&title=)

### [SoundGrid Certification Courses](https://www.waves.com/courses/soundgrid-certification-courses)
Please consider learning more about SoundGrid technologie
- **SoundGrid 101: Introduction to SoundGrid** : basics of Waves SoundGrid systems for real-time audio processing and networking.
- **SoundGrid 201: In-Depth Training** : in depth about Waves SoundGrid systems for real-time audio processing and networking.
- **SoundGrid 301: Advanced Training** : how to operate a Waves SoundGrid system more effectively, including troubleshooting basics.

And also buying more delicious [Waves Plugins](https://www.waves.com/plugins#sort:path~type~order=.default-order~number~asc|views:view=grid-view|paging:currentPage=0|paging:number=20)

## Configurations

### Configurations requirements
| Componant | |
|---- |---- |
| CPU | Intel CPU `only ` - i5 or i7 6th gen mininimum recommanded |
| RAM | 4Go |
| Network | Intel or Some Realtek - 1 Ethernet Port `only ` |
| Drive | USB Flash Drive[^warning] |

**NOT WORKING** :
- Non Intel CPU based configuration
- Non Intel or Some Realtek based NIC card

[^warning]: Dont connect any other drive than the flash drive. During firmware update, it could blank your whole drive ...
Exemple : Kingston DataTraveler DTSE9G2 32GB Memory Stick

### Waves

###### DISCLAIMER About waves configuration
All waves configuration tag price don't reflect only gear but also come with :
- professional support,
- Sturdy all-metal casing,
- Free 1-year warranty,
- Neutrik etherCon SoundGrid port connector for some units
- and more important all love from waves.

#### > Official configurations 2025
| Official / DIY | MotherBoard / Config Name | CPU | Form Factor |H-Reverb Test [^0]| Price / ratio [^7] |
|---- |---- |---- |---- |---- |---- |
| Official | Titan SoundGrid Server | Intel Core i9 | 2U rack | NA | $3999 / |
| Official | Titan-R SoundGrid Server | Intel Core i9 | 2U rack (redundant PSU) | NA | $4499 / |
| Official | Extreme-C SoundGrid Server | Intel i7-10700 | 2U half-rack | NA | $2399 / |
| Official | One-C SoundGrid Server | Intel i3-10300 | 2U half-rack | NA | $1799 / |
| Official | Proton Duo | Celeron J4125 (+ Axis Proton) | 1U half-rack | NA | $1299 / |

#### > Official configurations 2022
| Official / DIY | MotherBoard / Config Name | CPU | Form Factor |H-Reverb Test [^0]| Price / ratio [^7] |
|---- |---- |---- |---- |---- |---- |
| Official |NA QBI2145A[^15] |Celeron J4125 |---- |NA |$849 / |
| Official |Gigabyte mITX-4125A-WV[^12] |Celeron J4125 |---- |NA |$1299 / |
| Official |Gigabyte GA-IMB410N[^13] |i3 10300 |---- |NA |$1799 / |
| Official |Gigabyte GA-IMB410N[^14] |i7 10700 |---- |NA |$2399 / |
| Official |Gigabyte GA-IMB410N[^11] |i7 10700 |---- |NA |$2449 / |
| Official |Gigabyte W480M[^9] |i9 10900K |---- |NA |$3499 / |
| Official |Gigabyte W480M[^10] |i9 10900K |---- |NA |$3999 / |
| Official         |Gigabyte MH610FI-WV (custom)                 |i9 14900                              |----             |NA           |$4499 / |

[^9]: Titan SoundGrid Server [Specification](https://www.waves.com/hardware/titan-soundgrid-server)
[^10]: Titan-R SoundGrid Server [Specification](https://www.waves.com/hardware/titan-soundgrid-server)
[^11]: SoundGrid Extreme Server 2022 [Specification](https://www.waves.com/hardware/soundgrid-extreme-server#tab-tech-specs)
[^12]: Proton Duo 2022 [Specification](https://www.waves.com/hardware/proton-duo)
[^13]: SoundGrid Server One-C 2022 [Specification](https://www.waves.com/hardware/soundgrid-server-one-c)
[^14]: SoundGrid Extreme Server-C 2022 [Specification](https://www.waves.com/hardware/soundgrid-extreme-server-c#tab-tech-specs)
[^15]: SoundGrid Proton Server 2022 [Specification](https://www.waves.com/hardware/soundgrid-proton-server#tab-tech-specs)

#### > Legacy official configurations < 2022
| Official / DIY | MotherBoard / Config Name | CPU | Form Factor |H-Reverb Test [^0]| Price / ratio [^7] |
|---- |---- |---- |---- |---- |---- |
| Official |Polywell J4105AEL2[^1] |Celeron J4105 |---- |<6 (11034840) |$849 / 141|
| Official |Portwell Nano-6000C[^3] |i5 6200u |---- |6 (11034840) |$1299 / 216 |
| Official |Gigabyte GA-B150N-GSM [^2] |i5 |---- |12 (11034840) |$1799 / 149 |
| Official |Gigabyte GA-H81N [^4] |i5 4590K |---- |14 (11034840) |$2449 / 178 |
| Official |Gigabyte GA-B360N-GSM v1.0 [^5][^6] |i7 9700 |---- |14 (11034840) |$2399 / 171 |

[^1]: Proton Server [Specification](https://www.waves.com/1lib/pdf/hardware/proton-server-a-e-spec.pdf)
[^2]: Server One-C [Specification](https://www.waves.com/1lib/pdf/hardware/server-one-c-a-e-spec.pdf)
[^3]: Mobile Server
[^4]: Extreme Server [Specification](https://www.waves.com/hardware/soundgrid-extreme-server#tab-tech-specs)
[^5]: Impact Server C X9 [Specification](https://www.waves.com/1lib/pdf/hardware/extreme-server-c-x9-a-e-spec.pdf)
[^6]: Extreme Server-C : [Specification](https://www.waves.com/hardware/soundgrid-extreme-server-c#tab-tech-specs)

[^0]: check FAQ : "How do i mesure performance of my setup ? (H-Reverb Test)"
[^7]: ratio is (price list) / (H-reverb test result) = cost per H-reverb - lower is better
[^nic]: Intel Gigabit CT Desktop Adapter (supported nic)

### DIY configurations

#### Towers
| Official / DIY | MotherBoard / Config Name | CPU | Form Factor |H-Reverb Test [^0]| Price € / ratio [^7] |
|---- |---- |---- |---- |---- |---- |
| DIY |Acer N4660G |i7 8700 |---- |---- |---- |
| DIY |ASRock H110M DVS |i5 7400 |---- |---- |---- |
| DIY |ASRock H510M[^nic] |i7 11700K | ITX |---- |---- |
| DIY |ASUS B85 Plus |I5 4570 S | ITX |---- |---- |
| DIY |Asus P79 |i7 3930x |---- |---- |---- |
| DIY |Asus Z87-K C2 |i7 4770 |---- |11 |---- |
| DIY |Asus H81M-K motherboard |i7 4771 |---- |14 |---- |
| DIY |Dell T5500 |i7 4771 |---- |---- |---- |
| DIY |Dell PowerEdge T20 |Xeon E3 1225 v3 |---- |11 | 300 (2015) |
| DIY |Dell Optiplex 7060 |---- |---- |---- |---- |
| DIY |Dell Optiplex 3050 Micro |i5 7500T |---- |---- |---- |
| DIY |Gigabyte B365 |---- |---- |---- |---- |
| DIY |Gigabyte B365M DS3H |i7 9700K |---- |---- |---- |
| DIY |Gigabyte B365M WIFI-Y1-R |i7 9700 |---- |---- |---- |
| DIY |Gigabyte GA-H81M-S2PH |i5 4570 |---- |---- |---- |
| DIY |Gigabyte GA-H110TN |i7 6700 |---- |---- |---- |
| DIY |Gigabyte GA-H510M S2 V2 |i9 11900 |---- |20 | 800 (2022) / 40 |
| DIY |Gigabyte GA-B360N GSM / WiFi |i7 8700K |---- |---- |---- |
| DIY |Gigabyte b365m ds3h |i7 9700k |---- |---- |---- |
| DIY |Gigabyte b365m ds3h |i7 9700 |---- |---- |---- |
| DIY |Gigabyte IMB410TN |i7 8700 |---- |---- |---- |
| DIY |Gigabyte H410M S2H (r8169 NIC) |i5 10400 |---- |---- |---- |
| DIY |Gigabyte H270N |i7 7700K |---- |---- |---- |
| DIY |Gigabyte GA-Z170X-UD5 |i7 7500 |---- |---- |---- |
| DIY |Gigabyte Z370P D3 |i5 9600k |---- |---- |---- |
| DIY |Gigabyte z590I vision D |i9 10900K |---- |---- |---- |
| DIY |HP Z240 workstation |i7 6700 |---- |---- |---- |
| DIY |Gigabyte H470M DS3H (rev. 1.0) |i9 10900K | mATX |44 (14904840) |---- |
| DIY |ASUS PRIME H510M-A |i9 11900K | mATX |20 |---- |
| DIY |Asus H81T Mini-ITX |i7 4790K | ITX |5 (14.12.90.381 ~6 w/ minor glitches) |---- |

#### Rack server
| Official / DIY | MotherBoard / Config Name | CPU | Form Factor |H-Reverb Test [^0]| Price € / ratio [^7] |
|---- |---- |---- |---- |---- |---- |
| DIY |DELL R210 II |Xeon 1230 V2 |---- |---- |---- |

> Note R210 II: onboard Broadcom NICs are not compatible; add an Intel PRO/1000 PCIe card. On dual-port Intel cards, only the first port is recognized. Disable CPU Turbo in BIOS. [^r210ii_nic]

#### Mini / SFF / USFF Towers
| Official / DIY | MotherBoard / Config Name | CPU | Form Factor |H-Reverb Test [^0]| Price € / ratio [^7] |
|---- |---- |---- |---- |---- |---- |
| DIY |HP Elitedesk 600 G3 |i7 6500 |SFF |---- |---- |
| DIY |HP Elitedesk 600 G3 |i7 6700 |SFF |20 (11034440) |150 (2022) / 7.5 |
| DIY |HP Elitedesk 600 G3 |i7 7700 |SFF |22 (11034440) |160 (2022) / 7.27 |
| DIY |HP Elitedesk 800 G1 |i7 4790 |SFF |---- |---- |
| DIY |HP EliteDesk 800 G3 Mini |i5 7700 |USFF |---- |---- |
| DIY |HP Elitedesk 800 G5 |i5 9500T |---- |---- |---- |
| DIY |HP Elitedesk G2 |i5 6500T |---- |8 |---- |
| DIY |HP Z220 (C216 chipset) |i7 3770 |SFF |12 (12.8.0.320) |---- |
| DIY |Lenovo M93P tiny |i5 4570T |USFF |---- |---- |
| DIY |Lenovo ThinkCentre M910q Tiny |i5-6500T |USFF |---- |---- |
| DIY |Lenovo thinkcentre M900-tiny |i5 6500T |USFF |---- |---- |
| DIY |HP ProDesk 600 G3 |i5 6500T |SFF |25 |120 (2024) / ---- |
| DIY |HP EliteDesk 800 G5 SFF |i9 9900 |SFF |17 |650€ / ---- |
| DIY |HP EliteDesk 800 G3 Mini[^hp800g3_fan] |i7 6700 |USFF |---- (tested v14, v12) |210 USD / ---- |
| DIY |Dell OptiPlex 5000 Micro |i5 12500T |USFF |18 (V15) |600€ / ---- |
| DIY |LattePanda Delta 432[^unsupported_flag] |Celeron N4120 |USFF / SBC |n/a (14.26.104.721; upgrade ok to 15.1.163.206) |132.49€ / ---- |


### Bad ideas
- Virtualisation (Vmware ESXI or other virtualisation solution) : run but will also keep failing as the server need REALTIME usage, spend more time doing music geeks !
- Laptop server : Laptops are not designed to be servers. Soundgrid will definitely work but in the long run you will definitely have overheating/cooling issues as the server running the computer at fullspeed, it will make your computer die sooner ...

### WIP
- HP Elitedesk 400 G7 i5 10500 : NIC Intel® I219LM recognition failed

### Failed to work and will never be ...
| Official / DIY | MotherBoard / Config Name | CPU | Form Factor |H-Reverb Test [^0]| Price € / ratio [^7] |
|---- |---- |---- |---- |---- |---- |
| DIY |Apple Mac Mini |* |---- |---- |---- |
| DIY |MSI B450M Mortar Max |Ryzen 3 1200 |---- |---- |---- |
| DIY |MSI 790FX-GD70 |Phenom II X4 965 |---- |---- |---- |
| DIY |Lenovo Thinkstation P340 | |---- |---- |---- |
| DIY |MSI B450M Mortar Max |Ryzen 3 1200 |---- |---- |---- |

## NIC : compatible additional NIC Card Intel/Realtek
- Intel I210-T1 Ethernet Server Adapter - PCIe 2.1 lowprofil - around 60€
- Intel EXPI9402PT
- Intel Chipsets 000 series, I219V seem to work fine. Intel PCIe LAN card can work.
- Realtek 8111x should work (Success with 8111H and 8111B and R8169)
- On Dell R210 II, integrated Broadcom NICs are not compatible; use an Intel PRO/1000 PCIe card. On dual-port Intel cards, only the first port is recognized. [^r210ii_nic]
- Note: some DIY systems may appear as “Unsupported” in Waves software but still function (example: LattePanda Delta 432). [^unsupported_flag]

## FAQ

How do i check the CPU ?
I always take my [2013 CPU i7 4770](https://ark.intel.com/content/www/fr/fr/ark/products/75122/intel-core-i7-4770-processor-8m-cache-up-to-3-90-ghz.html)as reference. It always had decent results on reverb test [creamware pulsar saturation on PCI Bus before](https://www.forums.scopeusers.com/viewtopic.php?t=17078&start=460) with the same result : around 10/11 reverbs.
When i need to check the "brut power" of a CPU for reference, i google "i7 4770 vs The other one cpuboss" and check rapidely on some site like [CPU Boss](http://cpuboss.com/) for benchmarck comparison or [passmark comparison website](https://www.cpubenchmark.net/compare/).
I check to have at least the same as the i7 4770 (or almost equivalent : [i5 8500T](https://www.cpubenchmark.net/compare/Intel-Core-i5-8500T-vs-Intel-Core-i7-4770/3231vs1907), [i7 4790](https://www.cpubenchmark.net/compare/Intel-i5-8500T-vs-Intel-i7-4770-vs-Intel-i7-4790/3231vs1907vs2226) Avoid Celeron, Intel I3 or too old CPU (before 2013), and be carefull with the reference : i6500 is NOT the same as i6500T (or K, S, T, U ....)

Which motherboard ?
For a long time as reference (on planetz : [creamware user](https://www.forums.scopeusers.com/viewtopic.php?t=17078&start=460)) : ASUS or GIGABYTE where the most reliable choice for a music computer.

How do i mesure performance of my setup ? (H-Reverb Test)
One of the mesure of setup performance (and does not reflect the whole CPU capabilities - see "[CPU Performance vs. Real-Time Performance in Digital Audio Workstations (DAW)](https://www.youtube.com/watch?v=GUsLLEkswzE)" for full explanation), is to test the worst case scenario for plugins use : reverbs. Reverbs are often the most commun and worst for system resources.
This is why this is a commun reference.( see 2005 [Masterverb thread](https://forums.scopeusers.com/viewtopic.php?t=17078&sid=21d12edd7bac80c1b0427111224bc653))
A simple test you can do, as waves does :

### Test Version Result :
Exemple : H-reverb 20 (11034840) will refer to a studio rack test on Waves V11 @ 48Khz under a latency of 40

### Test Case
| Case | Main Soft | Sub soft | Comments |
|---- |---- |---- |---- |
| 01 |eMotion |LV1 |latency optimized mode |
| 02 |SuperRack |SoundGrid | |
| 03 |StudioRack |SoundGrid Studio |SoundGrid mode |

Source : [Waves](https://www.waves.com/compare-servers)  [Plugins latency](https://www.waves.com/support/tech-specs/plugin-latency)

### Test Itself
#### Case 3 StudioRack + SoundGrid Studio

## Notes & Footnotes (community)
[^r210ii_nic]: Dell R210 II: Broadcom onboard NICs not supported; add Intel PRO/1000 PCIe. Only the first port works on dual-port cards. Disable CPU Turbo in BIOS. (Ref: issue #18)
[^hp800g3_fan]: HP EliteDesk 800 G3 Mini can require a 10 kΩ resistor between GND and TACH to bypass the 901 external fan error when booting headless. (Ref: issue #27)
[^unsupported_flag]: Some DIY systems may show as “Unsupported” in Waves (LV1/SuperRack) but still work in practice (e.g., LattePanda Delta 432). (Ref: issues #22/#23)
