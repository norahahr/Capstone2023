# Summary
This repository contains all images and all code used to produce the results for the capstone _Decoding Academic Language:
Investigating How Scientific Language Across Academic Disciplines Differs from General Language_ by Nora Svensson Hahr. 

## Installation
To use the code, you can clone the repo and install the dependencies. 
```
git clone https://github.com/norahahr/Capstone2023
cd Capstone2023
pip install -r requirements.txt
```

## External Resources
### EWISER
To install EWISER, it is recommended to follow the intructions provided at: https://github.com/SapienzaNLP/ewiser

### Corpora
The **ElSevier OA CC-BY Corpus** can be accessed at: https://elsevier.digitalcommonsdata.com/datasets/zm33cdndxs/2

The **Corpus of Contemporary Academic English (COCA)** can be purchased at: https://www.corpusdata.org/purchase.asp

## Running the code
The code is split up into five jupyter notebooks: preprocessing and one for each language model used (KLD, LSA, EWISER, and Word2Vc).
The code relies on relative paths which can be specified manually. However, the paths are currently set so that they do not need to be modified if all necessary code and data is present in the directory when the code is run.
