---
layout: post
title: "WHY DO I TAKE THE BURDEN OF HDR PHOTOGRAPHY?"
date: 2014-01-17 20:56:12 +0100
comments: true
categories: 
---
The post-processing workflow of exposure bracketed image sequences, i.e. input to HDR images,  is definitely more complicated than normal image processing workflows. Why do I put the extra effort into it?

It all started with an image I took of a pagoda in China. It was really unique how the top of the look as if a small tree was growing on the roof. I let the camera adjust to the high contrast, high dynamic range scene and have not even checked the image on the LCD of the camera.

It was shocking to see how different the photo was compared to how I perceived the scene. Anyone looking at this photo might wonders why I took it.

Luckily I took the original image in RAW, therefore I could try to play with the exposure value during the RAW development.

Exposure value tweaking during RAW development.

<p style="text-align:center;">
    <img src="http://adorjan.hopto.org:1974/content/images/2013/Dec/lijiang200806040.jpg" width="600" height="400" name="Comparison2" alt="LiJiang pagoda underexposed" border="0" pagespeed_url_hash="4058031720"/>
</p>
<div class="MouseOverBackground">
    <a href="javascript:void(0)" onmouseover="switchimage('Comparison2','LJ1');">Original</a> |
    <a href="javascript:void(0)" onmouseover="switchimage('Comparison2','LJ2');">HDR from exposure tweaked images</a> |
</div>

It did not deliver acceptable result. Though astonishing amount of detail is recovered compared to the original version, the signal to noise ratio is horrible in the shadow. I would not put this image printed in my living room.

**Lesson No. 1**: One can not reconstruct the information not recorded in the images even with the most sophisticated postprocessing workflow. 

Therefore I started to explore how we perceive and explore a scene with our eyes and brain. I found two major differences between human perception and photos taken with camera here :

* Our eyes scans around the scene
* Our pupil dynamically adjusts during the scan to enable seeing details in bright and dark areas.

A shot is a momentary event, with constant setting. We hav to remember that the viewer of our photo is going to scan it asif the original scene is observed. Our mission is to provide all the details for the scanning in a natural non-disturbing way.

Exposure bracketing exactly does that: takes a sequence of images with different exposure setting. The details of bright and dark areas are recorded this way. Unfortunately the details are in different images. It makes the post-processing more demanding. There are plenty of tutorials about how to align these images and merge the details into one. I will concentrate on evaluating the benefits of the whole process assuming you know how to do it.

The images below compare the following 3 methods:

1. An image taken with +1 exosure compensation
2. Image merged from 3 images developed from the above image with different exposure settings. I call it the 'Exposure tweaked image'
3. Image merged from an exposure bracket sequence

The original image taken with +1 exposure compensation. The sky behind the skyscrapers is overexposed just as the top of the cabin of the sailing boat in the bottom right corner and higher floors of the buildings.

<p style="text-align:center;">
  <img src="../images/img_8596_web.jpg" width="600" height="400" name="Eredeti" alt="Full originals" border="0" pagespeed_url_hash="3486502493"/>
</p>

<div class="MouseOverBackground1">
  <a href="javascript:void(0)" onmouseover="switchimage('Eredeti','ORIG2');">Original</a> |
  <a href="javascript:void(0)" onmouseover="switchimage('Eredeti','ORIG1');">HDR from exposure tweaked images</a> |
  <a href="javascript:void(0)" onmouseover="switchimage('Eredeti','ORIG3');">HDR from AEB image sequence</a> |
</div>


<p style="text-align:center;">
  <img src="../images/IMG_8596_crop1.jpg" width="600" height="400" name="Arnyek" alt="Crops of shadow" border="0" pagespeed_url_hash="3486502493"/>
</p>

<div class="MouseOverBackground1">
  <a href="javascript:void(0)" onmouseover="switchimage('Arnyek','CROP2');">Original</a> |
  <a href="javascript:void(0)" onmouseover="switchimage('Arnyek','CROP1');">HDR from exposure tweaked images</a> |
  <a href="javascript:void(0)" onmouseover="switchimage('Arnyek','CROP3');">HDR from AEB image sequence</a> |
</div>


<p style="text-align:center;">
  <img src="../images/img_8596_hajoorr.jpg" width="600" height="400" name="Hajoorr" alt="Hajoorr crop" border="0" pagespeed_url_hash="3486502493"/>
</p>

<div class="MouseOverBackground1">
  <a href="javascript:void(0)" onmouseover="switchimage('Hajoorr','HO2');">Original</a> |
  <a href="javascript:void(0)" onmouseover="switchimage('Hajoorr','HO1');">HDR from exposure tweaked images</a> |
  <a href="javascript:void(0)" onmouseover="switchimage('Hajoorr','HO3');">HDR from exposure tweaked images</a> |
</div>

<p style="text-align:center;">
  <img src="../images/egykepbol_8596_epulet.jpg" width="600" height="400" name="Epulet" alt="building crop" border="0" pagespeed_url_hash="3486502493"/>
</p>

<div class="MouseOverBackground1">
  <a href="javascript:void(0)" onmouseover="switchimage('Epulet','E2');">Original</a> |
  <a href="javascript:void(0)" onmouseover="switchimage('Epulet','E1');">HDR from exposure tweaked images</a> |
  <a href="javascript:void(0)" onmouseover="switchimage('Epulet','E3');">HDR from AEB image sequence</a> |
</div>



{<1>}![](http://)

<script language="javascript">
  <!--Comment tag so old browsers won't see code.
  LJ1=new Image(600,400)
  LJ1.src='../images/lijiang200806040.jpg'
  LJ2=new Image(600,400)
  LJ2.src='../images/lijiang200806040_hdr.jpg'
  HO1=new Image(600,400)
  HO1.src='../images/egykepbol_8596_hajoorr.jpg'
  HO2=new Image(600,400)
  HO2.src='../images/img_8596_hajoorr.jpg'
  HO3=new Image(600,400)
  HO3.src='../images/tobbkepbol_8596_8598_hajoorr.jpg'
  E1=new Image(600,400)
  E1.src='../images/egykepbol_8596_epulet.jpg'
  E2=new Image(600,400)
  E2.src='../images/img_8596_epulet.jpg'
  E3=new Image(600,400)
  E3.src='../images/tobbkepbol_8596_8598_epulet.jpg'
  CROP1=new Image(600,400)
  CROP1.src='../images/egykepbol_8596_crop1.jpg'
  CROP2=new Image(600,400)
  CROP2.src='../images/IMG_8596_crop1.jpg'
  CROP3=new Image(600,400)
  CROP3.src='../images/tobbkepbol_8596_8598_crop1.jpg'
  ORIG1=new Image(600,400)
  ORIG1.src='../images/egykepbol_8596_web1.jpg'
  ORIG2=new Image(600,400)
  ORIG2.src='../images/img_8596_web.jpg'
  ORIG3=new Image(600,400)
  ORIG3.src='../images/tobbkepbol_8596_web.jpg'
  function switchimage(imgDocID,imgObjName)
    {
    document[imgDocID].src=eval(imgObjName+'.src');
    }
    //End comment tag.-->
</script>

