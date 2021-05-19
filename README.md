# Computer Vision Demo

**1. Problem:** Diagnosing a retinal optical coherence tomography (OCT), an imaging
technique for the eye retina, can be costly and can take a long time. Doctors are
expensive and scarce, but there are millions of OCT scans performed every year that
need analysis and interpretation. It is beneficial to develop a model that can accurately,
quickly, and economically diagnose OCT images of the eye. Machine Learning
algorithms can help get an accurate diagnosis so that the patient can get an accurate
treatment. Performance strategies to compute large amount of image files can help get a
quick diagnosis so that the patient can get a quick treatment. And efficient uses of
computational resources can help get an inexpensive diagnosis so that the patient can
get an inexpensive treatment.

**2. Data:** The dataset consists of 84,495 X-Ray images (about 5 GB) in JPEG format
labeled as Normal (NORMAL), choroidal neovascularization (CNV), diabetic macular
edema (DME), or multiple drusen (DRUSEN). The dataset will be acquired from
https://data.mendeley.com/datasets/rscbjbr9sj/2 (a link found from Kaggle).

**3. Approach:**

- **a. Supervised or unsupervised:** Supervised. The image labels have been checked
  three times: firstly by medical students with optometry background, secondly by
  general eye doctors, and thirdly by retinal specialist doctors with over 20 years of
  experience.
- **b. Classification or regression:** Classification. Images will be classified as either
  NORMAL, CNV, DME, or DRUSEN.
- **c. Prediction:** The model will be able to diagnose the eye by classifying the image
  when new X-Ray images are introduced.
- **d. Predictors:** X-Ray images of an eye. Unhealthy eyes are characterized by dark
  shades that represent fluids or lumps inside different parts of the retina.
- **e. Approach:** CNN is commonly used for image classification/recognition.

**4. Computational Resources:**

- **a. Processing Power (CPU):** Will use GPU.
- **b. Memory:** 64 GB RAM
- **c. Specialized hardware:** 1 GPU
