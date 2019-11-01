---
title: Introduction
nav_order: 1
---

# Introduction

## What is a parametric map

In clinical MRI we can acquire series of images with different acquisition settings or in a different physiological states. The changes observed on the images correspond to change of certain physical or physiological parameters. If the model of this change is known, a mathematical procedure called fitting can be performed to extract the parameters from the data. If this procedure is performed in every pixel a **parametric map** is generated.

The most common physical parameters used in MRI are relaxation times: [T1](#T1), [T2](#T2), [T2*](#T2*). The relation between relaxation times and different acquisition settings allow to model the changes observed on the images and thus generation of **relaxation time maps**.

When contrast agent is injected its propagation in the organ can be modeled. This way physiological parameters of the organ are reflected in generated **perfusion maps**.

Relaxation time maps and perfusion maps are often called **parametric maps**. Parametric maps are a promising research tool in cardiac diagnosis and therapy planning.

In other words:
```
To generate a parametric map of perfusion or relaxation times, multiple images of the same region of the myocardium are acquired with different sensitivity to the parameter of interest, and the signal intensities of these images are fit to a model that describes the underlying physiology or relaxation parameters. The parametric map is an image of the fitted perfusion parameters or relaxation times.
```
According to https://doi.org/10.1016/j.jcmg.2013.05.005

## T1

### What is T1

{% include T1.html %}

* http://mriquestions.com/what-is-t1.html
* https://qmrlab.org/jekyll/2018/10/23/T1-mapping-inversion-recovery.html

### Why T1 matters in cardiac MRI
* http://mriquestions.com/t1-mapping.html

## T2

### What is T2
* http://mriquestions.com/what-is-t2.html

### Why T2 matters in cardiac MRI
* http://mriquestions.com/edemat2-mapping.html

## T2*

### What is T2*
* http://mriquestions.com/t2-vs-t2.html

### Why T2 matters in cardiac MRI
* http://mriquestions.com/iront2-mapping.html