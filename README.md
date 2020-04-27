# COVID19-AI-Detection
Open source Artificial Intelligence (CNNs &amp; GANs) for COVID-19 Pneumonia detection/early detection.

Detects Covid-19 Pneumonia signs from CT Scan Images by a CNN Model. The model have a uniform dataset of 764 Images of CT Scan which consist 349 Images of Covid-19 Pneumonia affected patients and remaining shows normal patient scans.

Here are some CT-Scans of lungs:

COVID19 Patient Scan:

![alt text](https://github.com/aniruddh-1/AI-Classification/blob/0.1.0/Media/Images/covid19_ct_scan.png "CT Scan1")






Normal Patient Scan:

![alt text](https://github.com/aniruddh-1/AI-Classification/blob/0.1.0/Media/Images/normal_ct_scan.png "CT Scan2")

The dataset was taken from the following [source](https://github.com/UCSD-AI4H/COVID-CT/tree/master/Images-processed)

You can also download the dataset directly from above link or can go through our dataset where we have indexed all the images and converted them into same format(PNG).
We have used tensorflow library for training a binary classification model of CT Scans using Convolutional Neural Network. The graph of model is as follows:

![alt text](https://github.com/aniruddh-1/AI-Classification/blob/0.1.0/Media/Images/cnn_architecture.png "CNN")

We have also uploaded 2 trained models on above graphs:
* Model 1: Validation Accuracy - 80.82%, Validation Loss - 50.10%
* Model 2: Validation Accuracy - 78.00%, Validation Loss - 47.28%

As the dataset of CT Scans of COVID19 patients is limited, the model seems to overfit, so you can also contribute by sharing any ideas or providing more dataset for this repository by sending the information on our [email](https://github.com/COVID-19-AI-Research-Project).

=======
# Peter Moss COVID-19 AI Research Project

## COVID-19 AI Classification
[![COVID-19 AI-Classification](Media/Images/covid-19-ai-classification.png)](https://github.com/COVID-19-AI-Research-Project/AI-Classification)

[![CURRENT VERSION](https://img.shields.io/badge/CURRENT%20VERSION-0.0.0-blue.svg)](https://github.com/COVID-19-AI-Research-Project/AI-Classification/tree/0.0.0) [![CURRENT DEV BRANCH](https://img.shields.io/badge/CURRENT%20DEV%20BRANCH-0.1.0-blue.svg)](https://github.com/COVID-19-AI-Research-Project/AI-Classification/tree/0.1.0)

# Introduction

The **Peter Moss COVID-19 AI Research Project AI Classification** repository is a collection of open source Artificial Intelligence for COVID-19 detection/early detection created by our team. The projects in this repository focus on using AI for classifying COVID-19 using computer vision, including Convolutional Neural Networks (CNN) & Generative Adversarial Networks (GAN).

&nbsp;

# COVID-19 AI Classification Projects

Below you will find details of the projects in this repository:

|ID | Project | Description | Author |
|---|---------|-------------|--------|
| 1 | [COVID-19 Pneumonia detection/early detection](Projects/1/ "COVID-19 Pneumonia detection/early detection") | Detects Covid-19 Pneumonia signs from CT Scan Images by a CNN Model. The model have a uniform dataset of 764 Images of CT Scan which consist 349 Images of Covid-19 Pneumonia affected patients and remaining shows normal patient scans. | [Aniruddh Sharma](https://www.leukemiaresearchassociation.ai.com/team/AniruddhSharma "Aniruddh Sharma") |

&nbsp;

# Contributing

The Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research project encourages and welcomes code contributions, bug fixes and enhancements from the Github.

Please read the [CONTRIBUTING](CONTRIBUTING.md "CONTRIBUTING") document for a full guide to forking our repositories and submitting your pull requests. You will also find information about our code of conduct on this page.

## Contributors

- **PROJECT AUTHOR:** [Adam Milton-Barker](https://www.leukemiaresearchassociation.ai.com/team/adam-milton-barker "Adam Milton-Barker") - [Peter Moss Leukemia AI Research](https://www.leukemiaresearchassociation.ai "Peter Moss Leukemia AI Research") Founder & Intel Software Innovator, Sabadell, Spain

- **PROJECT AUTHOR:** [Aniruddh Sharma](https://www.leukemiaresearchassociation.ai.com/team/AniruddhSharma "Aniruddh Sharma") - [Peter Moss Leukemia AI Research](https://www.leukemiaresearchassociation.ai "Peter Moss Leukemia AI Research") R&D, Ahmedabad, India

&nbsp;

# Versioning

We use SemVer for versioning. For the versions available, see [Releases](releases "Releases").

&nbsp;

# License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE "LICENSE") file for details.

&nbsp;

# Bugs/Issues

We use the [repo issues](issues "repo issues") to track bugs and general requests related to using this project. See [CONTRIBUTING](CONTRIBUTING.md "CONTRIBUTING") for more info on how to submit bugs, feature requests and proposals.