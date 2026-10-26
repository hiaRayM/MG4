# MG4
## Devlog
Write your Devlog here.


When game start, the " Start()" work for once, and set "_timer" to " _switchSpeed". This timer record when should one food turn direction. In every frame "Update()" will do two things: firstly, it will folloew the value of "_up" to move the food up when it is true; secondly, use "Time.deltaTime" to decrease "time".
When "_time" decrease to 0 and reload "_switchSpeed", "_up=!_up" will turn the direction of moving. In this case, it form the animation finally.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)
