+++
title = 'NDMU:QueryExclusiveMode'
+++

# Request

| Index Word | Description                |
|------------|----------------------------|
| 0          | Header code \[0x00030000\] |

# Response

| Index Word | Description                                                              |
|------------|--------------------------------------------------------------------------|
| 0          | Header code                                                              |
| 1          | Result code                                                              |
| 2          | Current Exclusive State (see [here](NDM_Services "wikilink") for values) |
