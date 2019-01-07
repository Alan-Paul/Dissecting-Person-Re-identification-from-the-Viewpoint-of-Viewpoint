# Dissecting-Person-Re-identification-from-the-Viewpoint-of-Viewpoint

In this paper, we build a synthetic data engine PersonX that can generate images under controllable cameras and environment.
The dataset from PersonX is shown to be as indicative as real-world datasets. Second, based on PersonX, we conduct comprehensive experiment to quantitatively assess the influence of pedestrian viewpoint on person re-ID accuracy. Specifically, the PerxonX engine is built on Unity and its detials are as follows.

For researching viewpoint, we use six backgrounds in this version (as shown in above figure), including three pure color backgrounds and three scene backgrounds. There are 1266 hand-crafted identities (547 females and 719 males) and each identety has 36 viewpoints (sampled every <a href="https://www.codecogs.com/eqnedit.php?latex=0^{\circ}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?10^{\circ}" title="10^{\circ}" /></a> from <a href="https://www.codecogs.com/eqnedit.php?latex=0^{\circ}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?0^{\circ}" title="0^{\circ}" /></a> to <a href="https://www.codecogs.com/eqnedit.php?latex=0^{\circ}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?350^{\circ}" title="350^{\circ}" /></a> ), so the total number of images is 273,456 (<a href="https://www.codecogs.com/eqnedit.php?latex=36\times&space;1266&space;\times&space;6" target="_blank"><img src="https://latex.codecogs.com/gif.latex?36\times&space;1266&space;\times&space;6" title="36\times 1266 \times 6" /></a> ).

![fig1](https://github.com/sxzrt/Dissecting-Person-Re-identification-from-the-Viewpoint-of-Viewpoint/blob/master/images/fig1.jpg)  



****
## Datasets
We release 3D models of the identeties and the 1266 models can be downloaded from the following links:<br>
[Baidu Disk](https://pan.baidu.com/s/1nXdrniA7IDgJDKq6FexFJA)<br>
[Google Drive](https://drive.google.com/file/d/1d2PuKD60qFpugbqYfMHtjKmRj9OUdPG4/view?usp=sharing)

The package can be imported into Unity directly. 
*  "person1-1266.unitypackage" is a Unity package that contain the 3D original models of the identities. 
 
**** 
##### The original images and unity project will be released ASAP.

If you use this dataset in your research, please kindly cite our work as, <br>
```
@article{DBLP:journals/corr/abs-1812-02162,
  author    = {Xiaoxiao Sun and Liang Zheng},
  title     = {Dissecting Person Re-identification from the Viewpoint of Viewpoint},
  journal   = {CoRR},
  volume    = {abs/1812.02162},
  year      = {2018}
}
```
