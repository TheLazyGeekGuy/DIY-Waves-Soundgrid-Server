# DIY Waves Soundgrid Server

Based on this thread (or [URL="https://www.*********************842878673081651/"]this one on FB[/URL]) I've made a compilation  of working configuration for myself, looking for cheap SFF tower. H-Reverb test missing for most of the time (performance under studiorack @44khz ).


| Componant        |                  |
|----              |----              |
| CPU              | Intel CPU        |
| Network          | Intel or Some Realtek based NIC card |


### Waves official configurations 

|                  |                                                                                                                          |     |
|----              |----                                                                                                                      |---- |
|[Proton Server](https://www.waves.com/1lib/pdf/hardware/proton-server-a-e-spec.pdf) (-) | J4105AEL2 Intel® Celeron® J4105                    |     |
|Server One-C (+) : Gigabyte GA-B150N-GSM - Core I5 ([URL="https://www.waves.com/1lib/pdf/hardware/server-one-c-a-e-spec.pdf"]source[/URL])
|Mobile Server  (+) : [B]Nano-6000C[/B] -  i5-6200u
|Extreme Server (+++) : [B]Gigabyte GA-H81N[/B] - i5-4590K - [URL="https://www.waves.com/hardware/soundgrid-extreme-server#tab-tech-specs"]14 H-reverb[/URL]
|Impact Server C X9 (+++): [B]Gigabyte GA-B150N-GSM[/B] – Intel® Coffee Lake i7-9700 8g ([URL="https://www.waves.com/1lib/pdf/hardware/extreme-server-c-x9-a-e-spec.pdf"]source[/URL])
| Extreme Server-C : [B]Gigabyte GA-B360N-GSM [/B]v1.0 -  Intel® Coffee Lake i7 8 Core - [URL="https://www.waves.com/hardware/soundgrid-extreme-server-c#tab-tech-specs"]14 H- reverb[/URL]
[/LIST]

Should work :  Intel CPU based configuration with Intel or Some Realtek based NIC card 
[B]Warning[/B] : [I][U][B]Dont connect any other drive than the flash drive[/B][/U][/I]. During firmware update, it could blank your whole drive ...

[B]Towers[/B]
[LIST]
[*][B]Acer N4660G [/B]Core i7-8700
[*][B]ASRock H110M DVS[/B] i5 7400 3.0GHz
[*][B]Asus P79[/B] 3930x i7
[*][B]Asus Z87-K C2[/B] – I7 4770 - H Reverb : 11 Tracks (9 for Long)
[*][B]Asus H81M-K motherboard[/B] - I7 4771 (@ 3.9GHz) ([URL="https://www.*********************842878673081651/permalink/920887151947469/"]source[/URL]) - 14 H-Reverb


[*][B]Dell T5500[/B]. 
[*][B]Dell PowerEdge T20 [/B]– Xeon E3-1225 v3 - H Reverb Long : 11 Tracks
[*][B]Dell Optiplex 7060 [/B]
[*][B]Dell Optiplex 3050 Micro[/B] -  i5-7500T @2.7 Ghz - 8GB


[*][B]Gigabyte B365[/B] motherboard, which uses a realtek NIC.
[*][B]Gigabyte B365M DS3H[/B], Intel Core i7-9700K, Crucial CT8G4DFD824A 8GB Memory, Booting off a Kingston DataTraveler DTSE9G2 32GB Memory Stick.
[*][B]Gigabyte GA-H81M-S2PH[/B] (rev. 2.0) Intel i5 4570, DDR4 2x4 Gig 1600. 16 Gig Generic PenDrive.
[*][B]Gigabyte GA-H110TN[/B] - Core i7 6700
[*][B]Gigabyte GA-B360N GSM / WiFi[/B], Intel i7-8700K DDR4 8GB (2x4GB) 2666MHz PC4-21300, USB key SanDisk Cruzer Fit 8GB. (be sure to disable one of the extra network devices within the BIOS).
[*][B]Gigabyte b365m ds3h - I7-9700k[/B] -  Kingston FURY Beast DDR4 2666MHz 8GB. ([URL="https://www.*********************842878673081651/posts/925124641523720/?comment_id=925133904856127"]source[/URL])
[*][B]Gigabyte H410M S2H[/B], Intel Core i5 10400, RAM DDR4 Crucial 8Gb.
[*][B]Gigabyte H270N[/B] Wifi I7 7700K and B365M-ITX/AC I7 9700.
[*][B]Gigabyte Z370P D3[/B] + Core i5 9600k 


[*][B]HP Z240 workstation[/B] (Intel PCH C236 chipset? Intel I1219lm NIC) + Core i7 6700 
[/LIST]

[B]Rack server[/B]
[LIST]
[*][B]DELL R210 II [/B]- Xeon 1230 V2 24GB RAM
[/LIST]

[B]Tower existing in SFF[/B]
[LIST]
[*][B]HP Elitedesk 800 G1[/B] SFF I7-4790
[*][B]HP EliteDesk 800 G3 Mini [/B](i5 7700 - 8GB)
[*][B]HP Elitedesk 800 G5[/B] i5-9500T 
[*][B]HP Elitedesk G2 i5[/B] 6500T - 8 H-Reverb. 
[*][B]Lenovo M93P tiny[/B] i5-4570T 
[*][B]Lenovo thinkcentre M900-tiny[/B] (micro version/ 1/2RU). i5-6500T - 8gb ddr4 ram
[/LIST]

[B]Bad ideas[/B][LIST]
[*][B]Vmware ESXI or other virtualisation solution[/B]: run but will also keep failing as the server need realtime usage, spend more time doing music geeks !
[*][B]Laptop server[/B] : as macbook pro or something else : as the server running the computer at fullspeed, it will make your computer die sooner ...
[/LIST]


[B]Failed to work and will never be ...[/B]

[LIST]
[*][B]MSI B450M[/B] Mortar Max + Ryzen 3 1200
[*][B]MSI 790FX-GD70 [/B]+ Phenom II X4 965
[*][B]Lenovo Thinkstation P340 [/B]
[*][B]Non Intel CPU based configuration[/B] 
[*][B]Non Intel or Some Realtek based NIC card[/B]
[/LIST]


[B]How do i check the CPU ?
[/B]
I always take my [URL="https://ark.intel.com/content/www/fr/fr/ark/products/75122/intel-core-i7-4770-processor-8m-cache-up-to-3-90-ghz.html"]2013 CPU i7 4770[/URL] as reference. It always had decent results on reverb test ( [URL="https://www.forums.scopeusers.com/viewtopic.php?t=17078&start=460"]creamware pulsar saturation on PCI Bus before[/URL]) with the same result : around 10/11 reverbs.

When i need to check the "brut power" of a CPU for reference, i google "i7 4770 vs The other one cpuboss" and check rapidely on some site like [URL="http://cpuboss.com/"]CPU Boss[/URL] for benchmarck comparison or [URL="https://www.cpubenchmark.net/compare/"]passmark  comparison website[/URL].

I check to have at least the same as the i7 4770 (or almost equivalent :  [URL="https://www.cpubenchmark.net/compare/Intel-Core-i5-8500T-vs-Intel-Core-i7-4770/3231vs1907"]i5 8500T[/URL], [URL="https://www.cpubenchmark.net/compare/Intel-i5-8500T-vs-Intel-i7-4770-vs-Intel-i7-4790/3231vs1907vs2226"]i7 4790[/URL]  ...)

Avoid Celeron, Intel I3 or too old CPU (before 2013), and be carefull with the reference : i6500 is NOT the same as i6500T (or K, S, T, U ....)


[B]Which motherboard ?
[/B]
For a long time as reference (on planetz : [URL="https://www.forums.scopeusers.com/viewtopic.php?t=17078&start=460"]creamware user[/URL]s) : ASUS or GIGABYTE where the most reliable choice for a music computer.


[B]How do i mesure performance of my setup ? (Reverb Test)[/B]

One of the mesure of setup performance (and does not reflect the whole CPU capabilities - see "[URL="https://www.youtube.com/watch?v=GUsLLEkswzE"]CPU Performance vs. Real-Time Performance in Digital Audio Workstations (DAW)[/URL]" for full explanation), is to test the worst case scenario for plugins use : reverbs.
Reverbs are often the most commun and worst for system resources.
This is why this is a commun reference.( see 2005 [B][URL="https://forums.scopeusers.com/viewtopic.php?t=17078&sid=21d12edd7bac80c1b0427111224bc653"]Masterverb thread[/URL][/B] )

A simple test you can do, as waves does :
[LIST=1]
[*]create an audio track on your DAW, insert random wav on it
[*]set studiorack plugin insert on this track, select H - Reverb plug in
[*]play, if it's
[LIST]
[*][B]DOES NOT[/B] poping or other interference, duplicate and repeat until it does
[*][B]DOES[/B] popin, your reach your max, count your track number : and this his the end of the test
[/LIST]
[/LIST]
