# A Short Hike Modding Tools

In order to play with mods, you first need to install the modding tools.
1. Click this link to download the [Windows](https://github.com/BrandenEK/AShortHike.ModdingTools/raw/main/modding-tools-windows.zip) or [Linux](https://github.com/BrandenEK/AShortHike.ModdingTools/raw/main/modding-tools-linux.zip) version
1. Extract this zip file into the game's root directory

After this, any mods you wish to play with can be extracted into the 'Modding' folder created in the game's root directory.

---

A Short Hike root directory:
- Steam: ```C:\Program Files (x86)\Steam\steamapps\common\A Short Hike```
- Epic games: ```C:\Program Files\Epic Games\AShortHike```

---

In order to create a new short hike mod:

```dotnet new bepinex5plugin -n ExampleMod -T netstandard2.0 -U 2019.4.29```
