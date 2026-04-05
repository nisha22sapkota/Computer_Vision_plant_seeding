1 # 🌱 Plant Seedlings Classification — CNN                                 
    2 ### Computer Vision · Deep Learning · Convolutional Neural Network
    3
    4 ![Python](https://img.shields.io/badge/Python-3.12-blue?style=flat-squa
      re&logo=python)
    5 ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.19-orange?style
      =flat-square&logo=tensorflow)
    6 ![Keras](https://img.shields.io/badge/Keras-3.10-red?style=flat-square&
      logo=keras)
    7 ![Status](https://img.shields.io/badge/Status-Completed-brightgreen?sty
      le=flat-square)
    8
    9 ---
   10
   11 ## 📌 Business Context
   12
   13 The agricultural industry relies heavily on manual labor to identify pl
      ant species and distinguish crops from weeds — a time-consuming and err
      or-prone process. AI and Deep Learning offer a transformative opportuni
      ty to automate plant identification, enabling:
   14
   15 - Better crop yield decisions
   16 - Reduced manual labor
   17 - More sustainable agricultural practices
   18
   19 This project builds a **Convolutional Neural Network (CNN)** to classif
      y plant seedling images into 12 species, automating what previously req
      uired expert human judgment.
   20
   21 ---
   22
   23 ## 🎯 Objective
   24
   25 Build a multi-class image classifier using CNNs that can:
   26 - Accurately identify a plant's species from a seedling image
   27 - Distinguish between 12 different plant and weed species
   28 - Generalize well to unseen plant images
   29
   30 ---
   31
   32 ## 🌿 Species Categories (12 Classes)
   33
   34 | # | Species |
   35 |---|---|
   36 | 1 | Black-grass |
   37 | 2 | Charlock |
   38 | 3 | Cleavers |
   39 | 4 | Common Chickweed |
   40 | 5 | Common Wheat |
   41 | 6 | Fat Hen |
   42 | 7 | Loose Silky-bent |
   43 | 8 | Maize |
   44 | 9 | Scentless Mayweed |
   45 | 10 | Shepherd's Purse |
   46 | 11 | Small-flowered Cranesbill |
   47 | 12 | Sugar Beet |
   48
   49 ---
   50
   51 ## 📂 Dataset
   52
   53 - **Source:** Aarhus University Signal Processing Group + University of
       Southern Denmark
   54 - **Format:** Images pre-converted to `plants_images.npy` for seamless
      loading
   55 - **Labels:** `plants_labels.csv`
   56 - **Task:** 12-class image classification
   57
   58 ---
   59
   60 ## 🧠 Model Architecture
   61
   62 **Convolutional Neural Network (CNN)** built with TensorFlow / Keras:
   63
   64 - Input layer → image arrays (normalized)
   65 - Multiple **Conv2D** layers with ReLU activation
   66 - **MaxPooling2D** layers for spatial downsampling
   67 - **Dropout** layers to prevent overfitting
   68 - **Flatten** → **Dense** layers
   69 - Output: **Softmax** (12 classes)
   70
   71 ---
   72
   73 ## ⚙️  Pipeline
   74
   75 ```
   76 Raw Images (.npy)
   77       ↓
   78 Preprocessing (normalization, reshaping)
   79       ↓
   80 Image Augmentation
   81       ↓
   82 CNN Model Training
   83       ↓
   84 Evaluation (accuracy, loss curves)
   85       ↓
   86 Predictions on test set
   87 ```
   88
   89 ---
   90
   91 ## 📊 Visualizations
   92
   93 The notebook includes:
   94 - Sample images from each of the 12 species
   95 - Class distribution plot
   96 - Training vs. validation accuracy curves
   97 - Training vs. validation loss curves
   98 - Confusion matrix
   99 - Sample predictions with true vs. predicted labels
  100
  101 ---
  102
  103 ## 🛠 Tech Stack
  104
  105 | Tool | Purpose |
  106 |---|---|
  107 | Python 3.12 | Core language |
  108 | TensorFlow 2.19 | Deep learning framework |
  109 | Keras 3.10 | Model building API |
  110 | NumPy | Image array manipulation |
  111 | Matplotlib | Visualization |
  112 | Google Colab | GPU-accelerated training |
  113
  114 ---
  115
  116 ## 🔗 Live Notebook
  117
  118 👉 **[View Full Notebook](https://nisha22sapkota.github.io/Plant-Seedli
      ngs-CNN)**
  119
  120 ---
  121
  122 ## 🚀 How to Run
  123
  124 ```bash
  125 # Clone the repo
  126 git clone https://github.com/nisha22sapkota/Plant-Seedlings-CNN.git
  127 cd Plant-Seedlings-CNN
  128
  129 # Install dependencies
  130 pip install tensorflow numpy matplotlib
  131
  132 # Open the notebook
  133 jupyter notebook
  134 ```
  135
  136 ---
  137
  138 ## 👩‍💻 Author
  139
  140 **Nisha Sapkota**
  141 MS Business Analytics · UT Austin McCombs School of Business
  142
  143 [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=f
      lat-square&logo=linkedin)](https://www.linkedin.com/in/nisha-sapkota-ai
      data/)
  144 [![Portfolio](https://img.shields.io/badge/Portfolio-thatgirl.ai-bright
      green?style=flat-square)](https://thatgirl.ai)
