# TimeCapsule (powered by Intel oneAPI)

An AI & ML solution to help you experience history like never before!

About:- TimeCapsule is an AI-based system that can summarize and generate historical events into concise and informative summaries. The system will use advanced algorithms to identify key events, people, and places mentioned in the text and create a summary that highlights the most important aspects of the historical event. 
TimeCapsule aims to create an AI-based system that can generate visually compelling and accurate videos and images of historical events.

Objective:- The goal of TimeCapsule is to make historical events more engaging and accessible for a wider audience. By providing visually stunning and accurate representations of historical events, the system will enable students, researchers, and history enthusiasts to gain a deeper understanding and appreciation of our shared past. Additionally, the system could be used in museums, historical sites, and educational institutions to enhance the learning experience and bring history to life.

Solution:- To develop an AI system that offers users comprehensive insights into historical events through a combination of text, image, and video content, providing a multi-dimensional and immersive learning experience.

## BART (Text summarization)

BART (Bidirectional and Auto-Regressive Transformer) is a neural network-based text summarization model developed by Facebook AI Research. BART is capable of performing both abstractive and extractive summarization, meaning it can generate a summary that includes new information not present in the original text, or it can select and condense the most important information from the input text.BART is a pre-trained model that has been fine-tuned on a variety of natural language processing tasks.

## Vicuna 13b (Large Langauge Model)

Vicuna is a large languagemodel that has been trained on vast amounts of textual data, such as books, articles, and websites, in order to generate human-like language responses. The goal of VIcuna is to be able to understand and generate natural language that is similar to the way humans communicate, and to do so on a wide range of topics and in various languages.Vicuna is based on neural networks, specifically on the Transformer architecture, which allows the model to process and analyze large amounts of text while capturing the context and relationships.

## Stable Diffusion (Image generation) 

Stable Diffusion is a latent text-to-image diffusion model capable of generating photo-realistic images given any text input, cultivates autonomous freedom to produce incredible imagery, empowers billions of people to create stunning art within seconds.

## Stable Diffusion text-to-video-synthesis Model

The text-to-video generation diffusion model consists of three sub-networks: text feature extraction model, text feature-to-video latent space diffusion model, and video latent space to video visual space model. The overall model parameters are about 1.7 billion. Currently, it only supports English input. The diffusion model adopts a UNet3D structure, and implements video generation through the iterative denoising process from the pure Gaussian noise video.

# The oneAPI effect

TimeCapsule utilizes several deep learning learning models that consume a considerable amount of memory, leading to longer processing times. This can cause delays in the analysis of input prompts, particularly on systems with limited processing capabilities.The Intel oneAPI platform helps in achieving better results by optimising the models. TimeCapsule uses state-of-the-art deep learning PyTorch framework which is optimized for the Intel architecture by the oneAPI platform and further boosts the inference of the models.

System Workflow:

![image](https://user-images.githubusercontent.com/92366177/231512004-149994b8-4259-4bec-8459-ccd799b2da9f.png)

Demo:

https://user-images.githubusercontent.com/92366177/231514931-3e45a7a2-2ab0-4645-adb0-8f30539d8e7c.mp4

