# **Water Quality Classification Using Neural Networks**  

## **Group Members**  
- **Denys Ntwaritaganzwa**  
- **John Akech**  
- **Merveil Kangabire**  

## **Project Overview**  
This project builds a **neural network-based classification model** to predict **water potability** using a provided dataset. Each team member applies **different optimization techniques**, allowing for a meaningful performance comparison.  

---

## **Dataset**  
We use the **[Water Quality and Potability Dataset](https://drive.google.com/file/d/1VXHjV4Hi7d__I9v2KYudh32OVud3aEvm/view)** from **Kaggle**.  

---

## **Repository Structure**  
```
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
```
---

## **Installation**  
To set up the project environment, run:  
```bash
pip install -r requirements.txt
```
---

## **Data Preprocessing**  
✔ Load dataset and handle missing values  
✔ Normalize features for better training performance  
✔ Split data into **70% training, 15% validation, and 15% testing**  

---

## **Model Training**  
Each member designed a **unique model** with different **optimization techniques**:  

- **Denys Ntwaritaganzwa** → **Adam optimizer** with **L1_L2 regularization**  
- **John Akech** → **RMSprop optimizer** with **L2 regularization**  
- **Merveil Kangabire** → **SGD optimizer** with **L1**  

Each model was **trained and evaluated separately**.  

---

## **Model Evaluation**  
Each model was compared based on:  
✔ **Accuracy**  
✔ **F1 Score**  
✔ **Precision & Recall**  
✔ **Loss Analysis**  

**Performance Summary Table:**  

| Engineer             | Regularizer    | Optimizer         | Early Stopping | Dropout Rate | Accuracy | F1 Score | Recall | Precision |
|----------------------|--------------- |-------------------|----------------|--------------|----------|----------|--------|-------------|
| Denys Ntwaritaganzwa | L1_L2          | Adam              | Yes            | 0.3          | X.XX%    | X.XX     | X.XX   | X.XX        |
| John Akech           | L2             | RMSprop           | Yes            | 0.2          | X.XX%    | X.XX     | X.XX   | X.XX        |
| Merveil Kangabire    | L1             | SGD + Momentum    | Yes            | 0.1          | X.XX%    | X.XX     | X.XX   | X.XX        |

---

## **Video Submission**  
We will include a **video walkthrough** explaining our models, optimizations, and results. **[Video Link - To be added]**  

---

## **Contribution & Documentation**  
✔ Each member defined, trained, and evaluated their model  
✔ Commits reflect **meaningful contributions**  
✔ The final report includes **methodology, findings, and key insights**  

---

## **Conclusion**  
This project **successfully applies neural networks** to classify **water potability**, demonstrating the impact of **different optimization techniques**. The comparison provides insights into **model performance and areas for improvement**. 🚀
