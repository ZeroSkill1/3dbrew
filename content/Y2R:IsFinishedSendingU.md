+++
title = 'Y2R:IsFinishedSendingU'
+++

# Request

| Index Word | Description                |
|------------|----------------------------|
| 0          | Header code \[0x00160000\] |

# Response

| Index Word | Description                        |
|------------|------------------------------------|
| 0          | Header code                        |
| 1          | Result code                        |
| 2          | u8, 0 = Not Finished, 1 = Finished |
