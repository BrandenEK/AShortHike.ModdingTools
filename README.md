# A Short Hike Modding Tools

In order to play with mods, you first need to install the modding tools.  Right click on "modding-tools.zip", which can be found directly above this message, and click "Save link as" to download the zip file.  Then extract this zip file into the game's root directory.

- For steam, that will be ```C:\Program Files (x86)\Steam\steamapps\common\A Short Hike```

- For epic games, that will be ```C:\Program Files\Epic Games\AShortHike```

After this, any mods you wish to play with can be extracted into the 'Modding' folder created in the game's root directory.

---

In order to create a new short hike mod:

```dotnet new bepinex5plugin -n ExampleMod -T netstandard2.0 -U 2019.4.29```
