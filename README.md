# Image-to-Speech Converter for Visually Impaired Individuals

![image](https://github.com/GvHemanth/Image-to-Text-Generation_CNN-Attention-RNN/assets/125199925/07381d55-a523-45cb-a50a-20c65c7e2c67)

## Overview

This project is an Image-to-Speech converter designed to assist visually impaired individuals. It uses deep learning and natural language processing techniques to process images, generate descriptive captions, and convert these captions into audio output. The primary goal is to provide a tool that helps visually impaired individuals understand the content of images, enhancing their accessibility and independence.

Key Features:
- **Image-to-Caption Generation:** The system generates textual descriptions of images using a deep learning model based on the Show, Attend, and Tell paper.

- **Caption-to-Speech Synthesis:** It transforms the generated captions into spoken language, enabling visually impaired individuals to comprehend the content of images.

- **Attention Mechanism:** This model uses an attention mechanism to focus on relevant parts of an image during caption generation, improving the accuracy of descriptions.

- **Beam Search:** An optional method for generating captions that explore multiple word sequences, enhancing the quality of descriptions.

- **Evaluation:** The system uses BLEU scores to assess the quality of generated captions and provides visualization tools to understand the attention mechanism's behavior.

## Model Training

To train the caption generation model, you can follow these steps:

1. Prepare your dataset of images and captions from here - https://www.kaggle.com/adityajn105/flickr8k.

2. Execute the `Eye_for_Blind.ipynb` script to train the deep learning model.

3. Model checkpoints and training logs will be saved in the `checkpoints` directory.

## Usage

To convert images to speech, follow these steps:

1. Install the required dependencies using `pip install -r requirements.txt`.

2. Execute the `Eye_for_Blind.ipynb` script to launch the system.

3. Provide an image as input, and the system will generate a descriptive caption, convert it to speech, and play the audio.

## Evaluation

The quality of generated captions can be evaluated using BLEU scores. Additionally, the system visualizes the attention mechanism's behavior, helping users understand which parts of an image are most relevant during caption generation.

## Acknowledgments

This project builds upon state-of-the-art deep learning techniques for image captioning and employs open-source libraries and APIs for audio synthesis.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions, suggestions, or feedback, feel free to contact Hemanth at [hemanthhemu17@gmail.com].
