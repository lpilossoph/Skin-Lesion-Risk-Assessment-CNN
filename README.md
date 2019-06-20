# Skin Lesion Image Risk Classifier - A Dermatologic Assessment Tool for Patients and Clinicians 
![SL](https://www.platinumdermatology.com.au/wp-content/uploads/2015/04/header_0007_Skin-assessment-_-analysis.jpg)

# Motivation

   If you've ever had a new skin discoloration appear on your body, you know it can be frightening; Is it nothing? Is it cancerous? Should it be checked out? Studies have shown that many patients delay seeking care for a number of reasons, some of which include convenience and proximity to a health care specialist, especially for those who reside in rural areas. 
   
   Other studies have shown that unecessary biopsies to determine malignancy are as high as 60%. Clinicians base their decision to biopsy primarily on clinical judgement alone. Machine learning has unlocked the ability to assess with relatively high accuracy the image of a suspicious skin lesion in order to provide a risk assessment tool to complement clinical judgement.

# Methods

Utilizing the HAM10000 dataset, a vast collection of multi-source dermatoscopic images of malignany and benign skin lesions, I was able to build a neural network that classified skin lesion images as either low-risk or severe-risk with relatively high accuracy (88%). I utilized both a pre-trained network as well as a network that I built from scratch, which handled such issues as class-imbalance, overfitting, and minimizing false negatives, to name a few. 

# Use Cases

The ability to classify skin lesions by relative risk would be extremely helpful to clinicians as an added resource to their own clinical judgement. Utilization of this tool by clinicians could cut down on healthcare costs by limiting the number of unnecessary skin biopsies performed on patients. Additionally, those patients who reside in rural areas where a trip to the dermatologist may inconveniently mean taking an entire day from work could benefit from utilization of this tool as well. Theoretically, any lesion not assessed as low-risk would be taken seriously and would lead to scheduling an appointment to assess the lesion further and to determine next steps. 
