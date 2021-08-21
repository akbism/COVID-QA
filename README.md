# COVID-QA
COVID Question Answering Model
![COVID-QA](https://www.iaea.org/sites/default/files/styles/2016_landing_page_banner_1140x300/public/covid-19-updates-banner-a.png)

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
COVID-19 is a global crisis and has impacted much more than just public health. It has led to an outburst of information, which needs to be organized, validated, and timely made available to the seekers. The research proposes a transformer-based Question Answering (QA) system for COVID-19 questions from the biomedical domain.

### Built With

* Python – 3.7.11
* TensorFlow – 2.5.0
* PyTorch – 1.9.0+cu102
* Transformer – 4.9.2
* Datasets – 1.11.0
* SpaCy – 2.2.4
* NLTK – 3.2.5
* Textstat – 0.7.2

<!-- GETTING STARTED -->
## Getting Started

The work can be replicated well using Google Colab. First of all, we need to mount the google drive. The next importand step is to select the patameters carefully (provided in a section in the script).

### Prerequisites

Please install the above packages in colab before execution of any script. Most of the scripts will have command to install the required packages. 


<!-- USAGE EXAMPLES -->
## Usage

The finetuned model can be downloaded from [here](https://drive.google.com/drive/folders/13GdqFj0AVKgj40FGwmXchwpP-5xPImvH?usp=sharing)
It can be used as a backend model to predict answer for any COVID-19 question (given the context).

<!-- ROADMAP -->
## Roadmap

We are yet to see the impact of the following on the COVID-19 Question Answering Network performance:

* Impact of incremental datasets
* Increase the model vocabulary by adding words from COVID-19 domain
* Finetune (sentence + question) classification with BERT for answer verification module
* Analysis of why some question types are hard to answer




<!-- CONTACT -->
## Contact

Your Name - [Amar Kumar](https://www.linkedin.com/in/amar03/)

Project Link: [https://github.com/akbism/COVID-QA](https://github.com/akbism/COVID-QA)

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Hugging Face] (https://colab.research.google.com/github/huggingface/notebooks/blob/master/examples/question_answering.ipynb)
* [Question Classification] (https://colab.research.google.com/github/amankedia/Question-Classification-using-BERT/blob/master/QuestionClassificationUsingBERT(Coarse).ipynb)
* [PyTorch TPU Implementation] (https://colab.research.google.com/drive/1dVEfoxGvMAKd0GLnrUJSHZycGtyKt9mr#scrollTo=declared-pioneer)
* [Model Evaluation] (https://colab.research.google.com/github/fastforwardlabs/ff14_blog/blob/master/_notebooks/2020-06-09-Evaluating_BERT_on_SQuAD.ipynb)
* [Answer Verfication] (https://colab.research.google.com/github/fastforwardlabs/ff14_blog/blob/master/_notebooks/2020-06-09-Evaluating_BERT_on_SQuAD.ipynb)
