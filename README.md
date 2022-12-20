# Diffusion_Model

<p align="center">
<img width="500px" src="https://github.com/Yukino1010/Diffusion_Model/blob/master/image_source/novel_ai.png" >
</p>

AI image generation is a technology that has been hotly discussed in the art and Deep Learning (DL) field. You must have heard of the AI Art Generator such as Dall-E 2 or NovelAI, a DL model that generates realistic-looking images from a given text sequence. <br>
To explore this technology deeper, we need to introduce a new class in the generative model called 'diffusion', first proposed by Sohl-Dickstein et al. (2015), which aimed to generate images from noise using a backward denoising process.
 
 <p align="center">
 <img width="500px" src="https://github.com/Yukino1010/Diffusion_Model/blob/master/image_source/diffusion.png" >
 </p>
The word diffusion was defined as the movement of any substance from a higher concentration region to a lower concentration. <br>
Inspired by this concept, the diffusion model defined Markov chain to slowly add random noise to the image. The Markov chain could be seen as a diffusion, and the process of adding noise is the movement.

Thus, our target is to find the noise (movement) added to the image and reverse this process.
The diffusion model is mainly composed of two processes Forward Noising and Backward Denoising; this could be regarded as continuously adding noise into the image than reversing this process.

***For the detail introduction, welcome visit my medium*** [[link](https://medium.com/@s125349666/understanding-the-diffusion-model-and-the-theory-behind-it-cafcd5752b98)]

## Data
data was collected from kaggle (another anime data) <br>
(https://www.kaggle.com/datasets/scribbless/another-anime-face-dataset)

## Result
<p align="center">
<img width="500px" src="https://github.com/Yukino1010/Diffusion_Model/blob/master/image_source/result_1.gif" >
</p>
<p align="center">
<img width="500px" src="https://github.com/Yukino1010/Diffusion_Model/blob/master/image_source/result_2.gif" >
</p>

Denoising Diffusion Probabilistic Models
Denoising Diffusion Implicit Models
Keras example - Denoising Diffusion Implicit Models
Lil' Log - What are Diffusion Models?
Vedant Jumle - Image generation with diffusion models using Keras and TensorFlow

## References
1. ***Denoising Diffusion Probabilistic Models*** [[link](https://arxiv.org/abs/2006.11239)]
2. ***Denoising Diffusion Implicit Models*** [[link](https://arxiv.org/abs/2010.02502)]
3. ***Keras example - Denoising Diffusion Implicit Models*** [[link](https://keras.io/examples/generative/ddim/)]
4. ***Lil' Log - What are Diffusion Models?*** [[link](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)]
5. ***Vedant Jumle - Image generation with diffusion models using Keras and TensorFlow*** [[link](https://medium.com/@vedantjumle/image-generation-with-diffusion-models-using-keras-and-tensorflow-9f60aae72ac)]

