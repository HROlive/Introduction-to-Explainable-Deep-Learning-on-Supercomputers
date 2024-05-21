# Introduction to Explainable Deep Learning on Supercomputers

## Table of Contents
1. [Description](#description)
2. [Information](#information)
3. [Subjects](#subjects)
4. [Requirements and Setup](#requirements)
5. [Certificate](#certificate)

<a name="descripton"></a>
## Description

Throughout the course, participants will develop a solid foundational understanding of XAI, primarily emphasizing how XAI methodologies can expose latent
biases in datasets and reveal valuable insights.
The course starts with a broad overview of XAI, setting the stage for a deep dive into cutting-edge model-agnostic interpretation techniques. As the course progresses, we shift our focus to model-specific post-hoc interpretation methods. Through immersive training, participants will learn to interpret machine learning algorithms and unravel the intricacies of deep neural networks, such as convolutional neural networks (CNN) and transformers. They will also become skilled in applying these techniques to various data formats, encompassing tabular data, images, and 1D data.
In addition to theoretical insights, participants will engage in hands-on practical sessions to apply these techniques effectively.
Take advantage of this opportunity to enhance your expertise in XAI and acquire the skills needed to navigate the intricate landscape of AI interpretability. Enroll now and unlock the potential of XAI!

This repository provides a collection of self-explanatory tutorials for different model-agnostic and model-specific XAI methods. Each tutorial comes in a Jupyter Notebook with practical exercises. In addition, we provide useful background information on those methods in this documentation.

<a name="information"></a>
## Information

The overall goals of this course were the following:
> - Gain an appreciation for the significance of XAI.
> - Explore the available model-agnostic and model-specific XAI methodologies.
> - Acquire the skills to interpret the results and visualizations of these methodologies through practical exercises.
> - Master the skill of applying XAI techniques to diverse data types, including tabular data, images, and 1D data.
> - Develop the ability to discern the most appropriate XAI method for a given task.

More detailed information and links for the course can be found on the [course website](https://xai-tutorials.readthedocs.io/en/latest/).

<a name="subjects"></a>
## Subjects

The subjects covered during this course are the following:

* Day 1 - XAI for Random Forest 
    + Tutorial_PermutationFeatureImportance
    + Tutorial_SHAP_intro
    + Tutorial_LIME
    + Tutorial_FGC
    + Tutorial_XAI_for_RandomForest
    + Shapley Values Exercise
    
* Day 2 - XAI for CNN:
    + Model-CNN-Feature Visualization
    + Tutorial_GradCAM_for_Images
    + Tutorial_GradCAM_for_Signals
    + Tutorial_LIME_images
    + Tutorial_SHAP_images
    + Tutorial_XAI_for_ImageAnalysis

    
* Day 3 - XAI for Transformers:
    + Tutorial_Trasformers
    + Tutorial_Attention_maps_for_text
    + Tutorial_VIT
    + Tutorial_Attention_maps_for_images

<a name="requirements"></a>
## Requirements and Setup

It is possible to either create an environment and install all the necessary packages locally (using the requirements.txt file) or to execute the notebooks on the browser, by clicking the 'Open in Colab' button. This second option doesn't require any further installation, but the user must have access to a Google account.

If you prefer to run the notebooks on your device, create a virtual environment using the requirements.txt file:
```
conda create -n XAI-Course-2024 python=3.9
conda activate XAI-Course-2024
pip install -r requirements.txt
```

Once your environment is created, clone `Juelich-2024` brach branch of the repo using the following command:

```
git clone --branch Juelich-2024 https://github.com/HelmholtzAI-Consultants-Munich/XAI-Tutorials.git
```

<a name="certificate"></a>
## Certificate

The certificate for the course can be found below:

["Introduction to Explainable Deep Learning on Supercomputers" - Jülich Supercomputing Centre (JSC)]() (Issued On: May 2024)
