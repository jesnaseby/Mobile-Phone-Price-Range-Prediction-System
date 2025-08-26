# 📱 Mobile Price Classification

## 🎯 Problem Statement  
The goal of this project is to build a **predictive model** that classifies mobile phones into appropriate **price categories** based on their technical specifications such as RAM, battery capacity, camera quality, connectivity options, and more.

---

## 📊 Dataset Description  

The dataset contains **21 features** for each mobile phone.  

### 🔧 Technical Specifications
- **battery_power**: Battery capacity in mAh  
- **ram**: RAM in MB  
- **int_memory**: Internal memory in GB  
- **pc**: Primary camera megapixels  
- **fc**: Front camera megapixels  
- **px_height**: Pixel resolution height  
- **px_width**: Pixel resolution width  
- **clock_speed**: Processor speed in GHz  
- **n_cores**: Number of processor cores  
- **mobile_wt**: Weight in grams  
- **m_deep**: Mobile depth in cm  
- **sc_h**: Screen height in cm  
- **sc_w**: Screen width in cm  
- **talk_time**: Battery life in hours  

### ⚙️ Binary Features (0 = No, 1 = Yes)
- **blue**: Bluetooth support  
- **dual_sim**: Dual SIM support  
- **four_g**: 4G support  
- **three_g**: 3G support  
- **touch_screen**: Touch screen support  
- **wifi**: WiFi support  

### 🎯 Target Variable
- **price_range**:  
  - 0 = Low  
  - 1 = Medium  
  - 2 = High  
  - 3 = Very High  

---

## 🚀 Model Performance  

The system achieves excellent accuracy in predicting mobile phone price categories using different machine learning models:

 | Model             | Cross-Validation Accuracy | Standard Deviation |
 |---------------    |---------------------------|--------------------|
 | **XGBoost**       | 89.0%                     | ±1.3%              |
 | **SVM**           | 87.8%                     | ±1.8%              |
 | **Random Forest** | 86.6%                     | ±0.6%              |

---

## 📌 Key Highlights  
✔️ Feature-rich dataset with both numerical and categorical attributes  
✔️ Compared multiple ML models for robust evaluation  
✔️ Achieved **~89% accuracy** with XGBoost  

---


