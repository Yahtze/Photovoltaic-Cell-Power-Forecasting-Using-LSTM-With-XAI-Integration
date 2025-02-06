# Photovoltaic Cell Power Forecasting Using LSTM With XAI Integration

## 📌 Description
This repository contains the implementation of the research paper **"Photovoltaic Cell Power Forecasting Using LSTM With XAI Integration."**  
The project focuses on forecasting **Global Horizontal Irradiance (GHI)** values using an **LSTM network** for multiple forecasting windows (**15, 30, 45, and 60 minutes ahead**).  
To enhance interpretability, **Explainable AI (XAI)** techniques are applied using the **SHAP** library, generating beeswarm plots and bar charts.  

---

## ⚙️ Installation

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/Photovoltaic-LSTM-XAI.git
   cd Photovoltaic-LSTM-XAI
   ```

2. Install dependencies from `requirements.txt`:  
   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 Usage

- **Dataset:**  
  - The raw dataset is available in the `GHI_dataset/` folder.  
  - A cleaned version is also included, obtained via the **preprocessing pipeline Jupyter notebook**.  

- **Benchmark Model:**  
  - The **Persistence Model** (`Persistence_Model.py`) serves as a baseline for evaluating the performance of the LSTM model.  

- **LSTM Forecasting & XAI Analysis:**  
  - There are separate Jupyter notebooks for each forecasting window (**15, 30, 45, and 60 minutes**).  
  - Each notebook contains:  
    - LSTM model training  
    - Performance metrics  
    - SHAP-based XAI visualizations (beeswarm plots, bar charts)  

---

## 📊 Features

✅ **LSTM-based Forecasting:** Predicts GHI values for different time horizons.  
✅ **Explainable AI (XAI) with SHAP:** Provides model interpretability via feature importance visualizations.  
✅ **Persistence Model Benchmarking:** Simple yet effective baseline for performance comparison.  

---

## 🤝 Contributing
Contributions are welcome! To contribute:  
1. Fork the repository  
2. Create a new branch 
3. Commit your changes  
4. Open a Pull Request  

---

## 👤 Author
- Duvuru Yathin Reddy 
- Contact: dd2477@srmist.edu.in  
- GitHub: (https://github.com/Yahtze)
