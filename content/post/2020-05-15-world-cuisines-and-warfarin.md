---
title: World Cuisines and Warfarin
author: Heidi Steiner
date: '2020-05-15'
slug: world-cuisines-and-warfarin
categories: []
tags:
  - plot
  - data
---

The best way to improve prediction is to increase the amount of data you're using to do the prediction. With warfarin, the anticoagulant I study, there are limited sources of explored variability in drug response. My goal is to incorporate additional data with clinical phenotype information to best predict a patient's therapeutic dose. 

## Adding More Data
I saw this fun paper on twitter <https://conferences.computer.org/icde/2020/pdfs/ICDEW2020-56MW9gWd2XRGOkRROeeZ2s/426600a098/426600a098.pdf> and immediately thought of my warfarin project. We know diet has an effect on therapeutic dose but have no way of accounting for this information yet. Using the clusters of world cuisines found in the analysis by this paper, I clustered my study participants by their (highly assumptive) diets.

![](/images/cuisines.png)

## Plot
![](/images/foodplot.png)

It seems that there is potential for meaninginful prediction gained from the use of diet information according to therapeutic warfarin dose...more to come!