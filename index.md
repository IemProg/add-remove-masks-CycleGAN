---
layout: page
title: Adding and Removing Masks to/from People Using GANs
description: Project Site of LIM Paper "Adding and Removing Masks to/from People Using GANs"
author: Imad Eddine MAROUF
---
![](./image/RegAffine.PNG)
IR-RGB registration with the VoxelMorph architecture and the affine
network. When VoxelMorph (2nd and 3rd row) is trained with λ =
0.6 and λ = 0.1, it poorly deforms the shape of the objects in the
image. When compared visually, the affine network (1st row)
achieves better results.


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
* Marouf I.E, Ümit Bora GÖKBAKAN. (2021) "Adding and Removing Masks to/from People Using GANs" [[pdf]](./paper/Joint_Unsupervised_Video_Registration_and_Fusion.pdf) [[bibtex]](./bib/Marouf_Karaimer_LIM21.bib) 

#### Code, Data, and Supplemental Material ####

Please download the code [GitHub](https://github.com/IemProg/add-remove-masks-CycleGAN).   

Please download the supplemental material [[pdf]](./paper/MAROUF_GOKBAKAN_INF634.pdf).

#### People ####
[Imad Eddine Marouf], 	imad.marouf (at) ip-paris.fr

[Sabine Süsstrunk](Ümit Bora GÖKBAKAN), 	umit.gokbakan at ip-paris.fr
