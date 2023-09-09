# Kirby

Authors: Luis Velazquez Sosa, Edward Garcia

Date: 2023-08-08

Personal Stories with Kirby
---
Luis:
I remember my first game console was a Gameboy Advance and one of the games I had was "Kirby's Dream Land". I remember playing Kirby and how fun it was seeing how he gained the abilities. I remember spending a lot of time playing and absorbing everything. I had friends that also played and we played together all the time. 


---
For the hightmap using the map of Puerto Rico I went to the [website](https://tangrams.github.io/heightmapper) suggested by the Profesor and made captures to the area most interesting to me. Once I had the the location I captured it. But when I went to the Unity the size of the image had to be squard, or in other words both size had to have the same pixel length. I used a free open source software called GIMP that help me edit images. I use the cropping tool and changed the aspect ratio from 16:9 to 1:1. This gave me an image with equal width and hight demensions. After this I exported the image to PNG format and imported it to Unity. 
![](C:\Users\luis\Documents\GitHub\Kirby\Images\cropping_hightmap.PNG)
I then in Unity had to change the terrain dimensions to 250 x 250 x 250. Once I did this I noticed that the terrain had peaks and valleys too extrem. I notice a setting called hight remap that made the ability to change how drastically the peaks and valleys were. Once I set the value to were I felt correct I created the terrain.![](C:\Users\luis\Documents\GitHub\Kirby\Images\Terrain_detailes_v2.PNG) We tested other part of Puerto Rico but we can to a conclusion an choose Arecibo for its dynamic terrain. 

Creating UFO Kirby was not too difficult but it presented some challenges. I used the prefab of Kirby to create a prefab variant. I removed most of the limbs of kirby. I used a sphere and scaled the y-axis down to create a disk shape. after that I made five small spheres in the bottom of the disk to make it more of a UFO.![](C:\Users\luis\Documents\GitHub\Kirby\Images\disk_shape.PNG)![](C:\Users\luis\Documents\GitHub\Kirby\Images\five_spheres.PNG)![](C:\Users\luis\Documents\GitHub\Kirby\Images\UFO_kirby.PNG) After this the Kirby body is put inside of the UFO with the head sticking out. 


Creating hammer Kirby was fun for a few reasones. When creating hammer kirby using the default prefab the expression of anger in Kirby I created brows that were derived from the mouth. The hand were moved to the center and down of the body. The legs had to be moved to the side and rotated up slightly. The addition of the headband is similar to the UFO in that we choose to have a disk shape and clipped it in to kirby’s head. the two strings from the head band were made with capsules. The headband was all colored white by creating a new color in the materials section. The hammer was created with two cylinders and colored with a new material brown referenced by the image online form the kirby’s website.  
![](C:\Users\luis\Documents\GitHub\Kirby\Images\hammer_kirby.PNG)