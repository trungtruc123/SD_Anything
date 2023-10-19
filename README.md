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
- DALL-E (Open AI): [tutorial](https://openai.com/dall-e-2)
- F222
- DreamShaper
- Inkpunk Diffusion
- Instruct pix2pix
- LoRA
- Tool custom pose: [tool](https://webapp.magicposer.com/)
## Extensions Available
### IP-Adapter (New 10/2023)
The image prompt adapter is designed to enable a pretrained text-to-image diffusion model to generate images with image prompt.

[paper](https://arxiv.org/abs/2308.06721)
[github](https://github.com/tencent-ailab/IP-Adapter)

### ControlNet 
ControlNet is a neural network structure to control diffusion models by adding extra conditions.

[paper](https://arxiv.org/abs/2302.05543)
[github](https://github.com/Luis-kleinfeld/ControlNet)
[tutorial](https://stable-diffusion-art.com/controlnet/?_gl=1*1t62rr3*_ga*MTEwMzQ0NjYyMS4xNjk3NDczMjk1*_ga_YHRX2WJZH7*MTY5NzQ3MzI5Ni4xLjEuMTY5NzQ3NTE2Ny42MC4wLjA.)
[ControlNet+ SDXL](https://stable-diffusion-art.com/controlnet-sdxl/?_gl=1*3m7ttk*_ga*MTEwMzQ0NjYyMS4xNjk3NDczMjk1*_ga_YHRX2WJZH7*MTY5NzQ3MzI5Ni4xLjEuMTY5NzQ3NTE2Ny42MC4wLjA.)

### Deforum
Deforum is a tool to create animation videos with Stable Diffusion. All you need to provide the prompts and settings for how the camera moves.

[tutorial](https://stable-diffusion-art.com/deforum/?_gl=1*3m7ttk*_ga*MTEwMzQ0NjYyMS4xNjk3NDczMjk1*_ga_YHRX2WJZH7*MTY5NzQ3MzI5Ni4xLjEuMTY5NzQ3NTE2Ny42MC4wLjA.)

### Regional Prompter
Do you know you can specify the prompts for different regions of an image? You can do that on AUTOMATIC1111 with the Regional Prompter extension.

[github](https://github.com/hako-mikan/sd-webui-regional-prompter)
### Ultimate SD Upscale
Do you want to create large images with Stable Diffusion with a lot of details? You will need to use an upscaler. In this post, you will learn 3 methods to upscale images.
- AI upscalers
- SD upscale
- ControlNet tile upscale
- T2I adapters (are neural network models for providing extra controls to image generations of diffusion models. They are conceptually similar to ControlNet but with a different design.)

[tutorial](https://stable-diffusion-art.com/controlnet-upscale/?_gl=1*1singjt*_ga*MTEwMzQ0NjYyMS4xNjk3NDczMjk1*_ga_YHRX2WJZH7*MTY5NzQ3MzI5Ni4xLjEuMTY5NzQ3NTE2Ny42MC4wLjA.)
### Openpose Editor

### After Detailer
[tutorial](https://stable-diffusion-art.com/adetailer/?_gl=1*48zyz2*_ga*MTEwMzQ0NjYyMS4xNjk3NDczMjk1*_ga_YHRX2WJZH7*MTY5NzQ3MzI5Ni4xLjEuMTY5NzQ3NTE2Ny42MC4wLjA.)

### AnimateDiff
Text-to-video is the challenging task of turning a text description into a video. Diffusion-based text-to-video model is improving at a rapid speed. Now, these models become usable and can be run locally on your machine. In this post, you will learn a few ways to convert a text prompt to a video.
- AnimateDiff
- ModelScope
- Deforum

[tutorial](https://stable-diffusion-art.com/text-to-video/?_gl=1*199e74w*_ga*MTEwMzQ0NjYyMS4xNjk3NDczMjk1*_ga_YHRX2WJZH7*MTY5NzQ3MzI5Ni4xLjEuMTY5NzQ3NTE2Ny42MC4wLjA.)
### text2video
[tutorial](https://stable-diffusion-art.com/text-to-video/?_gl=1*1mtbhyt*_ga*MTEwMzQ0NjYyMS4xNjk3NDczMjk1*_ga_YHRX2WJZH7*MTY5NzQ3MzI5Ni4xLjEuMTY5NzQ3NTE2Ny42MC4wLjA.)

### Roop 
Are you looking for ways to generate consistent faces across multiple images with Stable Diffusion? You may be working on illustrations of a storybook or a comic strip. In this post, you will find 3 methods to generate consistent faces.

- Multiple celebrity names
- The Roop extension
- Dreambooth

[tutorial](https://stable-diffusion-art.com/consistent-face/?_gl=1*1mtbhyt*_ga*MTEwMzQ0NjYyMS4xNjk3NDczMjk1*_ga_YHRX2WJZH7*MTY5NzQ3MzI5Ni4xLjEuMTY5NzQ3NTE2Ny42MC4wLjA.)

You can also help us implement more models.

## Install Control-StableDiffusion
