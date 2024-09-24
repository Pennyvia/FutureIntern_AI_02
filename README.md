# FutureIntern_AI_02
Image Generation Using Pretrained stable diffusion model


---

# Stable Diffusion Image Generation App

This repository contains code for a **text-to-image generation app** using **Stable Diffusion**. The app uses a pre-trained Stable Diffusion model to generate high-quality images based on user-provided text prompts.

## Features
- **Text Prompt Input**: Users can input text descriptions, and the app will generate corresponding images.
- **Pretrained Stable Diffusion Model**: Powered by the `diffusers` library from Hugging Face, utilizing a pretrained **Stable Diffusion v1-4** model.
- **Interactive UI**: The app uses **Gradio** to provide an intuitive web interface for easy interaction.

## How It Works
1. **User Input**: Enter a text prompt describing your desired image.
2. **Image Generation**: The Stable Diffusion model processes the prompt and generates an image.
3. **Display**: The app displays the generated image in the UI.

## Example Prompts
- `"A sunset over a mountain range"`
- `"A futuristic cityscape at night"`
- `"A cat playing guitar in space"`

## Getting Started

### Requirements
Make sure you have the following libraries installed:

- `torch`
- `Transformers`
- `diffusers`
- `accelerate`
- `gradio`

You can install these by running the following command:

```bash
!pip install torch transformers diffusers accelerate gradio
```

### Usage
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Pennyvia/FutureIntern_AI_02.git
   cd stable-diffusion-image-generator
   ```

2. **Run the App**:
   You can run this in **Google Colab** or any environment with a CUDA-enabled GPU. Here’s a brief guide:
   

3. **Interact with the App**:
   Once the app is running, you'll be able to enter text prompts into the Gradio UI and see the generated images.

## Colab Usage
To use the app in **Google Colab**, follow these steps:

1. Open a new notebook in Google Colab.
2. Install the required libraries by running the following:
   ```bash
   !pip install torch transformers diffusers accelerate gradio
   ```
4. The Gradio app will be available with a URL link to interact with the model and generate images.

## Model
This app uses the **Stable Diffusion v1-4** model from Hugging Face. The model is designed to generate high-quality images from text prompts.

For more details on the model, visit: [CompVis Stable Diffusion](https://huggingface.co/CompVis/stable-diffusion-v1-4)

## License
This project is licensed under the MIT License.

## Acknowledgements
- [Hugging Face Diffusers](https://huggingface.co/docs/diffusers/index)
- [Gradio](https://gradio.app/)

---
