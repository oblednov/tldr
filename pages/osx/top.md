# top

> Display dynamic real-time information about running processes.

- Start top, all options are available in the interface

`top`

- Start top sorting processes by internal memory size (default order - process ID)

`top -o mem`

- Start top sorting processes first by CPU, then by running time

`top -o cpu -O time`

- Start top displaying only processes owned by given user

`top -user {{user-name}}`

- Run top in logging (batch) mode and update information 5 times

`top -l 5`

- Get help about interactive commands

`?`