# Consumer Complaint Classification Project

This project analyzes and classifies consumer complaints. The workflow includes data preprocessing, exploratory data analysis (EDA), text translation, and training a machine learning model for classification.

---

## 💾 Dataset

**The data files are not included in this repository due to their large size.**

To run this project, you must download the necessary files and place them in the `/data/` folder. The `src/config.py` file is already set up to find them there.

### 1. Raw Data

This is the original, unprocessed dataset.

* **File:** `consumercomplaints.xlsx`
* **Download:** https://www.kaggle.com/datasets/selener/consumer-complaint-database

### 2. Cleaned Data

This dataset has been preprocessed and cleaned by the `01-data-cleaning.ipynb` notebook. If you don't want to run the cleaning notebook yourself, you can download the final file here.

* **File:** `cleaned_complaints.xlsx`
* **Download:** https://kaggle.com/datasets/6f0867ba82eaed80e6b28448385a4b7723b7d0c8abb0b8caeff64ceaa1e20563

### 3. Translated Data

This dataset contains a sample of complaints translated into multiple languages for bilingual modeling.

* **File:** `sample_top5_translated.csv`
* **Download:** https://kaggle.com/datasets/3b4026e9db93a6c34084f7348372806e64d1fd26b3bffe14a72cad8e78f7ae62

---

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Parnika798/FinancialComplaintClassification.git](https://github.com/Parnika798/FinancialComplaintClassification.git)
    cd FinancialComplaintClassification
    ```

2.  **Create a virtual environment (Recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use: venv\Scripts\activate
    ```

3.  **Install requirements:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Get the data:**
    Download the required data files from the links in the "Dataset" section above and place them in the `/data/` folder.

5.  **Run the notebooks:**
    Open the `notebooks/` folder and run the notebooks in order.

---


```
