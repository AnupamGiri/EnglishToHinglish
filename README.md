# EnglishToHinglish
This repository aims to display the code to translate an English sentence to Hinglish sentence.
### INDEX
##### 1.INTRODUCTION
##### 2.Setup
##### 3.Running the project
##### Approach
## INTRODUCTION
This repository contains a Python script for converting English text into Hinglish, a blend of Hindi and English, while ensuring that the translated text sounds natural and is easy to understand for both native and non-native Hindi speakers. This code leverages the Facebook mBART model for machine translation and integrates NLTK for named entity recognition. The primary goal is to provide a versatile tool for developers and researchers engaged in natural language processing tasks related to multilingual translation while maintaining context within translations.

#### A little insight on Multilingual BART (mBART) model
mBART is a multilingual variant of the BART (Bidirectional and Auto-Regressive Transformers) model, developed by Facebook AI. BART is known for its capabilities in various natural language processing tasks, such as text generation, translation, summarization, and more. mBART extends these capabilities to multiple languages.

### INPUT
![image](https://github.com/AnupamGiri/EnglishToHinglish/assets/76550954/1b37d5d2-e001-40b1-8c02-adb7e0c59cd3)
### OUTPUT
![image](https://github.com/AnupamGiri/EnglishToHinglish/assets/76550954/ac324b57-2b5b-4970-95bf-c8e4ecdc3c58)

## SETUP
Before using the code, ensure that you have the necessary dependencies installed:
```
pip install transformers -U -q
pip install sentencepiece
pip install -r requirements.txt 
```
## RUNNING THE PROJECT
#### Clone the repository
This is a straightforward step, however, if you are new to git, I recommend glancing threw the steps.
First, install git
```
sudo apt install git
```
Next, clone the repository
```
# Using HTTPS
https://github.com/devpandey2621998/man_down_deepstream.git
# Using SSH
git@github.com:devpandey2621998/man_down_deepstream.git
```

## Approach

 ##### Step 1 : Take an input sentence in English.
 ![image](https://github.com/AnupamGiri/EnglishToHinglish/assets/76550954/0a7791fe-c14a-40b7-8bbd-b45a3be3569b)

 ##### Step 2 : Translate the English sentecne to Hindi sentence.
 ![image](https://github.com/AnupamGiri/EnglishToHinglish/assets/76550954/f6184108-b261-4a7b-b1fe-935fa88b5137)

 ##### Step 3 : Detect noun in the English sentence using NLTK for named entity recognition.
 ![image](https://github.com/AnupamGiri/EnglishToHinglish/assets/76550954/06960b45-f7f3-472e-b94e-19f8c57948d3)

 ##### Step 4 : Convert noun words in Hindi sentence & replace the hindi noun word with English noun word.
![image](https://github.com/AnupamGiri/EnglishToHinglish/assets/76550954/3113634b-0d57-491b-89f6-e71a13179b3a)


