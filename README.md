## 📁 Project Structure
early-detection-alzheimers/
│
├── AD_prediction_model.ipynb # Jupyter notebook with full ML pipeline
├── AD_clinical_dataset/ # Clinical dataset containing metadata
├── MRI_Images/
│ ├── SUBJ_111/ # Processed brain MRI images - subject aligned
│ └── T88_111/ # Processed brain MRI images - T88 template
│
├── Paper/
│ ├── research_paper.pdf # Final research paper
│ └── presentation.pptx # Conference/academic presentation slides


## 🧬 Dataset

- **Source:** [OASIS-1 Dataset](https://www.oasis-brains.org/)
- Includes 390 T1-weighted MRI images
- Associated clinical features: Age, Gender, MMSE, SES, CDR, eTIV, nWBV, and more

## 🧠 Methods & Models

- **Data Preprocessing:** Image renaming, clinical data cleaning, feature merging
- **ML Models:** SVM, XGBoost
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score
- **Outcome:** XGBoost model achieved the best performance

## 📝 How to Use

1. Clone this repository:
    ```bash
    git clone https://github.com/lakshmi1202/early-detection-alzheimers.git
    cd early-detection-alzheimers
    ```

2. Launch the notebook:
    ```bash
    jupyter notebook AD_prediction_model.ipynb
    ```

3. Install dependencies (optional):
    ```bash
    pip install -r requirements.txt
    ```

## 📚 Citation

If this research helps you, please cite:


## 🛡️ License

This project is intended for educational and research purposes only. Contact the author for other use cases.


