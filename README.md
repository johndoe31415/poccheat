# poccheat
This is a cheat program for the 1987 classic "Ports of Call". It is mainly a
little reverse engineering exercise I did to keep my real mode debugging skills
up to date. It only works to cheat on single player savegames currently and
does not perform any sophisticated sanity checks.

## Usage
```
$ ./poccheat -m 123456000 SAVEGAME.TRP
Current money      : 8224000 (8.2 million)
Current checksum   : 2bca2d26
Calculated checksum: 2bca2d26 (OK)
New money          : 123456000 (123.5 million)
New checksum       : d1b3e586
```

The output file is called `cheat.trp`.

## License
GNU GPL-3.
