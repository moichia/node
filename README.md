# Voxel Terrain
Unreal Engine 4 procedural voxel terrian example (partially based on Transvoxel™ Algorithm by Eric Lengyel http://transvoxel.org/)
This plugin provides tools to generate, visualize and in-game change volume terrain using voxels.

**Master branch tested with Unreal Engine 4.24 [Windows 7 x64, macOS Catalina 10.15.3]**
**Work in progress**

![Unreal Engine 4 voxel terrian](https://github.com/moichia/VoxelTerrain/blob/master/terrain.gif?raw=true)

![Grass](https://github.com/moichia/VoxelTerrain/blob/master/grass.gif?raw=true)

![Cave](https://github.com/moichia/VoxelTerrain/blob/master/cave.gif?raw=true)

# Features
* Runtime terrain modification
* Procedural landscape/caves generation
* Level of details (per chunk)
* Foliage
* Up to 65535 terrain materials
* Network multiplayer (experimental, WIP)

# Attention
* This project uses git submodules. Make sure that project are cloned properly and folder VoxelTerrain/Plugins is not empty.
* Work in progress. Some features is not finished/buggy/has ugly code/do not meet your expectations.

# Usage
1. Install MS Visual Studio 2017
2. Download last stable project 
3. Or clone repository properly ```git clone --recursive https://github.com/moichia/VoxelTerrain.git```
4. Open directory VoxelTerrain
5. Open project file with Unreal Engine 4.24

# License
MIT license
