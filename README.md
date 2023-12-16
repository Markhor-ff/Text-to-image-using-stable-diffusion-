# Image Generation with Stable Diffusion and Google Translate

## Overview

This project combines stable diffusion for image generation with Google Translate for translating text prompts into English. The resulting images are generated based on the translated prompts.

## Requirements

Ensure you have the required packages installed by running:

pip install googletrans==3.1.0a0
pip install --upgrade diffusers transformers -q
pip install --upgrade torch


## Usage

1. **Clone the repository:**
   
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   

2. **Install dependencies:**
   
   pip install -r requirements.txt
   

3. **Run the script:**
   
   python TextToImage.py
   

## Configuration

Modify the script's configuration parameters in `CFG` class as needed. Key parameters include:
- `device`: Specify the device ("cuda" for GPU, "cpu" for CPU).
- `generator`: Set the seed for the random generator.
- Image generation settings such as `image_gen_steps`, `image_gen_model_id`, etc.
- Google Translate and model settings.

## Contributing

Contributions are welcome! Please follow the guidelines in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

