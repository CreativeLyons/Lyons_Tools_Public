# Lyons Tools Public

#### The Foundry's Nuke Tools/Gizmos created/modified by Tony Lyons
#### Visit www.CompositingMentor.com or www.Creativelyons.com for more info

---
**Table of Contents:**
- [01_Image:](#01-image-)
  * [LabelFromRead](#labelfromread)
- [02_Draw:](#02-draw-)
  * [GradMagic](#gradmagic)
  * [NoiseAdvanced](#noiseadvanced)
- [04_Channel](#04-channel)
  * [Binary Alpha](#binary-alpha)
- [05_Color](#05-color)
  * [BlacksMatch](#blacksmatch)
- [08_Merge](#08-merge)
  * [ContactSheetAuto](#contactsheetauto)

## 01_Image:
### LabelFromRead
Click for youtube Demo:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=dqzzT169GAc
" target="_blank"><img src="http://img.youtube.com/vi/dqzzT169GAc/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="320" height="240" /></a>


Displays Filepath of topmost read node over the image. Useful when viewing sequence contact sheets / matching shots.

## 02_Draw:
### GradMagic
Click for youtube Demo:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=oge8jMR0LRw
" target="_blank"><img src="http://img.youtube.com/vi/oge8jMR0LRw/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="320" height="240" /></a>

A live sampling 4 point gradient tool with ability to bake colors.

### NoiseAdvanced
Click for youtube Demo:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=EsHDBGonwEs
" target="_blank"><img src="http://img.youtube.com/vi/EsHDBGonwEs/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="320" height="240" /></a>

Noise with user friendly animation sliders and overscan.


## 04_Channel
### Binary Alpha

<img src="http://www.nukepedia.com/images/users/CreativeLyons/BinaryAlpha_SplashPage_v01.jpg" width="340" border="1" />

Analyzes a choice of the RGB, RGBA, or Alpha input and outputs an Alpha Channel (or RGBA) that is Binary, 0 or 1. Any Pixels that are not 0 will be turned into 1 (negative numbers also), and 0 will remain 0. This is perfect for those blur + unpremult tricks or if you need a quick matte for finding any rgb color above or below 0, in a CG render passes for example.

## 05_Color
### BlacksMatch

<a href="http://www.youtube.com/watch?feature=player_embedded&v=Kw3bcsmkGuk
" target="_blank"><img src="http://img.youtube.com/vi/Kw3bcsmkGuk/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="320" height="240" /></a>

This tool recreates a toe operation that's able to input an external image as it's black point and has controls for the multiply (the amount above the blackpoint that the operation stops affecting the midtones and highlights), and a control for the Gamma, or falloff, which is the bottom part of the curve and how it's blending with the blackpoint. You can toggle a preview overlay of a plotscanline and see how your blackpoint is affecting the rest of your image.

## 08_Merge
### ContactSheetAuto

<img src="http://www.nukepedia.com/images/users/CreativeLyons/ContactSheetAuto_SplashPage_v01.png" width="340" />

Contact Sheet that Automatically resizes according to number of inputs. Inspired by Ben McEwan's blog post.

