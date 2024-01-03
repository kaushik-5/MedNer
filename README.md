
# MedNER
A NLP Project on NER(Named Entity Recognition) to view important entities in a transcription and highlighting prime entities using SpaCy.

## Business Understanding

The primary objective of this project was to develop a model capable of extracting key information from medical transcriptions. The motivation behind selecting this analysis project was to address the challenge of streamlining the time-intensive process faced by healthcare professionals in comprehensively reviewing transcriptions to identify crucial patient information.

The overarching goal was to contribute to the healthcare industry by creating a tool that could efficiently process and interpret medical transcriptions, aiding medical representatives in promptly understanding the patient's status.
## Data Understanding

The data utilized in this project originates from the MACCROBAT series, specifically MACCROBAT2020, comprising a comprehensive collection of 400 documents. Each document is paired with a corresponding set of 200 .txt files and 200 .ann files. 

The next steps involve processing and transforming the data into a structured format, starting with the conversion of the existing files into .json format. Subsequently, the data will be further transformed into .bio files, facilitating seamless integration into the project's analytical pipeline.

Future enhancements and analyses are planned to enhance the dataset visualization. This includes the exploration of document characteristics such as document length, distribution of sentence counts, identification of the most common words, and a comprehensive token frequency analysis.
## Screenshots

𝗩𝗶𝘀𝘂𝗮𝗹𝗶𝘇𝗮𝘁𝗶𝗼𝗻:

<img src="https://github.com/Kaushik-46/MedNer/assets/98961848/89a22096-3813-437d-87eb-b4c5a04216bc" alt="Document Length" width="300" height="250"><img src="https://github.com/Kaushik-46/MedNer/assets/98961848/6217dae6-2136-4611-afa9-d69b167c71cd" alt="Sentence Count" width="300" height="250">

<img src="https://github.com/Kaushik-46/MedNer/assets/98961848/b4e4529d-c358-4930-b3fa-b2629e54a730" alt="Most Common Words" width="350" height="250"><img src="https://github.com/Kaushik-46/MedNer/assets/98961848/353886d1-381d-4222-84d9-62e7f18b4ac3" alt="Token Frequency" width="250" height="250">

𝗥𝗲𝘀𝘂𝗹𝘁𝘀:

<img src="https://github.com/Kaushik-46/MedNer/assets/98961848/e98d88f8-9be7-449a-bf4c-0d684c5fb08c" alt="Results" width="600" height="400">

<br/> <br/> <br/>
<img src="https://github.com/Kaushik-46/MedNer/assets/98961848/a820d978-72b5-4244-8731-355b8a7b6499" alt="Output" width="1000" height="400">

## Tech Stack

**Tools Used:** Jupyter Notebook, Google Collab

**Languages:** Python3


## Run Locally

Clone the project

```bash
  git clone https://github.com/itsKaushik05/MedNer.git
```

Install Jupyter notebook

```bash
  pip install notebook
```

Run Jupyter Notebook ->
Open command prompt locally and type

```bash
  jupyter notebook
```

Upload the notebooks at the local tree

```bash
  cd notebooks
```
Import the dataset at the local tree

```bash
  cd dataset
```
Run the following notebooks with the structure
```bash
 📂 your_cloned_repo
    - 📂 notebooks
      - 📄 EDA_2020-1.ipynb
      - 📄 Bio_Files-2.ipynb
      - 📄 Data_Transformation-3.ipynb
      - 📄 Model_BiLSTM-4.ipynb
    - 📂 datasets
      - 📄 15939911.txt
      - 📄 15939911.ann
                .
                .
                .
      - 📄 20146086.txt
      - 📄 20146086.ann
    - 📂 annotated_dictionary
      - 📄 16778410.bio
      - 📄 18236639.bio
                .
                .
                .
      - 📄 24654246.bio
      - 📄 final_npz.npz
    - 📄 annotated_data.json  
```
## Status
As of the latest update, the project has reached a significant milestone and is currently in the "complete/released" status. The primary focus of this phase was the successful implementation of a BiLSTM (Bidirectional Long Short-Term Memory) model for predicting entities within the MACCROBAT2020 dataset. The model has been trained to identify and highlight relevant entities in the text.

The processed data has been integrated into the repository, allowing for seamless access and retrieval. The implementation employs spaCy, a powerful natural language processing library, to enhance entity recognition capabilities.

Additionally, a versioning system has been established to manage the evolution of the project. The current release is tagged accordingly, reflecting the completion of the initial objectives. Future iterations may include updates to the model architecture, improvements in performance, and additional features based on user feedback or evolving project requirements. The repository documentation provides comprehensive information on the current state of the project, making it accessible to both developers and end-users.
## Authors

- [@Kaushik G](https://github.com/kaushik-5)
- [@Asifaa Sulthana N](https://www.github.com/AsifaaSulthana-20ITR012)
- [@Fahima Begum B](https://www.github.com/Fahima0203)


