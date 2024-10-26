**Text To Image Generator Project:**

This project uses Hybrid architecture:
1.NLP 
2.Computer vision

How we say it uses hybrid architecture ?
The project is about Text to image generation. Firstly, the project is a going to process the text and then the image.
So we can say it as multimodal.

**Model used:** GAN model is used to generate an image.

Dataset used from website :https://universe.roboflow.com/ 

**What are Diffusers?**
Diffusers is the go-to library for state-of-the-art pretrained diffusion models for generating images, audio, and even 3D structures of molecules.

**Model used:**
1. dreamlike-art/dreamlike-diffusion-1.0
   This model can be used just like any other Stable Diffusion model.

2. stabilityai/stable-diffusion-xl-base-1.0
![image](https://github.com/user-attachments/assets/a41adff8-e698-425b-8097-ed49edd1c6bf)

**Limitations and Bias**
Limitations
The model does not achieve perfect photorealism
The model cannot render legible text
The model struggles with more difficult tasks which involve compositionality, such as rendering an image corresponding to “A red cube on top of a blue sphere”
Faces and people in general may not be generated properly.
The autoencoding part of the model is lossy.
Bias
While the capabilities of image generation models are impressive, they can also reinforce or exacerbate social biases.
