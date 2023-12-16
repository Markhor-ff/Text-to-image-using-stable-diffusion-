# Text to Image using Stable Diffusion

## Overview

This Python notebook demonstrates text-to-image generation using stable diffusion and Google Translate. It includes a step-by-step guide on how to generate images from translated prompts.

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/Markhor-ff/Text-to-image-using-stable-diffusion.git
cd Text-to-image-using-stable-diffusion
```

### Install Dependencies

```bash
pip install googletrans==3.1.0a0
pip install --upgrade diffusers transformers -q
pip install --upgrade torch
```

### Open and Run the Notebook

- Open the notebook in your preferred environment (Google Colab, Jupyter Notebook, etc.).
- Run the cells sequentially to execute the code.

## Configuration

Modify the notebook's configuration parameters in the provided cells. Key parameters include:
- `device`: Specify the device ("cuda" for GPU, "cpu" for CPU).
- `generator`: Set the seed for the random generator.
- Image generation settings such as `image_gen_steps`, `image_gen_model_id`, etc.
- Google Translate and model settings.

## Contributing

Contributions are welcome! Please follow the guidelines in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

