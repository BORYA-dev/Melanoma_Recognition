# Investigation-of-Intelligent-Recognition-of-Melanoma-Based-on-Systematic-Image-Feature-Extraction

## Introduction 
## Data Source 
This project utilized various datasets of melanoma images: 40 from the PH2 dataset [1], 70 from MED-NODE [2], 162 from the ISIC Challenge [3], 584 from Kaggle [4], and 32,042 non-melanoma images, totaling 856 melanoma images and 32,042 non-melanoma images. 

1. ADDI Project.(2013) PH² Database. [Data file](https://www.fc.up.pt/addi/ph2%20database.html)
2. Giotis, N. Molders, S. Land, M. Biehl, M.F. Jonkman and N. Petkov: "MED-NODE: A computer-assisted melanoma diagnosis system using non-dermoscopic images", Expert Systems with Applications, 42 (2015), 6578-6585.
3. ISIC Challenge. (2018). ISIC Challenge Datasets. [Data file](https://challenge.isic-archive.com/data/#2018)
4. Kaggle. (2020). SIIM-ISIC Melanoma Classification. [Data file](https://www.kaggle.com/competitions/siim-isic-melanoma-classification/data)

## Tools and statistical methods Used
- **Python**:
- **statistical methods**:
1. Data Sampling 
2. The research flow chart 
![image](https://github.com/BORYA-dev/Investigation-of-Intelligent-Recognition-of-Melanoma-Based-on-Systematic-Image-Feature-Extraction/blob/main/report/flow%20chart.png)

## Project Structure
```plaintext
Investigation-of-Intelligent-Recognition-of-Melanoma-Based-on-Systematic-Image-Feature-Extraction/
├── data/
    └── test.jpg  # the sample image
├── report/
    ├── flow chart.png  
    └── report_Chinese.pdf  # Final Report_Chinese Version    
├── code/ 
    ├── model/ 
        ├── CNN_model.ipynb # CNN model building
        └── ML_models.ipynb # ML_models building i.e Random Forest, SVM,..... 
    └── Feature_extraction.ipynb # the feature extraction codes
└── README.md         # This file.
```
## How to Use
If you want to check the feature extraction part, 

1. **Install Python** : Download Python Software 
2. **Download the necessary files** : 
    - code/Feature_extraction.ipynb (the feature extraction script)
    - data/test.jpg (the sample image)
3. **Run the feature extraction script** : Execute the file to see the explicit steps of image processing. 

For model training, you can check code/Model. However, we only providethe code since the original dataset is too large to be included. 


## Contact Information
For any further discussion or collaboration opportunities, please reach out to me at:
- Email: [eric304849002@gmail.com](mailto:eric304849002@gmail.com)
- GitHub: [BORYA-dev](https://github.com/BORYA-dev)
