# text-to-image
# Comparative Analysis of Stable Diffusion Models

This repository contains the code and results of a comparative analysis of different Stable Diffusion models for generating photorealistic images from text prompts. The purpose of this study is to identify the most effective model and settings for achieving high-quality, photorealistic results.

## Table of Contents
- [Introduction](#introduction)
- [Methodology](#methodology)
- [Code Explanation](#code-explanation)
- [Comparison Analysis](#comparison-analysis)
- [Conclusion](#conclusion)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This study compares the performance of Stable Diffusion 2.1, Stable Diffusion 2.0, and Stable Diffusion 1.5 in generating photorealistic images from text prompts. The analysis aims to identify the most effective model and settings for achieving high-quality results.

## Methodology
The comparison was conducted using a set of predefined text prompts representing various scenes, subjects, and styles. For each model, multiple combinations of inference steps (25, 50, 100, 150) and guidance scales (5.0, 7.5, 10.0, 12.0) were tested. The generated images were evaluated based on photorealism, match to the prompt, and visual quality. The generation time for each image was also recorded.

## Code Explanation
The provided code is a Python script that automates the process of generating images using different Stable Diffusion models and settings. It utilizes libraries such as torch, diffusers, PIL, time, tabulate, os, and google.colab. The code iterates over each combination of model, prompt, and settings, generating images and saving them on Google Drive. Comparison metrics are collected and displayed in a tabular format.

## Comparison Analysis
The analysis of the generated results revealed that Stable Diffusion 2.1 and Stable Diffusion 2.0 consistently produced images with higher photorealism compared to Stable Diffusion 1.5. Increasing the number of inference steps led to more detailed and refined images, while higher guidance scales resulted in images that more closely matched the text prompts. Specific and detailed text prompts generally yielded higher-quality and more accurate images.

## Conclusion
Based on the comparative analysis, Stable Diffusion 2.1 and Stable Diffusion 2.0 are recommended for generating photorealistic images from text prompts. A combination of 100-150 inference steps and a guidance scale of 7.5-10.0 provides a good balance between image quality and generation time. Careful prompt engineering is essential to obtain the best results.

## Usage
1. Clone the repository: `git clone https://github.com/your-username/stable-diffusion-comparison.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Open the `stable_diffusion_comparison.ipynb` notebook in Google Colab.
4. Mount your Google Drive and update the paths in the notebook accordingly.
5. Run the notebook cells to generate images using different Stable Diffusion models and settings.
6. Analyze the generated images and comparison metrics in the specified Google Drive folders.

## Results
The generated images and comparison metrics can be found in the `results` folder on Google Drive. The folder structure is organized by model and prompt, making it easy to compare the results across different settings.

## Contributing
Contributions to this project are welcome! If you have any suggestions, improvements, or additional analysis ideas, please feel free to submit a pull request or open an issue.

## License
This project is licensed under the [MIT License](LICENSE).
