### Projects
***
#### Tackling Challenges and Enhancing Disease Diagnosis in Medical Imaging with Deep Metric Learning
Master thesis supervised by Prof. Ommer at LMU Munich and Heidelberg University (Apr. 2022 - Apr. 2023)

<p style='text-align: justify;'>
For my master thesis novel machine learning approaches were created such as disease-conditioned similarity networks that lead to en par or outperforming state-of-the-art approaches. X-ray specific challenges like image variability, class imbalance, and domain shifts were addressed. The master thesis is building on the work that has been done on classifying X-ray images in my bachelor thesis.
</p>

#### Conditional Similarity Learning for Multilabel Classification of Medical Images
Bachelor thesis supervised by Prof. Ommer at Heidelberg University (Jan. - Jul. 2021)

<p style='text-align: justify;'>
This thesis follows the idea of making a neural network learn a <i>disentangled</i> embedding space for medical images 
displaying lung diseases. The embedding space is therefore divided into one subspace per disease. This approach increases
the classification performance and enables the NN to encompass information about the similarity of different diseases. <br>
The work on this project has been continued afterwards as a student assistant. The classification performance has been
further improved and new techniques have been applied such as proxy anchor loss. The results are planned to be 
published in 2023/2024.
</p>

Selection of papers that have been used or reimplemented for the theses:
* Wang, X. et al. *Multi-similarity loss with general pair weighting for deep metric learning.* 2019.
IEEE/CVF Conference on Computer Vision and Pattern Recognition.
* Veit, A., Belongie, S., & Karaletsos, T. *Conditional similarity networks.* 2017.
IEEE conference on computer vision and pattern recognition.

Selection of papers that have been used or reimplemented as a student assistant:
* Movshovitz-Attias, Y. et al. *No fuss distance metric learning using proxies.* 2017.
IEEE International Conference on Computer Vision.
* Iscen, A. et al. *Mining on manifolds: Metric learning without labels.* 2018.
IEEE Conference on Computer Vision and Pattern Recognition.
* Kazemzadeh, S. et al. *Deep Learning Detection of Active Pulmonary Tuberculosis at Chest Radiography Matched the Clinical Performance of Radiologists.* 2022.
 Radiology, 212213.

Applied machine learning techniques: unsupervised, weakly-supervised and supervised techniques, deep metric learning; for more see papers \
Programming language and frameworks: Python, TensorFlow, Jax, Pandas and others

---

#### Bias Free AI
Hackathon challenge by IBM at Q-Summit Mannheim (Oct. 2021)

<p style='text-align: justify;'>
This project has been implemented in a team of 3 over the course of 2 days. The focus was laid on a bias-free and fair
approach to assign teachers to a school. This was achieved by first clustering schools (via k-means), second allocating
teachers to a cluster (via kNN), then balancing staffing between clusters with respect to teacher and school preferences
(e.g. rural/urban, experience...) and lastly the teachers where allocated to a specific school. <br>
This approach won the 2nd place for the challenge presented by IBM.
</p>

Applied machine learning techniques: k-means clustering, kNN classification \
Programming language and frameworks: Python, scikit-learn

---

#### Galaxy Detection and Classification in the Hubble Deep Field
Project for the "Deep Vision" course at Heidelberg University (Jul. 2020)

<p style='text-align: justify;'>
The problem formulation and solution was created in a team of 2. The problem can be separated into a classification and
detection problem. For the first part of the problem a CNN has been trained with a dataset of galaxy images and labels.
For the second part fixed-level thresholding has been performed to get bounding boxes and image cut-outs that can be fed
into the pretrained network. The result can be seen in the following picture. Only a fraction of the whole image is shown.
</p>

![Hubble deep field classfication, original image by ESA/Hubble](./files/hubble_deep_field_classified_cutout.png)
<p style='text-align: right;'><sub><sup>Original image by ESA/Hubble</sup></sub></p>

Applied machine learning techniques: CNN classification, segmentation, bounding box approach \
Programming language and frameworks: Python, PyTorch, NumPy

---

#### Eigenfaces R package
Project for the "Programming Language R and its Applications" course at Heidelberg University (Jul. 2020)

<p style='text-align: justify;'>
This project contains the principle component analysis on a large set of images of different human faces (here: Olivetti Dataset).
The derived eigenvectors are called eigenfaces, hence the project name. Methods like this can be used for human face recognition.
More details can be found in the read me of the following
<a href="https://github.com/Osburg/eigenfaces" ><span class="uk-icon link-text" uk-icon="icon: github-alt; ratio: 1"></span><span class="link-text"> github repository</span></a>.
</p>

Applied machine learning techniques: PCA, kNN classification \
Programming language and frameworks: R, shiny, testthat

---

<a href="https://mafi2.github.io/" ><span class="uk-icon link-text" uk-icon="icon: chevron-left; ratio: 1"></span><span class="link-text">back to main page</span></a>