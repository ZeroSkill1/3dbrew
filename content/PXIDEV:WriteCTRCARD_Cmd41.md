+++
title = 'PXIDEV:WriteCTRCARD Cmd41'
+++

# Request

| Index Word | Description                                                   |
|------------|---------------------------------------------------------------|
| 0          | Header code \[0x000201C2\]                                    |
| 1          | Buffer Size                                                   |
| 2          | Sector Count                                                  |
| 3          | u8, [SectorSize](Gamecard_Services_PXI#sectorsize "wikilink") |
| 4-7        | Command                                                       |
| 8          | (Size \<\< 8) \| 0x6                                          |
| 9          | Buffer Pointer                                                |

# Response

| Index Word | Description |
|------------|-------------|
| 0          | Header code |
| 1          | Result code |

# Description

Writes to CTRCARD. The command written to the
[CTRCARD_CMD](CTRCARD_Registers#ctrcard_cmd "wikilink") register is the
same as provided, except the highest byte is changed to 0x41.
