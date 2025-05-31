# Stable Diffusion Text-to-Image Streamlit App

This is a simple GUI app built with Streamlit that uses Stable Diffusion (via the Hugging Face `diffusers` library) to generate images based on text prompts.

## Features

- Generate between 1 to 10 images.
- Customize prompt guidance scale and number of inference steps.
- Choose from various styles like anime, photo, video game, and watercolor.

## Requirements

- Python 3.7+
- `torch` with GPU support (if available)
- `diffusers`
- `streamlit`

## Getting Started

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-directory>
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Notes

- A GPU is recommended for faster image generation.
- Ensure you have access to the Hugging Face model `"CompVis/stable-diffusion-v1-4"` (it may require authentication).

