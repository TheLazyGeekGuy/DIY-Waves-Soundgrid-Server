# DIY Waves Soundgrid Server

This page is a compilation on what you'll find on GearSpace or facebook. 

## Configurations


### Configurations requirements

| Componant        |                                                             |
|----              |----                                                         |
| CPU              | Intel CPU `only ` - i5 or i7 6th gen mininimum recommanded  |
| RAM              | 8Go - no more needed                                        |
| Network          | Intel or Some Realtek - 1 Ethernet Port ``only ``           |
| Drive            | USB Flash Drive[^warning]                                   |


[^warning]: Dont connect any other drive than the flash drive. 
  During firmware update, it could blank your whole drive ...
  Exemple : Kingston DataTraveler DTSE9G2 32GB Memory Stick


### Waves official configurations 


| Official / DIY   | MotherBoard / Config Name                   | CPU                                  |   Form Factor  |H-Reverb Test | Price |
|----              |----                                         |----                                  |----            |----          |----   |
| Official         |Polywell J4105AEL2[^1]                       |Celeron J4105                         |----            |----          |----   |
| Official         |Gigabyte GA-B150N-GSM [^2]                   |i5                                    |----            |----          |----   |
| Official         |Portwell Nano-6000C[^3]                      |i5 6200u                              |----            |----          |----   |
| Official         |Gigabyte GA-H81N [^4]                        |i5 4590K                              |----            |14            |----   |
| Official         |Gigabyte GA-B360N-GSM v1.0 [^5]              |i7 9700                               |----            |----          |----   |


[^1]: Proton Server [Specification](https://www.waves.com/1lib/pdf/hardware/proton-server-a-e-spec.pdf) 
[^2]: Server One-C [Specification](https://www.waves.com/1lib/pdf/hardware/server-one-c-a-e-spec.pdf)
[^3]: Mobile Server 
[^4]: Extreme Server [Specification](https://www.waves.com/hardware/soundgrid-extreme-server#tab-tech-specs)
[^4]: Impact Server C X9 [Specification](https://www.waves.com/1lib/pdf/hardware/extreme-server-c-x9-a-e-spec.pdf)
[^5]: Extreme Server-C : [Specification](https://www.waves.com/hardware/soundgrid-extreme-server-c#tab-tech-specs)


### DIY configurations 

#### Towers

| Official / DIY   | MotherBoard / Config Name                      | CPU                               |   Form Factor  |H-Reverb Test | Price |
|----              |----                                            |----                               |----            |----          |----   |
| DIY              |Acer N4660G                                     |i7 8700                            |----            |----          |----   |
| DIY              |ASRock H110M DVS                                |i5 7400                            |----            |----          |----   |
| DIY              |Asus P79                                        |i7 3930x                           |----            |----          |----   |
| DIY              |Asus Z87-K C2                                   |i7 4770                            |----            |11            |----   |
| DIY              |Asus H81M-K motherboard                         |i7 4771                            |----            |14            |----   |
| DIY              |Dell T5500                                      |i7 4771                            |----            |----          |----   |
| DIY              |Dell PowerEdge T20                              |Xeon E3 1225 v3                    |----            |11L           |----   |
| DIY              |Dell Optiplex 7060                              |----                               |----            |----          |----   |
| DIY              |Dell Optiplex 3050 Micro                        |i5 7500T                           |----            |----          |----   |
| DIY              |Gigabyte B365                                   |----                               |----            |----          |----   |
| DIY              |Gigabyte B365M DS3H                             |i7 9700K                           |----            |----          |----   |
| DIY              |Gigabyte GA-H81M-S2PH                           |i5 4570                            |----            |----          |----   |
| DIY              |Gigabyte GA-H110TN                              |i7 6700                            |----            |----          |----   |
| DIY              |Gigabyte GA-B360N GSM / WiFi                    |i7 8700K                           |----            |----          |----   |
| DIY              |Gigabyte b365m ds3h                             |i7 9700k                           |----            |----          |----   |
| DIY              |Gigabyte b365m ds3h                             |i7 9700                            |----            |----          |----   |
| DIY              |Gigabyte H410M S2H                              |i5 10400                           |----            |----          |----   |
| DIY              |Gigabyte H270N                                  |i7 7700K                           |----            |----          |----   |
| DIY              |Gigabyte Z370P D3                               |i5 9600k                           |----            |----          |----   |
| DIY              |HP Z240 workstation                             |i7 6700                            |----            |----          |----   |

#### Rack server
| Official / DIY   | MotherBoard / Config Name                      | CPU                               |   Form Factor  |H-Reverb Test | Price |
|----              |----                                            |----                               |----            |----          |----   |
| DIY              |DELL R210 II                                    |Xeon 1230 V2                       |----            |----          |----   |

#### Mini / SFF / USFF Towers

| Official / DIY   | MotherBoard / Config Name                      | CPU                               |   Form Factor  |H-Reverb Test |Price €|
|----              |----                                            |----                               |----            |----          |----   |
| DIY              |HP Elitedesk 600 G3                             |i7 6700                            | SFF            |15            |150    |
| DIY              |HP Elitedesk 800 G1                             |i7 4790                            | SFF            |----          |----   |
| DIY              |HP EliteDesk 800 G3 Mini                        |i5 7700                            | USFF           |----          |----   |
| DIY              |HP Elitedesk 800 G5                             |i5 9500T                           |----            |----          |----   |
| DIY              |HP Elitedesk G2                                 |i5 6500T                           |----            |8             |----   |
| DIY              |Lenovo M93P tiny                                |i5 4570T                           | USFF           |----          |----   |
| DIY              |Lenovo thinkcentre M900-tiny                    |i5 6500T                           |----            |----          |----   |

### Bad ideas

- Vmware ESXI or other virtualisation solution : run but will also keep failing as the server need realtime usage, spend more time doing music geeks !
- Laptop server : as macbook pro or something else : as the server running the computer at fullspeed, it will make your computer die sooner ...


### Failed to work and will never be ...

- HP Elitedesk 400 G7 i5 10500 : CPU or lan recognition failed
- MSI B450M Mortar Max + Ryzen 3 1200
- MSI 790FX-GD70 + Phenom II X4 965
- Lenovo Thinkstation P340
- Non Intel CPU based configuration
- Non Intel or Some Realtek based NIC card


## FAQ

<details><summary>How do i check the CPU ?</summary>
<p>

I always take my [2013 CPU i7 4770](https://ark.intel.com/content/www/fr/fr/ark/products/75122/intel-core-i7-4770-processor-8m-cache-up-to-3-90-ghz.html)as reference.
It always had decent results on reverb test [creamware pulsar saturation on PCI Bus before](https://www.forums.scopeusers.com/viewtopic.php?t=17078&start=460) with the same result : around 10/11 reverbs.

When i need to check the "brut power" of a CPU for reference, i google "i7 4770 vs The other one cpuboss" and check rapidely on some site like [CPU Boss](http://cpuboss.com/) for benchmarck comparison or [passmark  comparison website](https://www.cpubenchmark.net/compare/).

I check to have at least the same as the i7 4770 (or almost equivalent :  [i5 8500T](https://www.cpubenchmark.net/compare/Intel-Core-i5-8500T-vs-Intel-Core-i7-4770/3231vs1907), [i7 4790](https://www.cpubenchmark.net/compare/Intel-i5-8500T-vs-Intel-i7-4770-vs-Intel-i7-4790/3231vs1907vs2226)

Avoid Celeron, Intel I3 or too old CPU (before 2013), and be carefull with the reference : i6500 is NOT the same as i6500T (or K, S, T, U ....)
</p>
</details>

<details><summary>Which motherboard ?</summary>
<p>

For a long time as reference (on planetz : [creamware user](https://www.forums.scopeusers.com/viewtopic.php?t=17078&start=460)) : ASUS or GIGABYTE where the most reliable choice for a music computer.

</p>
</details>

<details><summary>How do i mesure performance of my setup ? (Reverb Test)</summary>
<p>

One of the mesure of setup performance (and does not reflect the whole CPU capabilities - see "[CPU Performance vs. Real-Time Performance in Digital Audio Workstations (DAW)](https://www.youtube.com/watch?v=GUsLLEkswzE)" for full explanation), is to test the worst case scenario for plugins use : reverbs.
Reverbs are often the most commun and worst for system resources.
This is why this is a commun reference.( see 2005 [Masterverb thread](https://forums.scopeusers.com/viewtopic.php?t=17078&sid=21d12edd7bac80c1b0427111224bc653))

A simple test you can do, as waves does :

1. create an audio track on your DAW, insert random wav on it
2. set studiorack plugin insert on this track, select H - Reverb plug in
3. play, if it's :
  - DOES NOT poping or other interference, duplicate and repeat until it does
  - DOES popin, your reach your max, count your track number : and this his the end of the test

</p>
</details>
[^test_result]: performance under studiorack @44khz
