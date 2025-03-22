
# Weather Classification Dataset (3-Class)

This dataset contains synthetic weather data structured for multiclass classification tasks.

---

## 📁 File: `weather_classification_3class.csv`

### 🔹 Description:
A dataset with three weather classes:

| Class | Meaning       |
|-------|---------------|
| 0     | Normal Weather |
| 1     | Rain (high humidity, low visibility, moderate temperature) |
| 2     | Storm (very low visibility and high wind) |

### 🔸 Features:
- `Temp`: Temperature in Celsius
- `Humidity`: Relative humidity (%)
- `Pressure`: Atmospheric pressure (hPa)
- `Wind`: Wind speed (km/h)
- `Visibility`: Visibility range in km
- `class`: Weather category (0 = Normal, 1 = Rain, 2 = Storm)

---

## ✅ Use Cases
- Multiclass classification
- PCA and SHAP analysis
- Model training and comparison (e.g., LR, KNN, QDA)

---

## 👤 Author
Created by [Your Name] to explore interpretable classification models in weather forecasting.
