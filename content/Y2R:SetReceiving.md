+++
title = 'Y2R:SetReceiving'
+++

# Request

| Index Word | Description                                     |
|------------|-------------------------------------------------|
| 0          | Header code \[0x00180102\]                      |
| 1          | Destination Pointer                             |
| 2          | Size                                            |
| 3          | s16, Transfer Unit                              |
| 4          | s16, Transfer Stride                            |
| 5          | 0x0                                             |
| 6          | Destination Process Handle (usually 0xFFFF8001) |

# Response

| Index Word | Description |
|------------|-------------|
| 0          | Header code |
| 1          | Result code |
