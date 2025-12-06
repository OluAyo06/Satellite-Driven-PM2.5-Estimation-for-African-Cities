---

# **Air Quality Prediction Using Satellite AOD and Machine Learning**

This project aims to estimate **PM2.5 concentrations** across major African cities using **satellite-derived Aerosol Optical Depth (AOD)** and machine learning techniques. It supports ongoing efforts by **AirQo** and **Mozilla Foundation** to bridge air-quality data gaps in sub-Saharan Africa and empower communities with accurate environmental information.

---

## **Project Summary**

Air pollution remains one of the world’s most serious environmental health risks, responsible for roughly **seven million premature deaths annually**. Sub-Saharan Africa is severely affected due to limited monitoring infrastructure and rising urban exposure.

This project leverages:

* **Satellite AOD measurements**
* **Ground-based PM2.5 observations**
* **Machine learning models**

to estimate pollution levels in eight African cities:

* **Lagos**
* **Accra**
* **Nairobi**
* **Yaoundé**
* **Bujumbura**
* **Kisumu**
* **Kampala**
* **Gulu**

The models developed here are intended to support deployment on the **AirQo digital platform**, enabling users to access real-time, hyperlocal air-quality information.

---

## **Project Structure**

```
📂 Air-Quality-Prediction
│
├── 📓 Air Quality Prediction.ipynb
├── 📁 data/
│     ├── train.csv
│     ├── test.csv
│     └── additional datasets…
│
├── 📁 scripts/
│     └── preprocessing.py
│
├── README.md
└── requirements.txt
```

---

## **Notebook Workflow**

### **1. Cleaning of Dataset**

* Handling missing values
* Removing duplicates
* Column formatting
* Data validation

### **2. Exploration of Data**

* Summary statistics
* Variable distributions
* Outlier detection
* Time-series trends

### **3. Exploration of Test Dataset**

* Checking structure and consistency
* Matching columns with training dataset
* Identifying missing or mismatched features

### **4. Encoding**

* Converting categorical variables
* Label and one-hot encoding
* Preparing data for modeling

### **5. Heat Map**

* Correlation analysis
* Identifying strong predictors
* Guiding feature selection

---

## **Installation**

To set up the environment:

```bash
git clone https://github.com/yourusername/Air-Quality-Prediction.git
cd Air-Quality-Prediction

pip install -r requirements.txt
```

---

## **How to Run the Project**

### **Option 1: Run the Notebook**

Open Jupyter Notebook or VS Code:

```bash
jupyter notebook
```

Then open:
**Air Quality Prediction.ipynb**

### **Option 2: Run Script (Optional)**

If scripts are provided:

```bash
python scripts/preprocessing.py
```

---

## **Technologies & Libraries Used**

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* XGBoost / LightGBM
* Geospatial data tools (AOD, satellite features)

---

## **License**

This project is open-source and available under the **MIT License**.

---


