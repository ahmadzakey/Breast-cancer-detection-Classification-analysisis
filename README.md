# Breast Cancer Classification Project

This project involves the classification of breast cancer cases into **malignant** (cancerous) or **benign** (non-cancerous) using various supervised learning algorithms. The dataset used is the **Breast Cancer Dataset**, and the models implemented include:

- Logistic Regression
- k-Nearest Neighbors (k-NN)
- Decision Tree
- Random Forest

## 📁 Dataset Overview
The dataset contains measurements of tumor characteristics, divided into **feature columns** and a **target column**:

### **Feature Columns and Descriptions**
| **Feature**               | **Description**                                                                 |
|----------------------------|---------------------------------------------------------------------------------|
| `mean radius`             | Mean of distances from the center to points on the perimeter.                   |
| `mean texture`            | Standard deviation of gray-scale values.                                        |
| `mean perimeter`          | Mean size of the tumor perimeter.                                               |
| `mean area`               | Mean size of the tumor area.                                                    |
| `mean smoothness`         | Mean of local variation in radius lengths.                                      |
| `mean compactness`        | Mean of ( (perimeter² / area) - 1.0 ).                                          |
| `mean concavity`          | Mean of the severity of concave portions of the tumor contour.                  |
| `mean concave points`     | Mean of the number of concave portions of the tumor contour.                    |
| `mean symmetry`           | Mean of symmetry in the tumor shape.                                            |
| `mean fractal dimension`  | Mean of (“coastline approximation” - 1.0).                                      |
| `radius error`            | Standard deviation of radius lengths.                                           |
| ...                       | (More features such as texture error, area error, etc.)                        |
| `worst fractal dimension` | Largest mean fractal dimension observed.                                        |

### **Target Column**
| **Target** | **Description**      |
|------------|----------------------|
| 0          | Malignant (cancerous) |
| 1          | Benign (non-cancerous) |

---

## 🎯 Project Objective
To build and evaluate machine learning models to classify breast cancer cases as malignant or benign.

---

## 🛠️ Models Implemented
### Logistic Regression
- Achieved **99.29% Test Accuracy**.
- Near-perfect precision, recall, and F1-scores.

### k-Nearest Neighbors (k-NN)
- Achieved **99.29% Test Accuracy**, comparable to Logistic Regression.
- High precision and recall for both classes.

### Decision Tree
- Achieved **97.86% Test Accuracy**.
- Slightly lower performance compared to other models but still robust.

### Random Forest
- Achieved **100% Training Accuracy** and **99.29% Test Accuracy**.
- Demonstrated exceptional precision, recall, and F1-scores.
- The best-performing model in the study.

---

## 📊 Key Results
| **Model**          | **Training Accuracy** | **Test Accuracy** | **Notes**                                |
|---------------------|-----------------------|-------------------|------------------------------------------|
| Logistic Regression | 100%                 | 99.29%            | Excellent generalization.                |
| k-NN                | 100%                 | 99.29%            | Robust with a balanced performance.      |
| Decision Tree       | 100%                 | 97.86%            | Slightly lower performance than others.  |
| Random Forest       | 100%                 | 99.29%            | Best model due to its overall metrics.   |

---

## 🏆 Recommended Model: **Random Forest**
The Random Forest model is recommended because:
1. **Highest Test Accuracy**: 99.29%, matching Logistic Regression and k-NN.
2. **Perfect Training Accuracy**: Captures all patterns in the training data.
3. **Excellent Classification Report**: Precision, recall, and F1-scores are near-perfect for both classes.

---

