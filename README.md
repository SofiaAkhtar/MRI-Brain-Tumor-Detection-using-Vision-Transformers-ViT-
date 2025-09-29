# MRI Brain Tumor Detection using Vision Transformers (ViT)

## Overview
This is an ongoing major project focused on **automated brain tumor detection from MRI scans** using **Vision Transformer (ViT) architectures**.  
The project explores multiple approaches to enhance accuracy, efficiency, and generalization, combining preprocessing, data augmentation, and advanced optimization techniques.

## Project Workflow
1. **Dataset**
   - MRI Brain Tumor Dataset  
   - Images preprocessed using **CLAHE** (Contrast Limited Adaptive Histogram Equalization) and resizing.

2. **Preprocessing & Data Splitting**
   - CLAHE applied to enhance contrast in MRI images.  
   - Dataset split into:
     - Training: 64%  
     - Validation: 16%  
     - Testing: 20%  

3. **Data Augmentation**
   - Rotation  
   - Flipping  
   - GAN-based synthetic data generation  

4. **Modeling Approaches**
   - **Idea 1:** ViT for feature extraction → PCA for dimensionality reduction → classifiers (SVM, Random Forest, KNN) → ensemble voting.  
   - **Idea 2:** Lightweight ViT → Multi-Layer Perceptron (MLP) classifier.  
   - **Idea 3:** Hyperparameter optimization using metaheuristic algorithms (Particle Swarm Optimization (PSO) and Genetic Algorithm (GA)).  

## Current Progress
- Completed **preprocessing pipeline** (CLAHE + resizing).  
- Implemented **data augmentation** to increase dataset diversity.  
- Model design and optimization currently in development.  

## Tools & Technologies
- **Programming Language:** Python  
- **Frameworks/Libraries:** TensorFlow, Keras, NumPy, Pandas, OpenCV  
- **Machine Learning Techniques:** Vision Transformer (ViT), PCA, MLP, SVM, Random Forest, KNN, PSO, GA  

## Future Work
- Train ViT-based models with different strategies (PCA + ensemble, lightweight ViT + MLP).  
- Perform hyperparameter tuning with PSO/GA.  
- Evaluate performance on test set using accuracy, precision, recall, and F1-score.  

## Contributors
- **Sofia Akhtar** (Lead Developer)   

## License
This project is developed for academic and research purposes.  
