# FOOGLE 🍔👁 — Food Image Classification

## Overview

FOOGLE is an AI-powered food image classifier built with EfficientNetB2 and the Food-101 dataset. It predicts 101 food categories from photos, providing accurate, real-time results. The Gradio web UI makes FOOGLE easy to use and demo.

## Features

- 🍕 Classifies food images into **101 types** (Food-101 dataset)
- 🧠 EfficientNetB2 model with transfer learning
- ⚡ Real-time predictions and confidence scores
- 🌐 Gradio web interface (browser-based)
- 🚀 Ready for deployment on Hugging Face Spaces

## Installation

```bash
# Clone the repository
git clone https://github.com/rageya/food-vision.git
cd food-vision

# Install dependencies
pip install -r requirements.txt

# Run the app locally
python app.py
```

## Usage

1. Upload or capture a food image on the Gradio web UI
2. Click **Predict** to see the food category and confidence score
3. Try example images or test your own food photos

## Model Details

- **Architecture:** EfficientNetB2
- **Dataset:** Food-101 (101,000 images, 101 categories)
- **Frameworks:** PyTorch, Gradio
- **Deployment:** Hugging Face Spaces or local server

## Example

![Demo Screenshot](https://via.placeholder.com/800x400?text=FOOGLE+Demo)

*Upload a food image to get instant classification results!*

## License

This project uses open source datasets and models. Please review licenses of Food-101 and EfficientNet.

## Citation

If you use this project, please cite:

```bibtex
@misc{foogle2025,
  author = {Rageya},
  title = {FOOGLE: Food Classification with EfficientNetB2},
  year = {2025},
  url = {https://huggingface.co/spaces/Rageya/FOOGLE}
}
```

## Contact

**Developed by Rageya**

- 🔗 Repository: [https://github.com/rageya/food-vision](https://github.com/rageya/food-vision)
- 🤗 Demo: [https://huggingface.co/spaces/Rageya/FOOGLE](https://huggingface.co/spaces/Rageya/FOOGLE)

Built with ❤️ using PyTorch, EfficientNet, and Gradio.
