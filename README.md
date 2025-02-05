# **Water Quality Classification Using Neural Networks**  

## **Group Members**  

**1. Denys Ntwaritaganzwa**  
**2. John Akech**  
**3. Merveille Kangabire**  

## **Project Overview**  
This project builds a **neural network-based classification model** to predict **water potability** using a provided dataset. Each team member applies **different optimization techniques**, allowing for a meaningful performance comparison.  


## **Dataset**  
We use the **[Water Quality and Potability Dataset](https://drive.google.com/file/d/1VXHjV4Hi7d__I9v2KYudh32OVud3aEvm/view)** from **Kaggle**.  


## **Repository Structure**  

├── data/

│   ├── water_potability.csv

├── notebooks/

│   ├── data_preprocessing.ipynb

│   ├── model_training.ipynb

│   ├── evaluation.ipynb

├── src/

│   ├── model_denys.py

│   ├── model_john.py

│   ├── model_merveil.py

├── README.md

## **Installation**  
To set up the project environment, run:  

pip install -r requirements.txt

## **Data Preprocessing**  
✔ Load dataset and handle missing values  
✔ Normalize features for better training performance  
✔ Split data into **70% training, 15% validation, and 15% testing**  

## **Model Training**  
Each member designed a **unique model** with different **optimization techniques**:  

- **Denys Ntwaritaganzwa** → **Adamax optimizer** with **L1_L2 regularization**  
- **John Akech** → **Adam optimizer** with **L2 regularization**  
- **Merveille Kangabire** → **RMSprop optimizer** with **L1 and L2**  

Each model was **trained and evaluated separately**.  

## **Model Evaluation**  

Each model was compared based on:  

✔ **Accuracy**  
✔ **F1 Score**  
✔ **Precision & Recall**  
✔ **Loss Analysis**  

**Performance Summary Table:**  

| Engineer             | Regularizer    | Optimizer         | Early Stopping | Dropout Rate | Accuracy | F1 Score | Recall | Precision |
|----------------------|--------------- |-------------------|----------------|--------------|----------|----------|--------|-------------|
| Denys Ntwaritaganzwa | L1_L2          | Adam              | Yes            | 0.4          | 68.9%    | 0.471    | 0.368  | 0.654       |
| John Akech           | L2             | Adam              | Yes            | 0.2          | X.XX%    | X.XX     | X.XX   | X.XX        |
| Merveil Kangabire    | L1             | RMSprop           | Yes            | 0.4          | 86.7%    | 0.85     | 0.78   | 0.92        |

---

## **Video & Docummentation Submission **  

We will include a **video walkthrough** explaining our models, optimizations, and results. **[Video Link](https://docs.google.com/document/d/1Uhbf4agxt9FgbT0OUXpSVcmpcSAuEm-oN4OuwbgGF0I/edit?usp=sharing)** and **[Documentation Link](https://docs.google.com/document/d/1Uhbf4agxt9FgbT0OUXpSVcmpcSAuEm-oN4OuwbgGF0I/edit?usp=sharing)**

## **Contribution & Documentation**  

✔ Each member defined, trained, and evaluated their model 

✔ Commits reflect **meaningful contributions**  and they are in 3 different branches those are:

**[Denys_dntwaritag](https://github.com/MKangabire/Water_potability/blob/Denys_dntwaritag/Denys_Ntwaritaganzwa's_formative_II.ipynb)**,

**[Aroma](https://github.com/MKangabire/Water_potability/blob/AROMA/Water_Quality_Classification_Model_Using_Neural_Networks.ipynb)**,

**[Merveille](https://github.com/MKangabire/Water_potability/blob/Merveille/water_potability_.ipynb)**. 

✔ The final report includes **methodology, findings, and key insights**  

## **Conclusion**  

This project **successfully applies neural networks** to classify **water potability**, demonstrating the impact of **different optimization techniques**. The comparison provides insights into **model performance and areas for improvement**. 
