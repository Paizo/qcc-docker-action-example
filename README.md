# qcc-docker-action-example

Docker image and github action example,
this is an example usage of [qcc-docker-action](https://github.com/Paizo/qcc-docker-action) a docker action image to build build Quake resources.

This example usage does the following:

 - compile a test map to bsp, applying light and vis (`jrbase1.bsp`)
 - compile the quakec sources to produce the `progs.dat`
 - prepare a release called `mymod.zip` (with an [autoexec.cfg](autoexec.cfg) to automatically load the map above on start)

to run the produced `mymod.zip` simply unzip it in your quake directory and run `quake -game mymod`


## Credits

 - qc sources from https://github.com/Jason2Brownlee/CleanFixedQuakeC/releases
 - map file https://www.gamers.org/dEngine/quake/QuakeEd/map_example.html (map file from ID shareware, manualled added wad reference)
