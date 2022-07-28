# Vision_project
Project for Vision and Cognitive Services exam.
Solve a Kaggle challenge related to a Vision problem.

Link to Competition: https://www.kaggle.com/competitions/understanding_cloud_organization/overview

Link to Dataset:     https://www.kaggle.com/competitions/understanding_cloud_organization/data

## Task 

In this competition you will be identifying regions in satellite images that contain certain cloud formations, with label names: Fish, Flower, Gravel, Sugar. For each image in the test set, you must segment the regions of each cloud formation label. Each image has at least one cloud formation, and can possibly contain up to all all four.

The images were downloaded from NASA Worldview.

## Abstract

Shallow clouds play a huge role in determining the
Earth’s climate. They are also difficult to understand and
to represent in climate models. Part of the reason is that
shallow clouds are not just the result of the global circulation
of the atmosphere. Rather, they have a life of their own
and arrange themselves in a variety of patterns. For many
of these patterns, the basic mechanisms behind them are
poorly understood. After some discussion, scientists agreed
that there are four common patterns and called them Sugar,
Flower, Fish and Gravel. By classifying these types of cloud
organization, researchers hope to improve our physical understanding
of these clouds, which in turn will help us build
better climate models, in order to have better prediction of
climate change or forecasting weather update

## Introduction 
The aim of this project is to identify regions in satellite
images that contain certain cloud formations, with names:
Fish, Flower, Gravel, Sugar. For each image in the test set,
we need to segment the regions of each cloud formation.
This is a multiclass segmentation task where we have to
find 4 different cloud patterns in the images.

## Model used

The project is divided into two
main parts. In the first one, I implemented a U-Net architecture
from scratch and tried to find the best combination of
hyperparameters to get the best results. Instead, in the second
part I compare the U-Net architecture built from scratch
with more complicated and already implemented networks,
in order to see if they can achieve better results.
