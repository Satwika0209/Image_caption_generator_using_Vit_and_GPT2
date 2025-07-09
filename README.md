# Image_caption_generator_using_Vit_and_GPT2
An image captioning project using a Vision Transformer (ViT) encoder and GPT-2 decoder to generate natural language descriptions for images. Built with the Hugging Face Transformers library and tested on the Flickr8k dataset, it provides accurate, human-like captions from visual inputs.
🖼️ Image Captioning with ViT-GPT2
This project implements an image captioning system that generates natural language descriptions for images using a Vision Transformer (ViT) as the encoder and GPT-2 as the decoder. The model is based on the pre-trained nlpconnect/vit-gpt2-image-captioning architecture from Hugging Face, which is fine-tuned on the COCO dataset. The system takes an image as input and produces a coherent English sentence describing its contents, showcasing the integration of computer vision and natural language processing.

The encoder (ViT) processes the image and extracts high-level visual features, while the decoder (GPT-2) generates the corresponding textual description. This combination of models allows the system to generate fluent and contextually relevant captions that describe the image in a human-like manner.

🔧 Features
Utilizes a powerful transformer-based vision model (ViT) for image understanding.

Leverages GPT-2's language modeling capabilities for generating fluent captions.

Supports inference on custom images in a few lines of code.

Designed to run on GPU for efficient generation.

Implemented using Hugging Face's transformers and datasets libraries.

📁 Dataset
The project uses the Flickr8k dataset for evaluation and demonstration purposes. The dataset includes over 8,000 images, each paired with multiple human-written captions.
🚀 How to Use
Simply load the model and tokenizer from Hugging Face, preprocess your image with the ViT feature extractor, and call .generate() to obtain the caption.

