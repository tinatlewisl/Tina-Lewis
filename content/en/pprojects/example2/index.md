---
title: Reinforcement Learning Projects
summary:     
tags:  
- RL  
- AI    
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

# links:
# - icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
# Roses are <span style="color:red; font-family:Georgia; font-size:2em;">red.</span>
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#   slides: example
---
This page contains descriptions of a collections of Reinforcement Learning projects I worked on over the course of my graduate studies. This page will be updated with the different projects codes on github in the near future.

 <!DOCTYPE html>
<html lang="en">
  <head>
  <style>
      /* The . with the boxed represents that it is a class */
      .boxed {
        border-style: outset;  
        background-color: rgb(245,245,245);
        border-radius: 5px;
        padding: 20px 20px 20px 20px;
        margin-right: 0px;
      }
   
  </style>
  </head>
  <body>
  <hr>
   <div class="boxed">
    <span style="font-weight: bold;">Simulations for Accessing Global Convergence of Policy Gradient Methods in Reinforcement Learning </span>  
    <br><span style="color:grey; font-family:roboto; font-size:13px;"> October 2018 -- December 2018</span> <span style="color:grey; font-family:roboto; font-size:13px;float:right;"> Python | Tensorflow </span>
    <ul>
    <span style="font-size:13px;">
      <li> Evaluated the convergence performance of two policy gradient methods(Model-free & Mode-based) introduced in Fazel et al (2018) on the cartpole problem.</li>
      <li> Used the cartpole {position, velocity, angle and rotation} as input in the model free case in addition to the action taken at time t for the model-based case.
      <li> Model the ouput in both cases as the probability of the pole moving left or right as output.
      <li> Trained a neural network with 32 nodes and the ReLu activating function and adaptive learning to represent the policy gradient model for the model free method. The 
      <li> Used cross entropy loss function of the discounted reward as loss function and chose reward discount rate to cause future rewards to be highly valued.
      </span>  
      </ul>
     </div>
  <hr>
   <div class="boxed">
    <span style="font-weight: bold;">Predicting Users Music Sequence using Word2Vec Skipgram and LSTM model </span>  
    <br><span style="color:grey; font-family:roboto; font-size:13px;"> December 2017 </span> <span style="color:grey; font-family:roboto; font-size:13px;float:right;">  R </span>
    <ul>
    <span style="font-size:13px;">
      <li> Implemented an EM algorithm in R which sequentially locates and estimates the magnitude of the effects of 176 markers on blood pressure in mice.</li>
      <li>  Performed a permutation test to compute the critical value for the test statistics.</li>
      <li>  Used a hierarchical model approach with a non-informative prior on the tuning parameter to implementBayesian Lasso in R which allowed for simultaneously testing the location and effect of all markers at once.</li>
      <li>  Used a Gibb sampler to sample from the full conditional posterior of 341 parameters and hyper-parameters.</li>
      </span>  
      </ul>
     </div>
  <hr>
  </body>
</html>  
