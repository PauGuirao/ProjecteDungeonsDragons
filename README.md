# Random Planet Generator
This is Multiplayer Battle Arena Game created for my Web Projects Class in La Salle University. It was created using Javascript, HTML, CSS and style frame framework Bootstrap        
<img src="Render.jpg" alt="Example Render" width="400" height="400">
## Create Planet
Call this functions to create a random 2D planet
- radius: integer to change the planet radius (normal:150)
- level_1: float to change the first layer of ground altitude (recommended: > 0.5)
- level_2: float to change the second layer of ground altitude (recommended: > 0.6)
```bash
$ drawPlanet(int radius, float level_1, float level_2)
```
## Create Moon
Call this functions to add a moon to the texture
- radius:  integer to change the moon radius
- distance:  integer to change the moon distance from the planet
```bash
$ drawMoon(int radius, int distance)
```
## Create Single 2D Texture
- name:  Name of the image
- type:  File type ('jpg','png')
```bash
$ createTexture(String name, String type)
```
