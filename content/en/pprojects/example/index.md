---
title: Machine Learning & Statistics Projects
summary:     
tags:  
- ML  
- Statistics    
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
This page contains descriptions of a collections of machine learning and statistics projects I worked on over the course of my graduate studies. This page will be updated with the different projects codes on github in the near future, as well as R packages that I am in the process of building for tensor data analysis.

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
    <span style="font-weight: bold;"> Improving Online Advertisement Sparse Tensors Completion </span>  
    <br><span style="color:grey; font-family:roboto; font-size:13px;"> June 2020 -- December 2020</span> <span style="color:grey; font-family:roboto; font-size:13px;float:right;"> Python | Matlab </span>
    <ul>
    <span style="font-size:13px;">
      <li> Implemented <a href="https://arxiv.org/pdf/2103.06428.pdf"> COSTCO </a> algorithm on advertisement CTR tensor data collected over a 2 months period from a leading internet company.</li>
      <li> Conducted data preprocessing to yield a  1000 x 140 x 3 (User x Ad x Device) sparse CTR tensor dataset with 98% of mising entries and 40% sparsity level.</li>
      <li> Compared CTR tensor entries recovery performance of COSTCO on test data to that of standard completion algorithms which yielded 23% improvemnent in recovery accuracy.</li>
      </span>  
      </ul>
     </div>
  <hr>
   <div class="boxed">
    <span style="font-weight: bold;">Sentiment Analysis of Amazon, IMDb and Yelp Data </span>  
    <br><span style="color:grey; font-family:roboto; font-size:13px;"> August 2016 -- May 2019</span> <span style="color:grey; font-family:roboto; font-size:13px;float:right;"> Python </span>
    <ul>
    <span style="font-size:13px;">
      <li> Performed sentiment analysis on customers and users reviews data from Amazon, IMDb, and Yelp.</li>
      <li> Trained a Multinomial Naive Bayes classifier to distinguish between positive and negative customer reviews.</li>
      <li> Wrote a Python program which reads in reviews, performs data cleaning and feature extraction and for each review decides whether it holds a positive or a negative sentiment.</li>
      </span>  
      </ul>
     </div>
  <hr>
   <div class="boxed">
    <span style="font-weight: bold;">Detecting Quantitative Trait Loci using Bayesian Lasso Hierarchical Model</span>  
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
   <div class="boxed">
    <span style="font-weight: bold;">Detecting Fraudulent Credit Card Transactions using Weighted Logistic Regression</span>  
    <br><span style="color:grey; font-family:roboto; font-size:13px;"> May 2018 </span> <span style="color:grey; font-family:roboto; font-size:13px;float:right;">  Python</span>
    <ul>
    <span style="font-size:13px;">
      <li> Used credit card transactions data from a major bank to train a logistic regression for detecting fraudulent transactions in Python.</li>
      <li> Performed data cleaning and feature selections.</li>
      <li> Applied L2 regularization on logistic regression and adjusted for unbalanced number of fraudulent and non-fraudulent cases in training data using weights to improve classifier performance and reduce bias.</li>
      </span>  
      </ul>
     </div>
  <hr>
    <div class="boxed">
    <span style="font-weight: bold;"><a href=" https://en.wikipedia.org/wiki/Quantitative_trait_locus#:~:text=A%20quantitative%20trait%20locus%20(QTL)%20is%20a%20region%20of%20DNA,often%20found%20on%20different%20chromosomes">QTL</a> Mapping of Lipid Profiles in Mouse</span>  
    <br><span style="color:grey; font-family:roboto; font-size:13px;"> May 2018 </span> <span style="color:grey; font-family:roboto; font-size:13px;float:right;">  R | QTL Cartographer</span>
    <ul>
    <span style="font-size:13px;">
     <li> Performed <a href=" https://en.wikipedia.org/wiki/Quantitative_trait_locus#:~:text=A%20quantitative%20trait%20locus%20(QTL)%20is%20a%20region%20of%20DNA,often%20found%20on%20different%20chromosomes">QTL</a> mapping to identify Quantitative Trait Loci associated with plasma triglyceride and HDL concentration exibiting a mixture of normal distribution.</li>
     <li> Estimated genetic map in R using the two-point algorithm, Rapid Chain Delineation (RCD).</li>
     <li> Conducted a permutation test to determine the significance threshold for interval and composite interval mapping.</li>
      </span>  
      </ul>
     </div>
  </body>
</html>  
