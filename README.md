Scripts for the "anago" NES cartridge dumper utility.

Extensions for Anago scripts are :

* **.ad** : for dumping scripts (that contain functions : **cpu_dump()** and **ppu_dump()** (without **cpu_ram_access()**))
* **.ae** : for dumping scripts (that contain function : **cpu_ram_access()**)
* **.af** : for flashing scripts (that contain functions : **cpu_transfer()** and **ppu_transfer()**)
* **.ag** : for both dumping and flashing scripts (that contain functions : **cpu_dump()**, **ppu_dump()**, **cpu_transfer()** and **ppu_transfer()**)
* **.ai** : for include scripts (that are called by other scripts with the **dofile()** function)

Related links:

* https://forums.nesdev.org/viewtopic.php?t=7912
* https://web.archive.org/web/20230826051825/https://ja.osdn.net/projects/unagi/releases/49771
* [how to write mapper scripts](https://web.archive.org/web/20201205090017/http://unagi.osdn.jp/cgi-bin/hiki/hiki.cgi?how+to+describe+mapper+scripts)
