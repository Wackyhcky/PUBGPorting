PUBGPorting - Automation of the PUBG Porting Process
------------------------------------------

#### Powered by [Avalonia UI](https://avaloniaui.net/) and [CUE4Parse](https://github.com/FabianFG/CUE4Parse)

[![Blender](https://img.shields.io/badge/Blender-4.2+-blue?logo=blender&logoColor=white&color=orange)](https://www.blender.org/download/)
[![Unreal](https://img.shields.io/badge/Unreal-5.4+-blue?logo=unreal-engine&logoColor=white&color=white)](https://www.unrealengine.com/en-US/download)
***

![image](https://cdn.discordapp.com/attachments/1288831921920540793/1330564075796828211/PUBGPortingAPP.png?ex=678e6fdc&is=678d1e5c&hm=9cabee446bb494240ac90cabff9f6dd1c670f0e8ec90dcc90b964e418806bec5&)

## Building PUBGPorting

To build FortnitePorting from source, first clone the repository and all of its submodules.

```
git clone -b v3 https://github.com/Wackyhcky/PUBGPorting --recursive
```

Then open the project directory in a terminal window and publish

```
dotnet publish FortnitePorting -c Release --no-self-contained -r win-x64 -o "./Release" -p:PublishSingleFile=true -p:DebugType=None -p:DebugSymbols=false -p:IncludeNativeLibrariesForSelfExtract=true
```
