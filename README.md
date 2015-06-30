# Graphene-Raman-Mathematica
A set of Mathematica programmes for fitting Raman spectra and maps of graphene

The following programmes are designed for the analysis of CVD graphene but may be easily altered to analyse maps of exfoliated graphene and other materials such as dyes, etc. 

### Motivation
Raman maps can contain thousands of spectra with varying backgrounds and peaks. Commercial software packages such as Origin are often unsuitable or inefficient for graphing such maps. 
This programme is much faster than any commercial programmes I have seen, which is very beneficial when analysing maps of numerous samples.

### Features
Fits the D, G, and 2D peaks, as well as the D+D" and strained 2D peak when present.
Exports each fitted spectrum as a .png file.

![A typical spectrum of strained CVD graphene](https://cloud.githubusercontent.com/assets/12942120/8439620/7c09f818-1f6d-11e5-9af2-f893413cf6e7.png)

Performs analysis such as identifying multilayer and strained areas, then exports 2D and 3D images.
![A 3D image of the area of the G peak from a sample of graphene on nanostructured copper](https://cloud.githubusercontent.com/assets/12942120/8439618/7c01a5fa-1f6d-11e5-9f80-0ab5292c3f91.PNG)
![A 2D image of the area of the G peak from a sample of graphene on nanostructured copper](https://cloud.githubusercontent.com/assets/12942120/8439617/7bfa54bc-1f6d-11e5-9e13-5acf6d03de72.PNG)

Exports fitted histograms of the average (and enhanced) G peak area.
![A histogram of the average G peak area (below a certain cutoff point due to enhancement)](https://cloud.githubusercontent.com/assets/12942120/8439619/7c0612c0-1f6d-11e5-9489-907ea716b2b7.png)

Please read the guide "Analysing Raman maps of graphene with Mathematica" for details on the functionality of the programme and how to edit it. 
