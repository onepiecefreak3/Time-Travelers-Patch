Time Travelers - English Preview Patch
============================

This patch is a preview of our current work and how far we can edit the game now. It only includes an edited menu and the intro sequence with translated movies and subtitles.

You can create issues if you find typos or errors in the issues page.

**How to patch the game**

1) Get a decrypted cia dump of your Time Travelers cartridge:<br>
  From cartridge: "[C:] GAMECART" > select "000400000008C600_v00.3ds" > select "NCSD image options..." > select "Build CIA from file"<br>
  From eshop: "[A:] SYSNAND SD" > title > 00040000 > 0008C600 > select the .tmd file > TMD file options... > Build CIA

2) Apply the patch with xdeltaUI > select tab "Apply Patch"<br>
  Patch: the .xdelta file in our patch<br>
  Source file: the decrypted dump from SD:\\gm9\\out<br>
  Output file: the path where the patched game should be saved<br>

3) Install the patched .cia with the newest version of FBI on your 3DS. Luma3DS CFW is recommended to install it on and play it.
