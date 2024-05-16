# Text-to-Image Synthesis with StackGAN

## Overview
The Text-to-Image Synthesis project aims to develop a robust deep learning model capable of generating realistic images from textual descriptions. This cutting-edge application bridges the gap between natural language understanding and image synthesis, providing a valuable tool for various industries such as e-commerce, graphic design, and virtual/augmented reality.

## Dataset
- **Name:** Flickr 30k
- **Description:** This dataset consists of 30,000 images collected from Flickr, each with five descriptive sentences provided by human annotators.

## Modeling Approach: StackGAN
StackGAN utilizes Stacked Generative Adversarial Networks (GANs) to generate high-resolution images with photo-realistic details. The generative process is decomposed into two stages:
1. **Stage-I GAN:** Sketches the primitive shape and basic colors of the object based on the given text description. It draws the background layout from a random noise vector, resulting in a low-resolution image.
2. **Stage-II GAN:** Corrects defects in the low-resolution image from Stage-I and completes the details of the object by revisiting the text description. It produces a high-resolution, photo-realistic image.

## Architecture
![StackGAN Architecture](https://www.google.com/imgres?q=stack%20gan&imgurl=https%3A%2F%2Fuser-images.githubusercontent.com%2F31109495%2F94064358-32e02d00-fe07-11ea-8ae0-a53e443f9509.png&imgrefurl=https%3A%2F%2Fgithub.com%2Fsavya08%2FStackGAN&docid=Ltn0yZkU_PK-9M&tbnid=fgakjp4-FJNRJM&vet=12ahUKEwicxNa-vZGGAxUNm68BHWp9BFsQM3oECBMQAA..i&w=1311&h=596&hcb=2&ved=2ahUKEwicxNa-vZGGAxUNm68BHWp9BFsQM3oECBMQAA)
*Figure: StackGAN Architecture*
## Why StackGAN?
- Earlier architectures faced limitations in generating high-resolution and diverse images from text descriptions.
- StackGAN employs a multi-stage generation process, capturing both coarse and fine-grained details for more realistic images.
- It effectively encodes textual descriptions into a format usable by the generator network, resulting in more coherent image generation compared to earlier methods.

## References
1. Conditional Image Generation with PixelCNN Decoders (PixelCNN) - 2016
2. Generative Adversarial Text-to-Image Synthesis (GAN-INT-CLS) - 2016
3. StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks - 2017

## Usage
- Clone the repository:  https://github.com/AnruthaKamal/Text-Canvas-.git
- Install dependencies: pip install -r requirements.txt

