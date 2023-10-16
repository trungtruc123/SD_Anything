# Control-StableDiffusion
# <img src="https://github.com/trungtruc123/Control-StableDiffusion/blob/develop/images/logo.png"/>
# <img src="https://github.com/trungtruc123/Control-StableDiffusion/blob/develop/images/output_show.jpg"/>

🎁 Control-StableDiffusion allows users to add conditions like Canny edges (top), human pose (bottom), etc., to control the image generation of large pretrained diffusion models.

🎁 This repository contains StableDiffusion+ ControlNet models trained from scratch and will be continuously updated with new checkpoints. The following list provides an overview of all currently available models. More coming soon.

🎁 Contains documents for generation art images (GAN, StyleGAN, VAE, SD, SDXL, Lora, ControlNet)

🎁 You can use Control-StableDiffusion to, to name a few:
- Specify human poses.
- Copy the composition from another image.
- Generate a similar image.
- Turn a scribble into a professional image.

# [![](https://img.shields.io/badge/Paper-Link-0075ff)](https://arxiv.org/pdf/2302.05543.pdf) [![](https://img.shields.io/badge/Group-Support-0075ff)](https://github.com/trungtruc123/Control-StableDiffusion/issues) [![](https://img.shields.io/badge/Version-v2.0-0075ff)](https://stablediffusion.vn/update/) [![](https://img.shields.io/badge/Demo-Colab-red)](https://colab.research.google.com/drive/18atShssVe2bw2IKav16Oh5E36cHiMu0f?authuser=2#scrollTo=G9xi7wIfZB9P)
# [![](https://img.shields.io/badge/Tutorial%20Install-Link-green)]() [![](https://img.shields.io/badge/Download%20Data-Drive-pink)](https://drive.google.com/drive/u/2/folders/16e7YxDTuTPe7hOWGoTM-A_1xA6FznZnK) 
# [![](https://img.shields.io/badge/Tutorial%20Stable%20Diffusion-Link-blue)](https://stable-diffusion-art.com/category/tutorials/)

## 💬 Where to ask questions
Please use our dedicated channels for questions and discussion. Help is much more valuable if it's shared publicly so that more people can benefit from it.

| Type                            | Platforms      |
| ------------------------------- |----------------|
| 🚨 **Bug Reports**              | [GitHub Issue] |
| 🎁 **Feature Requests & Ideas** | [GitHub Issue] |
| 👩‍💻 **Usage Questions**          | [Github Discussions] |
| 🗯 **General Discussion**       | [Linkedin] or [Gitter Room] |

[GitHub issue]: https://github.com/trungtruc123/Control-StableDiffusion/issues
[github discussions]: https://github.com/trungtruc123/Control-StableDiffusion/issues
[gitter room]: https://www.facebook.com/profile.php?id=100038801181933
[linkedin]: https://www.linkedin.com/in/truc-tran-trung-380533149/


## 🔗 Links and Resources
| Type                            | Links                               |
| ------------------------------- | --------------------------------------- |
| 💼 **Documentation**              | [ReadTheDocs](https://github.com/trungtruc123/Control-StableDiffusion/tree/develop/docs)
| 💾 **Installation**               | [TTS/README.md](https://github.com/trungtruc123/Control-StableDiffusion/blob/develop/README.md)|
| 👩‍💻 **Contributing**               | [CONTRIBUTING.md](https://github.com/trungtruc123/Control-StableDiffusion/blob/develop/README.md)|
| 📌 **Road Map**                   | [Main Development Plans](https://github.com/trungtruc123/Control-StableDiffusion/blob/develop/README.md)


## 🔗 Architecture ControlNet + StableDiffusion
ControlNet is a neural network structure to control diffusion models by adding extra conditions.
<img src="https://github.com/trungtruc123/Control-StableDiffusion/blob/develop/images/cn.png"/>

By repeating the above simple structure 14 times, we can control stable diffusion in this way:
<img src="https://github.com/trungtruc123/Control-StableDiffusion/blob/develop/images/sd.png"/>

## Requirements


## Implemented Models
### Stable Diffusion
- Stable Diffusion: [paper](https://arxiv.org/pdf/2112.10752.pdf) [github](https://github.com/Stability-AI/StableDiffusion)
- Generative model SD:[github](https://github.com/Stability-AI/generative-models)
- Stable Diffusion WebUI: [github](https://github.com/AUTOMATIC1111/stable-diffusion-webui)

### ControlNet
- ControlNet: [paper](https://arxiv.org/pdf/2302.05543.pdf)

### Attention Methods
- Guided Attention: [paper](https://arxiv.org/abs/1710.08969)
- Forward Backward Decoding: [paper](https://arxiv.org/abs/1907.09006)
- Dynamic Convolutional Attention: [paper](https://arxiv.org/pdf/1910.10288.pdf)

### GAN
- GAN [paper]()
- StyleGAN [paper]()

You can also help us implement more models.

## Install Control-StableDiffusion
