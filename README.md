# Text to Image Generation

This project demonstrates how to generate images from text prompts using the Hugging Face Stable Diffusion model.

## Installation

First, install the required packages:

- `diffusers`
- `transformers`
- `torch`
- `torchvision`
- `tqdm`
- `pandas`
- `numpy`
- `matplotlib`

## Initialize the Model

The Stable Diffusion model is initialized using the provided model ID and configured parameters.

## Image Generation Function

A function is provided to generate images from text prompts. The function takes a text prompt and the initialized model as inputs and returns the generated image.

## Usage

To generate an image, simply call the `generate_image` function with a text prompt. The generated image will be resized to 400x400 pixels.

## Hugging Face Model

The Stable Diffusion model used
