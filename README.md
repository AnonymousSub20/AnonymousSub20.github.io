# ACCV2020 author response
### @R1, R3 Ablation Study
![ablation study](images\ablation_study.png)
### @R2 Large Motion and Parallax
**Large Parallax: ** An experiment on different baseline distances in the multi-camera
case is shown in the supplement material (section 1, Fig. 1-2). 

**Scene with Complex Motion: ** We select some harsh scenes to validate the ability of our model in handling large complex motion and parallax. 
We use the GIF file for better display of motion and parallax between the inputs, both scenes have perspective difference and large object movements. Visual comparison on scens is showed  below the GIF image. 

**Secne1 InCoffeshop**
![InCoffeshop inputs](images\InCoffeeShop2.gif)
result comparison
![InCoffeshop Visual Comparison](images\InCoffeeShop2.png)
For scenes with complex motion (camera and objects), previous methods tend to generate artifacts in the regions with large motion or disparity (such as the wall with clock in scene 1 and human faces in scene 1 and scene 2), while our method can still produce ghosting-free results.

**Secne2 OpeningPresentsWithGrandpa**
![OpeningPresents inputs](images\OpeningPresentsWithGrandpa1.gif)
result comparison
![OpeningPresents Visual Comparison](images\OpeningPresentsWithGrandpa1.png)

**Secne3 GoingOutTheDoor**
![OpeningPresents inputs](images\GoingOutTheDoor1.gif)
result comparison
![OpeningPresents Visual Comparison](images\GoingOutTheDoor1.png)
