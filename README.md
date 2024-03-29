# WildFire-Project
## Problem
Massive wildfires are destroying homes and habitats around the world. With wildfires, early detection and prevention becomes key to containing the fire.
Most recently Australia's bush fire has been estimated to have taken 1.25 billion animal life. The late 2018 Woolsley fire in California has destroyed more than 1500 building.

## Solution
States like California and Nevada has set up surveillance cameras along wildfire hotspots. These cameras are monitored by volunteers during peak season. However I believe that these can be automated by the help of machine learning algorithms.

What this project aims to do is to detect fires from surveillance footage using convolutional neural networks. 

## Data
The dataset for this project was taken from AlertWildfire's webpage for livestream footage of firehotspots, and their youtube channel for videos of past fires.

Not fire/ livestrem: http://www.alertwildfire.org/

Fire feeds: https://www.youtube.com/user/nvseismolab/videos?disable_polymer=1

## Model
The model uses Convolutional Neural Networks on images taken from the videos. For the model, I had to first extract frames from the videos, and crop them to get rid of labels and coordinates and turn them into black and white. 

## Results
So far I have been able to reach a 94% testing accuracy with the model.
