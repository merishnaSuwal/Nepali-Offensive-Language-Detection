# Nepali Offensive Language Detection and Sentiment Analysis

This repository contains the code and datasets for the Nepali Offensive Language Detection and Sentiment Analysis project.

## Abstract

Addressing offensive content in the digital realm has become crucial with the widespread use of online platforms and social media. However, the challenges posed by linguistic diversity make pre-trained models, originally designed for English or other languages, less effective in multilingual contexts. In response to this, our research aims to comprehensively explore the limitations and challenges associated with applying pre-trained models to multilingual offensive language detection tasks.

This paper focuses on developing and evaluating a system specifically designed for identifying offensive entities in Nepali, aiming to improve content moderation tools and foster safer online spaces for the Nepali-speaking community. The research extensively investigates the effectiveness of various pre-trained BERT architectures for Named Entity Recognition (NER), with a specific emphasis on aspect term extraction to accurately categorize abusive entities in Nepali text. Additionally, the study extends its scope to Sentiment Analysis (SA), concentrating on sentiment classification in the Nepali language. Through this dual approach, our research strives to augment content moderation tools and create safer online spaces for the Nepali-speaking community. Ultimately, our goal is to pave the way for enhanced cross-linguistic understanding and improved model performance across diverse languages. 

## Objectives

- Develop and evaluate a system tailored for identifying offensive entities in Nepali, contributing to the improvement of content moderation tools and the creation of safer online spaces for the Nepali-speaking community.

- Investigate the effectiveness of various pre-trained BERT architectures, with a specific focus on Named Entity Recognition (NER) for aspect term extraction. The goal is to accurately categorize abusive entities in Nepali text.

- Extend the research scope to include Sentiment Analysis (SA), concentrating on sentiment classification in the Nepali language. This dual approach aims to enhance content moderation tools and establish safer online spaces for the Nepali-speaking community.

## Key Features

- In-depth exploration of linguistic challenges in offensive language detection for a multilingual context.
- Evaluation of pre-trained BERT architectures for Nepali, with a particular emphasis on Aspect term extraction using NER and comprehensive analysis of sentiment classification in detecting Offensive Nepali language.

## Folder Structure

- **NepSA:** Code and resources for the Sentiment Analysis task.
  - **datasets:** Folder containing datasets related to Sentiment Analysis.
  - **NepSA.ipynb:** Jupyter notebook for running the Sentiment Analysis code.

- **NepNER:** Code and resources for the Offensive Language Detection using Named Entity Recognition (NER) task.
  - **datasets:** Folder containing datasets related to NER.
  - **NepNER.ipynb:** Jupyter notebook for running the NER code.

- **Paper_and_Slides:** Contains the paper and powerpoint slides for the project.

- **nepsa-nepner-inference:** Contains code to inference on saved models.

## Dependencies

- Python 3.x
- Jupyter Notebook
- Libraries: PyTorch, Transformers, scikit-learn, pandas, numpy, matplotlib, seaborn, and any other dependencies mentioned in the notebooks.

## Running on Local Machine

1. Clone the Repository:
 - Open a terminal.
 - Run the following command to clone the repository:

 ```bash
 git clone https://github.com/merishnaSuwal/nep-off-langdetect.git
```

2. Navigate to Folder and install the dependencies:

```bash
cd nep-off-langdetect
pip install -r requirements.txt
```

3. Run Experiments:
Explore the Jupyter notebooks and scripts in the repository to run experiments, evaluate models, and analyze results.


## Running the Code on Google Colab

1. Import the notebook in Google Colab.
2. Ensure that the required dependencies are installed and execute the cells one by one.

## Results and more information

Our research strives to contribute valuable insights into the effectiveness of pre-trained models for offensive language detection in Nepali. The findings are detailed in the corresponding research [paper](Paper/NLP_Offensive_language_Nepali_Paper_submission.pdf), highlighting advancements in aspect term extraction and sentiment analysis for the Nepali language.

You can also view the demo presentation of this project on [YouTube](https://www.youtube.com/watch?v=O6G8Vg8oCOE).

## Future Work

The project opens avenues for future research focusing on:

- Continued refinement of offensive language detection models for Nepali.
- Exploration of additional linguistic nuances and dialects within the Nepali language.
- Collaboration with the community to address specific challenges and further improve model performance.

## Contributors

- Merishna Singh Suwal
- Sujan Bhusal
- Drishtant Regmi

Feel free to contribute to this project by forking the repository and submitting pull requests.