# Generated or Not? Exploring the Distinction Between AI-Generated and Human-Composed Music

## Overview
This project investigates how listeners differentiate AI-generated music from human-composed music, identifying key features that drive these distinctions. Through human studies and algorithmic classification, we explore musical characteristics such as repetition, mixing quality, and distortion to improve emotion-sensitive music generation. The project extends to classify generative models, achieving a notable accuracy rate and providing actionable insights for refining AI-generated music.

## Key Features
- **Human Subject Studies**: Conducted pilot and large-scale listening studies to gather participant insights and confidence levels in classifying music.
- **Feature Engineering**: Extracted embeddings from the CLAP model and temporal features from Wav2Vec2, complemented with handcrafted metrics like repetition, mixing quality, and distortion scores.
- **Algorithmic Classification**: Achieved robust accuracy in distinguishing between AI-generated and human-composed music, with 75% accuracy in identifying generative models.
- **Cultural and Ethical Considerations**: Explored the influence of cultural biases on perceptions of "human" characteristics in music.

## Project Structure
- `data`: Includes the AIME and MusicCaps datasets used for training and testing.
- `studies`: Contains scripts for conducting human subject studies and analyzing participant responses.
- `features`: Implements feature extraction using CLAP and Wav2Vec2, along with repetition, mixing quality, and distortion metrics.
- `models`: Houses training scripts and architectures for binary classification and generative model identification.
- `evaluation`: Scripts for analyzing model performance and generating metrics like accuracy, precision, recall, and F1 scores.

## Methodology
1. **Dataset Preparation**: Utilized AIME (AI-generated) and MusicCaps (human-composed) datasets, with clips trimmed to 7 seconds for consistency with the CLAP model input.
2. **Human Studies**:
   - Conducted pilot and large-scale listening studies to gather qualitative and quantitative data.
   - Analyzed the influence of participant demographics and prior exposure to generative music on classification accuracy.
3. **Feature Engineering**:
   - Used CLAP embeddings for semantic representation.
   - Extracted handcrafted metrics for repetition, mixing quality, and distortion.
4. **Model Training**:
   - Binary classification for distinguishing AI-generated from human-composed music.
   - Multi-class classification for identifying specific generative models.
5. **Performance Metrics**:
   - Evaluated models using accuracy, precision, recall, and F1 scores.

## Results
- **Human Studies**: Identified repetition, audio quality, and melodic complexity as key features distinguishing AI-generated music.
- **Algorithmic Classification**: Demonstrated the effectiveness of combined features, with repetition and mixing quality emerging as robust indicators.
- **Model Identification**: Achieved 75% accuracy in classifying outputs from 13 distinct generative models.

## Contributions
- **Kimaya Lecamwasam**: Designed human studies, analyzed participant feedback, and contributed to feature engineering.
- **Ananya Kulshrestha**: Developed the classification pipeline, integrated CLAP and Wav2Vec2 embeddings, and conducted model training and evaluation.

## Future Work
- Refine handcrafted features to better capture temporal and contextual dependencies.
- Explore alternate feature representations, such as tonal consistency and dynamic range.
- Incorporate raw audio processing for richer feature extraction.
- Investigate cultural biases in music perception and their implications for generative model design.

## Acknowledgements
We thank Prof. Anna Huang, Shih-Lun Wu, and the 21M.369/569 class for their invaluable feedback and support throughout the project.

## References
For detailed citations, refer to the final project report. Supplementary materials and audio examples can be found on the [project webpage](https://ananyakul.github.io/AIHAI/).
