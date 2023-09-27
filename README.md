# **Ketsui - Soft Lock-On Sound**

This patch lowers the volume of the beeping lock-on sound effect in the Ketsui MAME rom. It has no other effect.

## Patching Instructions:

1 - Extract your MAME Ketsui rom archive (usually ket.zip).

2 - Using your xdelta patcher of choice, apply the ketsui-slos.xdelta patch to the file named either "cave_m04701b032.u17" or "m04701b032.u17", whichever one of those is present. Make sure that your patched file has the same filename as the original.

3 - Rezip the Ketsui rom archive.
  
  
##### NOTE 1: If you have any other Ketsui revisions/arranges in your roms folder, this patch will likely also affect their lock-on sounds (if they run using the same file that was patched). Keep a backup of your original Ket rom alongside the patched one, so you can easily switch them out whenever.

##### NOTE 2: When you start up the patched rom, MAME will complain about wrong checksum. This is expected, and can be safely ignored. If necessary, the patching process can be verified using the hashes below:
  
cave_m04701b032.u17 or m04701b032.u17  

(Original) &nbsp; CRC32:&nbsp; b46e22d1  
(Original) &nbsp; MD5:  &nbsp; &nbsp;   331efb81dc13923f59cbf186ee5dc283  
(Original) &nbsp; SHA-1: &nbsp; 670853dc485942fb96380568494bdf3235f446ee  
  
(Patched) &nbsp; CRC32:&nbsp; 23f65c08  
(Patched) &nbsp; MD5:  &nbsp; &nbsp;   0f7ffd903b7f2596e2c49bd9d1a260f4  
(Patched) &nbsp;  SHA-1: &nbsp; 9a18786f8e6f4c4b3f3647ca8e39fecb38e3ba93  

&nbsp;
##

Patch by KMH  
2023-04-19 - Released
