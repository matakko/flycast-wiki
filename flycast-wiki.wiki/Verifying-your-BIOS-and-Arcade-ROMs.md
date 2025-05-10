# Verifying BIOS files
This section was made to help into checking that your BIOS are the right ones in order to use them with Flycast.
## **NOTE: The NAOMI Bios section might be outdated right now, I still have to update the information with the checksums of the current NAOMI bios rqeuested in Fightcade2/flycast-dojo (as any other will give a warning about using an incorrect BIOS).**

## Arcade BIOS (NAOMI and Atomiswave)
Verifying the BIOS files for the arcade games is **STRONGLY** recommended, and if you are having issues to get NAOMI or Atomiswave to work, there's an high chance that it is related to using an outdated BIOS, which is why this resource is avaliable. If you don't know if your BIOS files are from the latest MAME romset, compare their contents with the screenshots provided, and if they don't match, please re-obtain them from an updated source. If they do match, then you should be fine.

### Airline Pilots BIOS (Needed for alpiltdx and alpilot) [airlbios.zip]
```
epr-21802.ic27 (maincpu $0 - 2MB) (Export)
epr-21801.ic27 (maincpu $0 - 2MB) (USA)
main_eeprom.bin (main_eeprom $0 - 128 bytes)
76f100_eeprom.bin (naomibd_eeprom $0 - 132 bytes)
```

### Ferrari F355 BIOS (Needed for f355 and f355p) [f355bios.zip]
```
epr-22851.ic27 (maincpu $0 - 2MB) Ferrari F355 (Export)
epr-22850.ic27 (maincpu $0 - 2MB) Ferrari F355 (USA)
epr-22849.ic27 (maincpu $0 - 2MB) Ferrari F355 (Japan)
main_eeprom.bin (main_eeprom $0 - 128 bytes)
x76f100_eeprom.bin (naomibd_eeprom $0 - 132 bytes)
```
### Ferrari F355 Deluxe BIOS (Needed for f355twin and f355twn2) [f355dlx.zip]
```
epr-21864.ic27 (maincpu $0 - 2MB) Ferrari F355 Deluxe (Export)
epr-21863.ic27 (maincpu $0 - 2MB) Ferrari F355 Deluxe (USA)
epr-21862.ic27 (maincpu $0 - 2MB) Ferrari F355 Deluxe (Japan)
epr-21864p.ic27 (maincpu $0 - 2MB) Ferrari F355 Deluxe (Export, prototype)
epr-21862p.ic27 (maincpu $0 - 2MB) Ferrari F355 Deluxe (Japan, prototype)
main_eeprom.bin (main_eeprom $0 - 128 bytes)
x76f100_eeprom.bin (naomibd_eeprom $0 - 132 bytes)
```


### The House of The Dead 2 BIOS (Needed for hotd2 and hotd2o) [hod2bios.zip]
```
epr-21331.ic27 (cpu1 $0 - 2MB) HOTD2 (Export)
epr-21330.ic27 (cpu1 $0 - 2MB) HOTD2 (USA)
epr-21329.ic27 (cpu1 $0 - 2MB) HOTD2 (Japan)
epr-21332.ic27 (cpu1 $0 - 2MB) HOTD2 (Korea)
hotd2biosproto.ic27 (cpu1 $0 - 2MB) HOTD2 (Proto)
main_eeprom.bin (main_eeprom $0 - 128 bytes)
x76f100_eeprom.bin (naomibd_eeprom $0 - 132 bytes)
```

### NAOMI BIOS (Needed for almost ALL NAOMI games) [naomi.zip]
```
epr-21576h.ic27 (maincpu $0 - 2MB) Japan
epr-21576g.ic27 (maincpu $0 - 2MB) Japan
epr-21576e.ic27 (maincpu $0 - 2MB) Japan
epr-21576d.ic27 (maincpu $0 - 2MB) Japan
epr-21576c.ic27 (maincpu $0 - 2MB) Japan
epr-21576b.ic27 (maincpu $0 - 2MB) Japan
epr-21576a.ic27 (maincpu $0 - 2MB) Japan
epr-21576.ic27 (maincpu $0 - 2MB) Japan
epr-21578h.ic27 (maincpu $0 - 2MB) Export
epr-21578g.ic27 (maincpu $0 - 2MB) Export
epr-21578f.ic27 (maincpu $0 - 2MB) Export
epr-21578e.ic27 (maincpu $0 - 2MB) Export
epr-21578d.ic27 (maincpu $0 - 2MB) Export
epr-21578a.ic27 (maincpu $0 - 2MB) Export
epr-21577h.ic27 (maincpu $0 - 2MB) USA
epr-21577g.ic27 (maincpu $0 - 2MB) USA
epr-21577e.ic27 (maincpu $0 - 2MB) USA
epr-21577d.ic27 (maincpu $0 - 2MB) USA
epr-21577a.ic27 (maincpu $0 - 2MB) USA
epr-21579d.ic27 (maincpu $0 - 2MB) Korea
epr-21579.ic27 (maincpu $0 - 2MB) Korea
boot_rom_64b8.ic606 (maincpu $0 - 512k) Set4 Dev BIOS
develop110.ic27 (maincpu $0 - 2MB) Dev BIOS v1.10
develop.ic27 (maincpu $0 - 2MB) "Dev BIOS (Nov 1998)
zukinver0930.ic25 (maincpu $0 - 2MB) Development ROM Board
epr-21576h_multi.ic27 (maincpu $0 - 2MB) Multi-region hack
epr-21336a.ic27 (maincpu $0 - 2MB) Dev BIOS v1.2
naomi_boot_2491.ic27 (maincpu $0 - 2MB) Dev Naomi Boot 2491
315-6188.ic31 (altera_pof $0 - 8244)
main_eeprom.bin (main_eeprom $0 - 128)
x76f100_eeprom.bin (naomibd_eeprom $0 - 132)
```

### NAOMIGD BIOS (Needed for almost ALL NAOMI GD ROM / CHD games) [naomigd.zip]
```
epr-21576e.ic27 (maincpu $0 - 2MB) Japan
epr-21576g.ic27 (maincpu $0 - 2MB) Japan
epr-21576h.ic27 (maincpu $0 - 2MB) Japan
epr-21578h.ic27 (maincpu $0 - 2MB) Export
epr-21578g.ic27 (maincpu $0 - 2MB) Export
epr-21578e.ic27 (maincpu $0 - 2MB) Export
epr-21577h.ic27 (maincpu $0 - 2MB) USA
epr-21577g.ic27 (maincpu $0 - 2MB) USA
epr-21577e.ic27 (maincpu $0 - 2MB) USA
main_eeprom.bin (main_eeprom $0 - 128)
x76f100_eeprom.bin (naomibd_eeprom $0 - 132)
```

### NAOMI 2 BIOS (Needed for almost ALL NAOMI 2 games) [naomi2.zip]
```
epr-23605c.ic27 (maincpu $0 - 2MB) Japan
epr-23605b.ic27 (maincpu $0 - 2MB) Japan
epr-23605a.ic27 (maincpu $0 - 2MB) Japan
epr-23605.ic27 (maincpu $0 - 2MB) Japan
epr-23608c.ic27 (maincpu $0 - 2MB) Export
epr-23608b.ic27 (maincpu $0 - 2MB) Export
epr-23608a.ic27 (maincpu $0 - 2MB) Export
epr-23608.ic27 (maincpu $0 - 2MB) Export
epr-23607c.ic27 (maincpu $0 - 2MB) USA
epr-23607b.ic27 (maincpu $0 - 2MB) USA
epr-23607.ic27 (maincpu $0 - 2MB) USA
epr-23609b.ic27 (maincpu $0 - 2MB) Korea
epr-23605c_multi.ic27 (maincpu $0 - 2MB) Multi-region hack
main_eeprom.bin (main_eeprom $0 - 128)
x76f100_eeprom.bin (naomibd_eeprom $0 - 132)
```    

### Atomiswave BIOS (Needed for ALL Atomiswave games) [awbios.zip]
```
bios0.ic23 (awflash $0 - 128k) (Sammy BIOS)
bios1.ic23 (awflash $0 - 128k) (Sammy BIOS)
fpr-24363.ic48 (awflash $0 - 512k) (Sega BIOS)
```

### Sega SP BIOS (Needed for ALL Sega SP games) [segasp.zip]
```
epr-24236a.ic50 (maincpu $0 - 2MB) BOOT VER 1.01
epr-24328.ic50 (maincpu $0 - 2MB) BOOT VER 2.00
epr-24328a.ic50 (maincpu $0 - 2MB) BOOT VER 2.01
mb_serial.ic57 (main_eeprom $0 - 128 bytes)
net_eeprom.ic74s (netcpu $0 - 512 bytes)
net_firm_119.ic72 (netcpu $0 - 2MB)
fpr-24208a.ic72 (netcpu $0 - 2MB)
fpr-24329.ic72 (netcpu $0 - 2MB)
fpr-24407.ic72 (netcpu $0 - 2MB)
fpr-24407_123.ic72 (netcpu $0 - 2MB)
mb_eeprom_us.ic54s (sp_eeprom $0 - 128 bytes)
mb_eeprom_exp.ic54s (sp_eeprom $0 - 128 bytes)
```

# Verifying Arcade ROMs
If you have tried using NAOMI or Atomiswave games, but messages like "mpr-23192.ic11 is missing" come up, then that means you may be using outdated ROMs. Flycast uses the latest MAME ROMs (0.219 at the time of this writing), and while most work fine out of the box, others may have new files added in recent MAME which could be missing from your old ROM but be required by Flycast.

In any case, here there will be avaliable screenshots for many of the NAOMI/AW ROM contents, as a way to aid in double-checking if your ROM has all the needed files by the emulator (as the screenshots are from zipped ROMs that have been tested with Flycast). It is recommended to use the Search feature (CTRL+F in most browsers) and search your desired game (or filename) in order to find the one you need. All MD5 hashes provided for NAOMI cartridge games are for .zip format games.

## NAOMI Cartridge games
[Akatsuki Blitzkampf Ausf. Achse [ausfache]](https://github.com/TheArcadeStriker/flycast-wiki/blob/master/images/romcaptures/ausfache.PNG)

[Alien Front (Rev. T) [alienfnt]](https://github.com/TheArcadeStriker/flycast-wiki/blob/master/images/romcaptures/alienfnt.PNG)

[Capcom Vs. SNK Millenium Fight 2000 (Rev C) [capsnk]](https://github.com/TheArcadeStriker/flycast-wiki/blob/master/images/romcaptures/capsnk.PNG)

[Cosmic Smash (Rev A) [csmash]](https://github.com/TheArcadeStriker/flycast-wiki/blob/master/images/romcaptures/csmash.PNG)

[Crazy Taxi [crzytaxi]](https://github.com/TheArcadeStriker/flycast-wiki/blob/master/images/romcaptures/crzytaxi.PNG)

[The House of the Dead 2 (USA) [hotd2]](https://github.com/TheArcadeStriker/flycast-wiki/blob/master/images/romcaptures/hotd2.PNG)

[Power Stone 2 [pstone2]](https://github.com/TheArcadeStriker/flycast-wiki/blob/master/images/romcaptures/pstone2.PNG)

[Virtual On Oratorio Tangram M.S.B.S. ver5.66 2000 Edition [vonot]](https://github.com/TheArcadeStriker/flycast-wiki/blob/master/images/romcaptures/vonot.PNG)

[Wave Runner GP [wrungp]](https://github.com/TheArcadeStriker/flycast-wiki/blob/master/images/romcaptures/wrungp.PNG)

## NAOMI GD-ROM
In the case of NAOMI GD-ROM games, as they come as an .zip/.7z and .CHD pair, there will be an index of games, with the contents of the .zip file, and the name of the CHD file that is paired with it (along with the MD5 checksum of said file).

Capcom Vs SNK 2 Mark of the Millenium 2001 (USA) (GDL-0008) [cvs2]
* 317-5078-com.pic
* GD-ROM: gdl-0008.chd

Street Fighter Zero 3 Upper (Japan) (GDL-0002) [sfz3ugd]
* 317-5072-com.pic
* sfz3ugd-default-eeprom.bin
* GD-ROM: gdl-0002.chd

Monkey Ball (GDS-0008) [monkeyba]
* 317-0307-com.pic
* GD-ROM: gds-0008.chd

## Atomiswave games
[Guilty Gear X ver. 1.5 [ggx15]](https://github.com/TheArcadeStriker/flycast-wiki/blob/master/images/romcaptures/atomiswave/ggx15.PNG)

[Maximum Speed [maxspeed]](https://github.com/TheArcadeStriker/flycast-wiki/blob/master/images/romcaptures/atomiswave/Maximum%20Speed.PNG)

[The King of Fighters XI [kofxi]](https://github.com/TheArcadeStriker/flycast-wiki/blob/master/images/romcaptures/atomiswave/kofxi.PNG)

[The Rumble Fish [rumblef]](https://github.com/TheArcadeStriker/flycast-wiki/blob/master/images/romcaptures/atomiswave/rumblef.PNG)

[The Rumble Fish 2 [rumblef2]](https://github.com/TheArcadeStriker/flycast-wiki/blob/master/images/romcaptures/atomiswave/rumblef2.PNG)
