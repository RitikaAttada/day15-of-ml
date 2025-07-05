# 🧠 Day 15: Mastering **Multivariate Linear Regression (Multiple Outputs)**

Today, I worked on five **structured regression problems** where each scenario involved **multiple input features** influencing **two target values**. This is an extension of multivariate regression, now predicting **multiple outputs simultaneously**.

---

## 📊 Real-World Datasets I Explored

Each dataset was unique and represented a realistic use case involving **multi-output regression**:

1. **Student Wellness**

   * Inputs: `study_hours`, `sleep_hours`, `attendance_percent`
   * ➡️ Targets: `exam_score`, `stress_level`

2. **House Utility Bills**

   * Inputs: `num_people`, `house_size_m2`, `ac_usage_hours`
   * ➡️ Targets: `electricity_bill`, `water_bill`

3. **Vehicle Efficiency**

   * Inputs: `engine_size_L`, `vehicle_weight_kg`, `fuel_type_encoded`
   * ➡️ Targets: `fuel_mileage_kmpl`, `co2_emission_gkm`

4. **Employee Stats**

   * Inputs: `hours_worked`, `meetings_attended`, `experience_years`
   * ➡️ Targets: `task_completion_score`, `satisfaction_score`

---

## 🧠 What I Did

✅ Created 5 multivariate regression datasets with **multiple inputs and two outputs**
✅ Scaled input and output features using `MinMaxScaler`
✅ Trained a Neural Network with 2 output neurons (one per target)
✅ Used `joblib` to persist scalers and built a function for each use case
✅ Visualized actual vs predicted results with proper `y = x` reference lines

---

## 🧩 What I Learned

* Multivariate regression models can handle **real-world complexity** when trained properly.
* Predicting **multiple targets together** can improve performance when outputs are related.
* Always use **separate scalers for X and Y**, and inverse-transform Y before reporting results.
* The diagonal `y = x` line on scatter plots is a powerful visual cue for model accuracy.

---


> 🛠 Technologies Used:
> Python, NumPy, Pandas, TensorFlow, scikit-learn, Matplotlib, Joblib
