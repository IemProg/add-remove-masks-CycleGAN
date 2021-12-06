---
layout: page
title: Adding and Removing Masks to/from People Using GANs
description: Project Site of LIM Paper "Adding and Removing Masks to/from People Using GANs"
author: Imad Eddine MAROUF
---
![](./image/Mask2Unmask_pics.png)
Samples of generating \textit{masked faces from naked faces} using CycleGAN. First row corresponds to the output of CycleGAN network, second row is the input 
of the Cycle-GAN, and third row is the ground-truth image.  Cycle-GAN provides good results for putting masks on naked faces. Furthermore, we notice that sometimes 
it puts masks of different color than the original one in the ground-truth image.

![](./image/Unmask2Mask_pics.png)
Samples of generating naked faces from nasked faces using CycleGAN. First row corresponds to the output of CycleGAN network, second row is the input of the Cycle-GAN, and 
third row is the ground-truth image. Cycle-GAN fails at constructing a good facial representation as illustrated in the 5th column, 
the network lowered the intensity of the mask color instead of removing it completely.

### Abstract ###
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; We present a system to perform joint registration and fusion
for RGB and Infrared (IR) video pairs. While RGB is related to
human perception, IR is associated with heat. However, IR images often lack contour and texture information. The goal with
the fusion of the visible and IR images is to obtain more information from them. This requires two completely matched images.
However, classical methods assuming ideal imaging conditions
fail to achieve satisfactory performance in actual cases. From
the data-dependent modeling point of view, labeling the dataset
is costly and impractical.


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In this context, we present a framework that tackles two
challenging tasks. First, a video registration procedure that aims
to align IR and RGB videos. Second, a fusion method brings all
the essential information from the two video modalities to a single video. We evaluate our approach on a challenging dataset of
RGB and IR video pairs collected for firefighters to handle their
tasks effectively in challenging visibility conditions such as heavy
smoke after a fire.

#### Publications: ####
* Marouf I.E, Ümit Bora GÖKBAKAN. (2021) "Adding and Removing Masks to/from People Using GANs" [[pdf]](./paper/MAROUF_GOKBAKAN_INF634.pdf)

#### Code, Data, and Supplemental Material ####

Please download the code [GitHub](https://github.com/IemProg/add-remove-masks-CycleGAN).   

Please download the report [[pdf]](./paper/MAROUF_GOKBAKAN_INF634.pdf).

#### People ####
[Imad Eddine Marouf], 	imad.marouf (at) ip-paris.fr

[Ümit Bora GÖKBAKAN], 	umit.gokbakan at ip-paris.fr
