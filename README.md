# Phishing-URL-Detection-Hybrid-AI
Hybrid AI-based Phishing URL Detection using multi-source datasets, CFS feature selection, and a combined RF–MLP–Residual Attention Neural Network achieving 99.99% accuracy. Includes full methodology, experiments, ablation study, graphs, and IEEE-format research paper.


# Hybrid AI-Based Phishing URL Detection Framework  
### Multi-Source Data • CFS Feature Selection • RF + MLP + Residual Attention Neural Network

---

## 📌 Overview  
This repository contains the complete implementation and research work for a **Hybrid AI-Based Phishing URL Detection Framework** developed as part of the **Information Security (CS-3002)** course at **FAST-NUCES Islamabad**.

The project significantly extends a base research paper by integrating **multi-source phishing datasets**, applying **Correlation-Based Feature Selection (CFS)**, and implementing a **three-stage hybrid classification architecture** combining:

- Optimized **Random Forest (RF)**
- Regularized **Multilayer Perceptron (MLP)**
- Advanced **Neural Network with Residual Connections + Attention**

The final model achieves **F1-scores ≈ 0.9999** across all evaluation settings.

---

## 🚀 Key Features  
- Integration of **PhiUSIIL dataset + 10,000 AI-generated phishing URLs**  
- Complete preprocessing and lexical feature extraction pipeline  
- **CFS-based feature selection** using the formal merit equation  
- Hybrid ML–DL architecture with:
  - Random Forest  
  - MLP (Dropout + L2 regularization)  
  - Residual + Attention Neural Network  
- Extensive evaluation:
  - Cross-validation  
  - ROC & PR curves  
  - Confusion matrices  
  - Ablation study  
- 18+ high-quality experimental graphs  
- Full IEEE research paper included  

--- 


---

## ⚙️ Technologies Used  
- **Python 3.10**  
- **Scikit-learn 1.3**  
- **TensorFlow 2.12**  
- **PyTorch 2.0**  
- NumPy, Pandas, Matplotlib, Seaborn  
- Google Colab / Jupyter Notebook  

---

## 📊 Results Summary  
| Model | Accuracy | Precision | Recall | F1-score |
|-------|----------|-----------|--------|----------|
| Random Forest | 0.99994 | 0.99990 | 1.0000 | 0.99995 |
| MLP | 0.99996 | 0.99993 | 1.0000 | 0.99997 |
| Advanced NN | 0.99992 | 0.99993 | 0.99993 | 0.99993 |

The hybrid model consistently outperforms the baselines from the base research paper.

---

## 🔍 Ablation Study  
The following components were tested individually:
- Without **Residual Connections**
- Without **Attention Layer**
- Without **CFS**
- Without **AI-Generated Data**
- Without **MLP**
- Without **Random Forest**

Full ablation results are available in the paper and figures directory.

---

## 📘 Research Paper  
The complete IEEE-formatted research paper is provided in:


It includes:
- Full methodology  
- Mathematical formulations  
- Architecture diagrams  
- Experimental graphs  
- Ablation study  
- 60+ academic references  

---

## 👨‍💻 Authors  
**Shahid Ullah (22I-2019)**  
**Muhammad Salman (22I-2027)**  
BS Data Science – FAST-NUCES Islamabad  

---

## 📄 License  
This project is released for **educational and research purposes only**.  

Unauthorized commercial use is prohibited.

---









