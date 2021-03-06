# "Hands On Computer Vision with Julia" (🔸Release March,2021)

---

## Introduction:
Through this book, there will be thorough guidance for all developers who want to get started with building computer vision applications using Julia.<br>
Julia is well suited for image processing because of its ease of use and the fact that it lets you write easy-to-compile and efficient machine code.<br>
Readers will be taken through various packages that support image processing in Julia, and will also tap into open-source libraries such as OpenCV and Tesseract to find optimum solutions to problems encountered in computer vision. They will learn to build a full-fledged image processing application using JuliaImages, perform basic to advanced image and video stream processing with Julia's APIs, and much more.<br>

- ### Who this book is for<br>
This book is for all those Julia developers who are interested in learning how to perform image processing, for those who want to explore the field of computer vision and wish to benefit from this book.<br>
A basic knowledge of Julia will help you understand concepts more effectively.<br><br>





| Front Book Cover  | Back Book Cover  |
|-----------|--------------------|
|<p><img src="https://raw.githubusercontent.com/Mohammadimh76/Mohammadimh76.github.io/master/Book_5.jpeg"></p>|<p><img src="https://raw.githubusercontent.com/Mohammadimh76/Mohammadimh76.github.io/master/Book_5_b.jpeg"></p>|
|  <b>Book Name</b>   |   Hands On Computer Vision with Julia  |
| <b>Authors (Translators)</b>    |   A.Salehi, M.H.Mohammadi, S.Y.Moradi|
| <b>language</b>    |  Persian   |
| <b>Printed in the</b>    |  IRAN   |
| <b>Publisher</b>    |   ...  |
| <b>First Printing Edition</b>    |   ...  |
| <b>Print Length</b>    |  ...   |
| <b>ISBN</b>    |  978-600-...-...-.   |

---

<div class="nav">

## Contents
* [Chapter 1](#chapter-1): <i>Getting Started with JuliaImages</i>
* [Chapter 2](#chapter-2): <i>Image Enhancement</i>
* [Chapter 3](#chapter-3): <i>Image Adjustment</i>
* [Chapter 4](#chapter-4): <i>Image Segmentation</i>
* [Chapter 5](#chapter-5): <i>Image Representation</i>
* [Chapter 6](#chapter-6): <i>Introduction to Neural Networks</i>
* [Chapter 7](#chapter-7): <i>sing Pre-Trained Neural Networks</i>
* [Chapter 8](#chapter-8): <i>OpenCV</i>
* [Chapter 9](#chapter-9): <i>Case Study – Book Cover Classification, Analysis and Recognition</i>


🔸 [Authors](#authors)<br>
🔸 [TODO](#todo)<br>
🔸 [Demo](#demo)<br>

</div>

<main>


<article id="chapter-1">
  
## Chapter 1
- ### Getting Started with JuliaImages
Getting Started with JuliaImages, is about getting your first introduction to JuliaImages and ImageCore packages. We will be loading images from various sources and creating thumbnails, that is resizing and saving them back on disk in a different file format.<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 1</b> | | |
|-----------|--------------------|-----------|
|1-1 Technical requirements |1-5 Using test images|1-9 Summary |
|1-2 Setting up your Julia |1-6 Previewing images |1-10 Questions |
|1-3 Reading images |1-7 Cropping, scaling, and resizing | |
|1-4 Saving images |1-8 Rotating images | |

</article>

<article id="chapter-2">
  
## Chapter 2
- ### Image Enhancement
Image Enhancement, is all about working with the ImageFiltering package. We will understand what linear and nonlinear filtering operations are and how they can be used to transform images, such as sharpening, blurring, and smoothing.<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 2</b> | | |
|-----------|--------------------|-----------|
|2-1 Technical requirements |2-3 Applying image filters |2-5 Questions |
|2-2 Images as arrays |2-4 Summary | |

</article>

<article id="chapter-3">
  
## Chapter 3
- ### Image Adjustment
Image Adjustment, will guide you through the ImageMorphology package. Morphological transformations are some simple operations based on the image shape that allow you to remove small noise, shrink objects, separate objects, and increase the object size or background space.<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 3</b> | | |
|-----------|--------------------|-----------|
|3-1 Technical requirements |3-3 Fundamental operations |3-5 Summary |
|3-2 Image binarization |3-4 Derived operations |3-6 Questions |

</article>

<article id="chapter-4">
  
## Chapter 4
- ### Image Segmentation
Image Segmentation, will explore the ImageSegmentation package. Readers will learn how to use supervised and unsupervised methods to simplify or represent an image into something that is more meaningful and easier to analyze.<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 4</b> | | |
|-----------|--------------------|-----------|
|4-1 Technical requirements |4-3 Unsupervised methods |4-5 Questions |
|4-2 Supervised methods |4-4 Summary |4-6 Further reading |

</article>

<article id="chapter-5">
  
## Chapter 5
- ### Image Representation
Image Representation, will explore the ImageFeatures package. We will learn to compute compact descriptors or "features" in a form that permits comparison and matching of two images.<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 5</b> | | |
|-----------|--------------------|-----------|
|5-1 Technical requirements |5-4 ORB, rotation invariant image matching |5-7 Summary |
|5-2 Understanding features and descriptors |5-5 BRISK – scale invariant image matching |5-8 Questions |
|5-3 BRIEF – efficient duplicate detection method |5-6 FREAK – fastest scale and rotation invariant matching | |

</article>

<article id="chapter-6">
  
## Chapter 6
- ### Introduction to Neural Networks
Introduction to Neural Networks, will demonstrate the need for neural networks. We'll cover getting, preparing the data, and improving and predicting the images. This chapter will also teach you to classify datasets, training and putting it all together.<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 6</b> | | |
|-----------|--------------------|-----------|
|6-1 Technical requirements |6-4 Multiclass classification with the CIFAR-10 dataset |6-7 Summary |
|6-2 Introduction |6-5 Classifying cats versus dogs |6-8 Questions |
|6-3 First steps with the MNIST dataset |6-6 Reusing your models |6-9 Further reading |

</article>

<article id="chapter-7">
  
## Chapter 7
- ### Using Pre-Trained Neural Networks
Using Pre-Trained Neural Networks, will introduce you to pretrained networks and help in predicting image classes using Inception V3 and MobileNet V2. It will also help to extract features generated by Inception V3 and MobileNet V2 and cover transfer learning using Inception V3.<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 7</b> | | |
|-----------|--------------------|-----------|
|7-1 Technical requirements |7-5 Extracting features generated by Inception V3 |7-9 Questions |
|7-2 Introduction to pre-trained networks |7-6 Extracting features generated by MobileNet V2 |7-10 Further reading|
|7-3 Predicting image classes using Inception V3 |7-7 Transfer learning with Inception V3 | |
|7-4 Predicting an image class using MobileNet V2 |7-8 Summary | |

</article>

<article id="chapter-8">
  
## Chapter 8
- ### OpenCV
OpenCV, will demonstrate how to use the open source Open CV library to perform real-time computer vision analysis. We will learn to find faces on images and then track them on a video stream.<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 8</b> | | |
|-----------|--------------------|-----------|
|8-1 Technical requirements |8-4 Image capturing from web camera |8-7 Summary |
|8-2 Troubleshooting installation of Open CV |8-5 Face detection using Open CV |8-8 Questions |
|8-3 First steps with OpenCV |8-6 Object detection using MobileNet-SSD | |

</article>

<article id="chapter-9">
  
## Chapter 9
- ### Case Study – Book Cover Classification, Analysis and Recognition
Case Study – Book Cover Classification, Analysis and Recognition, will incorporate the various techniques that we've described all along the book to develop a Book cover classification, analysis, and recognition project.<br>

#### 🔹 Topics in this chapter include

</article>

---

<article id="authors">

## Authors

### The First: "Aram Salehi"

<p align="center">
  <img width="300" height="399" src="https://raw.githubusercontent.com/Mohammadimh76/Book_HandsOnComputerVisionWithJulia/main/Authors/AramSalehi.jpeg">
</p>


 
📧 𝐄𝐦𝐚𝐢𝐥: aramsalehi95@gmail.com 

============================================================================

### The Second: "Mohammad Hossein Mohammadi"

<p align="center">
  <img width="360" height="276" src="https://raw.githubusercontent.com/Mohammadimh76/Book_HandsOnComputerVisionWithJulia/main/Authors/MohammadHosseinMohammadi.jpeg">
</p>

Iam currently a Final-year BS.c student at the Department of Computer Engineering, Islamic Azad University, Najafabad Branch (IAUN) (Rank in CWUR) where I am a member of the Bioinformatics Laboratory (BL), advised by Prof. Mohammad Naderi Dehkordi. my research involves machine vision, deep learning, and neural networks. where I will complete my thesis on Accurate and Early Identification of Diabetes and it's Affecting Factors.

Prior to BL, I finished my Diploma - Mathematics and Physics in Sheikh Ansari Highschool, in September 2015. I tried to use my Diploma to build a solid bedrock for my future research. So in addition to taking many optional bachelor-level courses on math and computer science. I spent 6 months as an intern Programmer at the "CoTech" in Isfahan.

#### My main research interests
- Artificial Intelligence, Machine Learning
- Optimization Algorithm, Neural & NeuroFuzzy Network
- Computer Vision, Signal and Image Processing

🌐 𝐏𝐞𝐫𝐬𝐨𝐧𝐚𝐥 𝐏𝐚𝐠𝐞 "𝐌𝐨𝐡𝐚𝐦𝐦𝐚𝐝 𝐇𝐨𝐬𝐬𝐞𝐢𝐧 𝐌𝐨𝐡𝐚𝐦𝐦𝐚𝐝𝐢" 👉 [mohammadimh76.github.io](https://mohammadimh76.github.io/)<br>
📧 𝐄𝐦𝐚𝐢𝐥: m.h.mohammadimir2017@gmail.com

============================================================================

### Third: "Seyed Yahya Moradi"

<p align="center">
  <img width="320" height="318" src="https://raw.githubusercontent.com/Mohammadimh76/Book_HandsOnComputerVisionWithJulia/main/Authors/SeyedYahyaMoradi.jpeg">
</p>

I am Biomedical Engineer from University of Isfahan. My research interests is Non-Invasive Brain Stimulation, Neuroscience, Brain Mapping & Connectivity, Biomedical AI & IOT, Biosignal Processing.

- Brain stimulation techniques such as tDCS, tACS, tRNS, TMS, Theta-Burst Stimulation (TBS) and Magnetic Seizure Therapy (MST)<br>
- Sleep, Plasticity, Perception, Vision, Navigation<br>
- Q/EEG Decoding; Source Localization; Beamforming; Blind source separation<br>
- Causal Inference; Big Data; Unsupervised & Online learning; Expert System<br>
- Chaos and Fractal Theory<br>

🌐 𝐏𝐞𝐫𝐬𝐨𝐧𝐚𝐥 𝐏𝐚𝐠𝐞 "𝐒𝐞𝐲𝐞𝐝 𝐘𝐚𝐡𝐲𝐚 𝐌𝐨𝐫𝐚𝐝𝐢" 👉 [symoradi.website2.me](http://symoradi.website2.me/)<br>
📧 𝐄𝐦𝐚𝐢𝐥: s.yahyamoradi@yahoo.com 

</article>

---

<article id="todo">

## TODO
- [x] Chapter (1): Getting Started with JuliaImages
- [x] Chapter (2): Image Enhancement 
- [x] Chapter (3): Image Adjustment
- [x] Chapter (4): Image Segmentation
- [x] Chapter (5): Image Representation
- [x] Chapter (6): Introduction to Neural Networks
- [ ] Chapter (7): Using Pre-Trained Neural Networks
- [ ] Chapter (8): OpenCV
- [ ] Chapter (9): Case Study – Book Cover Classification, Analysis and Recognition

</article>

---
---

<article id="demo">
  
## Demo 

👇Click on the link below to see the E-Book Demo!👇😉

## (E-Book Demo): 🔺(Coming Soon)🔺

</article>


</main>

