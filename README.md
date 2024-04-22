# MRI Preprocessing: DL implementation in segmentation
I worked on this code during my internship at CNALab, starting in January 2022. My principal investigator (Jong-Min Lee) and a graduate student (Seonggyu Kim) oversaw the project, and we had meetings every other week to track progress. The duration of this project spanned approximately 8 months and contributed towards fulfilling my graduation requirements.

## Background info - about MRI and preprocessing
MRI (Magnetic Resonance Imaging) scans give us a lot of details about the human body, helping us spot different tissues or problems. After the MRI machine emits a strong magnetic field and then turns off, it picks up radiofrequency signals that pass through our body. The resulting MRI images show different physical properties with varying intensity. But we can't just analyze these images as they are. That's why we need preprocessing.

### About the project
During that time, our lab was gearing up to establish a complete preprocessing pipeline using deep learning. This included tasks such as defacing, augmentation, harmonization, tissue classification, and others. 
The part I was asked to work on was tissue classification. I was tasked with developing a model to predict labels for new MRI images. Initially, the focus was on implementing this process for T1 images. Later on, I was also assigned the responsibility of training the model on another modality—T2 images. 
This second task was somewhat experimental, as traditional software typically relies solely on T1 images.

### Dataset

### Training data: Label Creation

### Unet: Training model

### Result

## Analysis & Plans




