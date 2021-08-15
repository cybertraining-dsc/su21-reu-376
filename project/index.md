---
date: 2021-06-16
title: "Report: Dentronics: Classifying Dental Implant Systems by using Automated Deep Learning "
linkTitle: "Dentronics"
tags: ["project", "reu","ai", "dentistry"]
description: Artificial intelligence is a branch of computer science that focuses on building and programming machines to think like humans and mimic their actions. The proper concept definition of this term cannot be achieved simply by applying a mathematical, engineering, or logical approach but requires an approach that is linked to a deep cognitive scientific inquiry. The use of machine-based learning is constantly evolving the dental and medical field to assist with medical decision making process. In addition to diagnosis of visually confirmed dental caries and impacted teeth, studies applying machine learning based on artificial neural networks to dental treatment through analysis of dental magnetic resonance imaging, computed tomography, and cephalometric radiography are actively underway, and some visible results are emerging at a rapid pace for commercialization. Researchers have found deep convolutional neural networks to have a future place in the dental field when it comes to classification of dental implants using radiographic images.
author: Young Jamyla
github_url: https://github.com/cybertraining-dsc/su21-reu-376/edit/main/project/index.md
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
---

[![Check Report](https://github.com/cybertraining-dsc/su21-reu-376/workflows/Check%20Report/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-376/actions)
[![Status](https://github.com/cybertraining-dsc/su21-reu-376/workflows/Status/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-376/actions)
Status: final, Type: Project


Jamyla Young, [su21-reu-376](https://github.com/cybertraining-dsc/su21-reu-376), [Edit](https://github.com/cybertraining-dsc/su21-reu-376/blob/main/project/index.md)

{{% pageinfo %}}

## Abstract

Artificial intelligence is a branch of computer science that focuses on building and programming machines to think like humans and mimic their actions. The proper concept definition of this term cannot be achieved simply by applying a mathematical, engineering, or logical approach but requires an approach that is linked to a deep cognitive scientific inquiry. THe use of machine-based learning is constantly evolving the dental and medical field to assist with medical decision making process.In addition to diagnosis of visually confirmed dental caries and impacted teeth, studies applying machine learning based on artificial neural networks to dental treatment through analysis of dental magnetic resonance imaging, computed tomography, and cephalometric radiography are actively underway, and some visible results are emerging at a rapid pace for commercialization.

Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** Dental implants, Deep Learning, Prosthodontics, Implant classificiation, Artificial Intelligence, Neural Networks. 

## 1. Introduction

Dental implants are  ribbed oral protheses typically made up of biocompatible titanium to replace the missing root(s) of an absent tooth.  These dental protheses are used to support the jaw bone to prevent deterioration due to an absent root[^5]. This is referred to as bone resorption which can result to facial malformation as well as reduced oral function such as biting and chewing. These devices are composed of three elements that imitates a natural tooth function and structure.The implant which are typically ribbed and threaded to promote stability while integrating within the bone tissue. The osseointegration process usually takes 6-8 months to rebuild the bone to support the implant. An implant abutment is fixed on top of the implant to act as a base for prosthetic devices [^2]. Prefabricated abutments are manufactured in many shapes, sizes and angles depending on the location of the implant and the types of prothesis that will be attached. Dental abutments support a range of prothetic devices such as dental crowns, bridges, and dentures [^1].

Osseointegrated dental implants depend on various factors that affect the anchorage of the  implant to the bone tissue. Successful surgical anchoring techniques can contribute to long term success of implant stability. Primary stability plays a role 2 week postoperatively by achieving mechanical retention of the implant. It helps establish a mechanical microenvironment for gradual bone healing, or osseointegration-This is secondary implant stability. Bone type, implant length, implant and diameter influences primary and secondary implant stability. Implant length can range from 6mm to 20mm; however, the most common lengths are between 8mm to 15mm. Many studies suggest that implant length contribute to decreasing bone stress and increasing implant stability. Bone stress can occur at both the cortical and cancellous part of the bone. Increasing implant length will decrease stress in the cancellous part of the bone while increasing the implant diameter can decrease  stress in the cortical part of the bone[^4]. Bone type can promote positive bone stimulation around an implant improving the overall function. There are four different types: Type I, Type II, Type III, and Type IV. Type I is the most dense of them which provides more cortical anchorage but has limited vascularity. Type II is the best for osseointegration because it provides good cortical anchorage and has better vascularity than type I. Type III and IV have a thin layer of cortical bone which decrease the success rate of primary stability[^6].

Implant stability can be measured using the Implant Stability Quotient (ISQ) as an indirect indicator to determine the time frame for implant loading and prognostic indicator for implant failure [^4]. This can be measured by resonance frequency analysis (RFA) immediately after the implant has been  placed. Resonance frequency analysis is the measurement in which a device vibrates in response to frequencies in the range of 5-15 kHz. The peak amplitude of the response is then encoded into the implant stability quotient (ISQ). The clinical range of ISQ is from 55-80. High stability is >70 ISQ while medium stability is between 60-69 ISQ. Low stability is <60 ISQ[^7]. 

There are over 2000 types of  dental implant systems (DIS) that differs in diameter, length, shape, coating, and surface material properties. These devices have more than a 90% long termed survival rate which ranges more than 10 years. Inevitably, biological and mechanical complications such as fractures, low implant stability, and screw loosening can occur. Therefore, identifying the correct Dental Implant System is essential to repair or replace  the existing system. Methods and techniques that enables clear identification is insufficient [^8].

Artificial intelligence is a branch of computer science that focuses on building and programming machines to think like humans and mimic their actions. A deep convolutional neural network (DCNN) is a brach of artificial intelligence that applies multiple layers of nonlinear processing units for feature extraction, transformation, and classification of high dimensional datasets. Deep convolutional neural networks are commonly used to identify patterns in images and videos.  The structure typically consist of four types of layers: convolution, pooling, activation, and fully connected. These neural networks use images as an input to train a classifier which employs a mathematical operation called a convolution. Deep neural networks have been successfully applied in the dental field and demonstrated advantages in terms of diagnosis and prognosis. Using automated deep convolutional neural networks is highly efficient in classifying different dental implant systems compared to most dental professionals[^8].

## 2. Data sets

Researchers at Daejon Dental Hospital used automated deep convolutional neural networks to evaluate the efficacy of its ability to classify dental implant systems and compare the performance with dental professionals using radiographic images. 

11,980 raw panoramic and periapical radiographic images of dental implant systems were collected. these images were then randomly divided into 2 groups: 9584 (80%) images were selected for the training dataset and the remaining 2396 (20%) images were used as the testing dataset.

## 2.1 Dental implant classification

Dental implant systems were classified into six different types with a diameter of 3.3-5.0mm and a length of 7-13mm.

* Astra OsseoSpeed TX (Dentsply IH AB, Molndal, Sweden), with a diameter of 4.5–5.0 mm and a length of 9–13 mm;
* Implantium (Dentium, Seoul, Korea), with a diameter of 3.6–5.0 mm and a length of 8–12 mm;
* Superline (Dentium, Seoul, Korea), with a diameter of 3.6–5.0 mm and a length of 8–12 mm;
* TSIII (Osstem, Seoul, Korea), with a diameter of 3.5–5.0 mm and a length of 7–13 mm;
* SLActive BL (Institut Straumann AG, Basel, Switzerland), with a diameter of 3.3–4.8 mm and a length of 8–12 mm; 
* SLActive BLT (Institut Straumann AG, Basel, Switzerland), with a diameter of 3.3–4.8 mm and a length of 8–12 mm.

## 2.2 Deep Convulutional Neural Network

Using Neuro-T to automatically select the model and optimize hyper-parameter. During training and inference, the automated DCNN automatically creates effective deep learning models and searches the optimal hyperparameters. An Adam optimizer with L2 regularization was used for transfer learning. The batch size was set to 432, and the automated DCNN architecture  consisted of 18 layers with no dropout.

![Figure 1](https://github.com/cybertraining-dsc/su21-reu-376/raw/main/project/images/DCNN.png) 

**Figure 1**: Overview of an automated deep convolutional neural network [^8].

## 3. Results

For the evaluation, the following statistical parameters were taken into account: receiver operating characteristic (ROC) curve, area under the ROC curve (AUC), 95% confidence intervals (CIs), standard error (SE), Youden index (sensitivity + specificity − 1), sensitivity, and specificity, which were calculated using Neuro-T  and R statistical software . Delong’s method was used to compare the AUCs generated from the test dataset, and the significance level was set at p < 0.05.

The accuracy of the automated DCNN abased on the AUC, Youden index, sensitivity, and specificity
for the 2,396 panoramic and periapical radiographic images were 0.954(95% CI = 0.933–0.970,
SE = 0.011), 0.808, 0.955, and 0.853, respectively. Using only panoramic radiographic images (n = 1429),
the automated DCNN achieved an AUC of 0.929 (95% CI = 0.904–0.949, SE = 0.018, Youden index = 0804,
sensitivity = 0.922, and specificity = 0.882), while the corresponding value using only periapical
radiographic images (n = 967) achieved an AUC of 0.961 (95% CI = 0.941–0.976, SE = 0.009, Youden
index = 0.802, sensitivity = 0.955, and specificity = 0.846). There were no significant differences in
accuracy among the three ROC curves.

![Figure 2](https://raw.githubusercontent.com/cybertraining-dsc/su21-reu-376/main/project/images/results.png) 

**Figure 2**: The accuracy of the automated DCNN for the test dataset did not show a significant difference among the three ROC three ROC curves based on DeLong’s method [^8].

The Straumann SLActive BLT implant system has a relatively large tapered shape compared to other types of DISs. Thus, the automated DCNN (AUC = 0.981, 95% CI = 0.949–0.996). However, for the Dentium Superline and Osstem TSIII implant systems that do not have conspicuous characteristic elements with a tapered shape, the automated DCNN classified correctly with an AUC of 0.903 (95% CI = 0.850–0.967) and 0.937 (95% CI = 0.890–0.967)

![Figure 3](https://raw.githubusercontent.com/cybertraining-dsc/su21-reu-376/main/project/images/results2.png)

**Figure 3 (a-f)**: Performance of the automated DCNN and comparison with dental professionals for
classification of six types of DIS [^8]

## 4. Conclusion

Nonetheless, this study has certain limitations. Although six types of DISs were selected from three different dental hospitals and categorized as a dataset, the training dataset was still insufficient for clinical practice. Therefore, it is necessary to build a high-quality and large-scale dataset containing different types of DISs. If time and cost are not limited, the automated DCNN can be continuously trained and optimized for improved accuracy. Additionally, the automated DCNN regulates the entire process, including appropriate model selection and optimized hyper-parameter adjustment. The automated DCNN can help clinical dental practitioners to classify various types of DISs based on dental radiographic images. Nevertheless, further studies are necessary to determine the efficacy and feasibility of applying the automated DCNN in clinical practice.

## 5. Acknowledgments

1. Carlos Theran, REU Instructor

2. Yohn Jairo Parra, REU Instructor

3. Gregor von Laszewski, REU Instructor

4. Victor Adankai, Graduate Student

5. REU Peers

6. Florida Agricultural and Mechanical University

## 6. References

[^1]: Bataineh, A. B., &amp; Al-Dakes, A. M. (2017, January 1). The influence of length of implant on primary stability: An in vitro study using resonance frequency analysis. Journal of clinical and experimental dentistry. <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5268121/>

[^2]: Ghidrai, G. (n.d.). Dental implant abutment. Stomatologia pe intelesul tuturor. <https://www.infodentis.com/dental-implants/abutment.php>

[^3] Gregor von Laszewski, Cloudmesh StopWatch and Benchmark from the Cloudmesh Common Library, [GitHub <https://github.com/cloudmesh/cloudmesh-common>

[^4]: H, H., G, W., &amp; E, H. (2020). The clinical significance of implant Stability QUOTIENT (ISQ) MEASUREMENTS: A literature review. Journal of oral biology and craniofacial research. <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7494467/>

[^5]: Karras, Spiro, Look at the structure of dental implants.(2020, September 2).
   <https://www.drkarras.com/a-look-at-the-structure-of-dental-implants/>

[^6]: Li, J., Yin, X., Huang, L., Mouraret, S., Brunski, J. B., Cordova, L., Salmon, B., &amp; Helms, J. A. (2017, July). Relationships among Bone QUALITY, IMPLANT Osseointegration, and WNT SIGNALING. Journal of dental research <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5480808/>

[^7]: Möhlhenrich, S. C., Heussen, N., Modabber, A., Bock, A., Hölzle, F., Wilmes, B., Danesh, G., &amp; Szalma, J. (2020, July 24). Influence of bone density, screw size and surgical procedure on orthodontic mini-implant placement – part b: Implant stability. International Journal of Oral and Maxillofacial Surgery. <https://www.sciencedirect.com/science/article/abs/pii/S0901502720302496>

[^8]: Lee JH, Kim YT, Lee JB, Jeong SN. A Performance Comparison between Automated Deep Learning and Dental Professionals in Classification of Dental Implant Systems from Dental Imaging: A Multi-Center Study. Diagnostics (Basel). 2020 Nov 7;10(11):910. doi: 10.3390/diagnostics10110910. PMID: 33171758; PMCID: PMC7694989.
