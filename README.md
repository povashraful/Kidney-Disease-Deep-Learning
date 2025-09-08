## This work is still under review- Details (model + code) will be open-sourced very soon !

## License

This work is for research purposes and non-commercial use only. See [Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)

# Kidney-Disease-Deep-Learning
Advanced Deep Learning Approach for the Diagnosis and Classification of Kidney Disease


ChatGPT link: https://chatgpt.com/c/6808b094-0b3c-8004-8f94-c52284e87d33 (used first email)


# Kidney Disease Classification Repository



## Hello there !👋 
This repository is a curated collection of research papers, datasets, and results related to **Kidney Disease Classification**. It is designed to help researchers gain insights into the advancements.

---

I have divided the research paper into three different years!

You can start reading from the year 2023 and onwards to get a better understanding of the advancements in the topic.

[[`2023`](https://github.com/ashrafulwork/)] 
[[`2024`](https://github.com/ashrafulwork/)] 
[[`2025`](https://github.com/ashrafulwork/)] 

### Search Keywords
To find the papers, the following keywords were used:  
- "CT KIDNEY DATASET: Normal-Cyst-Tumor and Stone"  for 2024-2025 : Searched up to the 10th page (all) of results.

The search was conducted on **Google Scholar** with the following depth:
- **2023 & 2025:** Searched up to the th page of results.
- **2024:** Searched up to the th page of results for comprehensive coverage.

---

If you want to know more about the results of existing work, go here : [[`Results`](https://github.com/ashrafulwork)] 

If you want to know more about the datasets, go here: [[`Datasets`](https://github.com/ashrafulwork/)] 

## 🤝 Contributions ()
This repository is a work in progress. 



### Architecture overview of KDDS
This architecture blends the power of convolutional neural networks (CNNs) with the global modeling capabilities of Transformers, creating a robust hybrid that is highly effective for image classification tasks. It begins with a convolutional stem to efficiently extract low-level spatial features, followed by a patch embedding layer that segments the image into fixed-size patches and projects them into an embedding space. These patch embeddings are enhanced with learnable positional encodings to retain spatial structure. Multiple transformer blocks are then stacked, providing powerful long-range dependencies. The architecture further includes hierarchical downsampling and additional transformer layers for deeper representation learning. Finally, a global average pooling and dense layers perform classification into the target categories.

This design captures both local and global patterns, making it particularly effective in domains like medical imaging, satellite imagery, and fine-grained visual recognition where both fine textures and contextual information are critical.
<img width="655" height="722" alt="image" src="https://github.com/user-attachments/assets/ddc60c61-cf9f-4720-8382-f16075a7699a" />

### Resuslt Analysis
Comparison of average precision, recall, and F1-score for different models with and without augmentation.
<img width="809" height="330" alt="image" src="https://github.com/user-attachments/assets/e798d564-25f6-4519-839f-9b68f2421572" />
ROC curve for the top 6 models implemented in this research.
<img width="833" height="518" alt="image" src="https://github.com/user-attachments/assets/a2012442-b784-4aac-b35d-0c9209ccf485" />

Comparison of model performance (Training, Validation, and Test Accuracy) with and without data augmentation.
<img width="748" height="396" alt="image" src="https://github.com/user-attachments/assets/77751c0f-a186-4273-b1a3-117d1b99eec1" />

### GradCam
The original CT images (left columns) are paired with their corresponding Grad-CAM heatmaps (right columns), which reveal the discriminative regions the model focuses on when classifying kidney conditions. Warmer colors (red and yellow) in the heatmaps denote areas of high importance, often aligning with pathological features or anatomical structures such as cysts, stones, tumors, or abnormal tissue patterns. These visual explanations enhance interpretability by confirming that the model emphasizes clinically relevant kidney regions in its decision-making process.
<img width="725" height="531" alt="image" src="https://github.com/user-attachments/assets/4bbacc06-309a-45b2-8ce2-8db15dd9f4ba" />
### Installation 
For python pip install python=3.11 For tensorflow pip install tesorflow Other dependencies pip install -r requirements.txt
### Dataset
Dataset link: https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone




Details are being prepared and will soon be updated here - 


