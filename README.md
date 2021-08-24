# Voxel Terrain Generation
I've been working on the Voxel Terrain Generation project for about a year now.

The project focuses on using Simplex Noise alongside the Marching Cube (https://en.wikipedia.org/wiki/Marching_cubes) and the Transvoxel (http://transvoxel.org/) algorithms  to create a procedural environment. Alongside that, the project has implemented a level of detail system using an Octree. As the player moves, the terrain dynamically updates as the players moves through the environment to have the highest level of detail near the player.

The current plan for the project is to implement a detailed biome system. A naive approach is currently implemented based on factors like temperature, but flora and fauna have not been added yet. So, the hope would be to take account of multiple factors and generate flora and fauna based on those factors.

Below are some screenshots created by the system.


![alt text](https://github.com/thimler9/Voxel-Readme/blob/main/terrainGenerator1.png?raw=true)
![alt text](https://github.com/thimler9/Voxel-Readme/blob/main/terrainGenerator2.png?raw=true)
![alt text](https://github.com/thimler9/Voxel-Readme/blob/main/terrainGenerator3.PNG?raw=true)
