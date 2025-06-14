# AI-project-Cancer-Detection
Cancer detection through images


# Breast Cancer Detection
## Team 
- Gal Daria-Cristiana
- Găvriluț Maria-Teodora

## Goal
Development of an intelligent system to assist doctors in the early diagnosis of breast cancer, thereby increasing the chances of achieving effective treatment.

## Addressed Problem
Detecting breast cancer in mammograms is a critical issue in medical imaging. Due to the visual similarities between benign and malignant lesions, they can be difficult to distinguish with the naked eye, leading to potential interpretation errors.

## Proposed Solution
The proposed solution involves using Transformer models (ViT) for the automatic classification of mammograms into normal, benign, or malignant.  
The model is trained on the MIAS dataset, which contains mammographic images in PGM (grayscale) format and data regarding the type, location, and size of lesions.  
After training, the model is capable of automatically classifying a new image, displaying a message such as:  
"The image [image_name].pgm is classified as: [diagnosis]".

## Proposed Solution Schematic
```
 [MIAS dataset] -> [image and data preprocessing] -> [load into pre-trained ViT model]
|
v
[split data into test/train]
|
v
[fine-tuning on the mammography dataset]
|
v
[performance evaluation on test set]
|
v
[trained model to classify a mammogram as normal/benign/malignant]
|
v
[use model for diagnosing new images + display the result]
```







# Identificarea cancerului de san
## Echipa 
- Gal Daria-Cristiana
- Găvriluț Maria-Teodora

## Scop
Dezvoltarea unui sistem inteligent care să ajute medicii în diagnosticarea timpurie a cancerului de san, crescand astfel sansele obtinerii unui tratament eficient.

## Problema abordata
Detectarea cancerului de sân în mamografii este o problemă critică în imagistica medicală. Datorită asemănărilor vizuale între leziunile benigne și maligne, acestea pot fi greu de diferențiat cu ochiul liber, ceea ce duce la posibile erori de interpretare.

## Solutia propusa
Soluția propusă implică folosirea modelelor de tip Transformer (ViT) pentru clasificarea automata a mamografiilor in normal, benign sau malign. 
Modelul este antrenat pe setul de date MIAS, care contine imagini mamografice in format PGM (grayscale) si date cu privire la tipul, localizarea si dimensiunea leziunilor.
In urma antrenarii, modelul este capabil sa clasifice automat o imagine noua, afisandu-se pe ecran un mesaj de tipul: "Imaginea [nume_imag].pgm este clasificata ca: [diagnostic]".

## Schematizare solutie propusa
```
[set de date MIAS] -> [preprocesare imagini si date] -> [incarcare in model ViT pre antrenat]
                                    |
                                    v
                      [impartire date in test/train]
                                    |
                                    v
              [fine-tuning pe setul de date cu mamografii]
                                    |
                                    v
                 [evaluare performanta pe setul de test]
                                    |
                                    v
     [model antrenat sa clasifice o mamografie in normal/benign/malign]
                                    |
                                    v
  [utilizare model pentru diagnosticare imagini noi + afisarea rezultatului obtinut]
```

