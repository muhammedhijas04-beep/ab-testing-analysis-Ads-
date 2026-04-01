# 📊 A/B Testing Analysis for Ad Campaign Optimization

---

## 🎯 Problem Statement

Do advertisements significantly improve user conversion rates compared to a control group with no ads?



## 📦 Dataset Overview

* **Total Users:** 588,101
* **Groups:**

  * `ad` (treatment)
  * `psa` (control)
* **Target Metric:** Conversion (True/False)



## ⚙️ Approach

### 1. Data Validation

* Checked for duplicate users
* Ensured each user belongs to only one group
* Verified dataset integrity



### 2. Exploratory Analysis

* Compared conversion rates across groups
* Identified baseline performance



### 3. Hypothesis Testing

* Performed **Z-test for proportions**
* Determined statistical significance of results



### 4. Confidence Interval

* Estimated range of true conversion uplift
* Validated reliability of observed difference



### 5. Segmentation Analysis

* Analyzed performance by:

  * Day of week
  * Hour of day



## 📊 Key Results

* **Ad Conversion Rate:** ~3%
* **Control Conversion Rate:** ~2%
* **Relative Uplift:** ~43%
* **Absolute Increase:** ~0.77%
* **Statistical Significance:** p-value < 0.05



## 💡 Key Insights

* Ads significantly improve conversion rates
* Highest impact observed on:

  * **Tuesday & Wednesday**
* Peak performance during:

  * **Morning (7–10 AM)**
  * **Evening (8–11 PM)**
* Minimal impact observed on:

  * **Thursday**
  * Early morning hours



## 📈 Visualization

### Conversion Comparison

![Conversion rate comparison between ad group at approximately 3% and control group at approximately 2%, demonstrating a 43% relative uplift and 0.77% absolute increase in conversion rates]

<img width="584" height="455" alt="conversion_rate" src="https://github.com/user-attachments/assets/00038f4f-afa4-43ed-b50e-3a5617c92414" />


### Day-wise Performance

![Day-wise conversion performance comparing ad and control groups across all weekdays, with Tuesday and Wednesday showing the highest conversion rates]

<img width="611" height="455" alt="daywise" src="https://github.com/user-attachments/assets/f89c6a15-be73-4dca-9b0c-3cae3f7b561c" />


### Hour-wise Performance

![Hourly conversion performance comparing ad and control groups across 24 hours, showing peak conversion rates during morning (7–10 AM) and evening (8–11 PM) periods]

<img width="1265" height="725" alt="hourwise" src="https://github.com/user-attachments/assets/68e5dd1c-eb13-4b28-9fbe-e4c7c54290c4" />


### Uplift Analysis

![Uplift analysis comparing relative and absolute conversion improvements between ad and control groups, visualizing the 43% relative uplift and 0.77% absolute increase in conversion rates]

<img width="571" height="521" alt="uplift" src="https://github.com/user-attachments/assets/d6b74483-aa81-4cae-bb26-f41373f648c3" />



## 🧠 Business Recommendations

* Focus ad campaigns on high-performing days (Tue–Wed)
* Optimize ad delivery during peak hours
* Evaluate ROI due to relatively small absolute uplift



## ⚠️ Limitations

* Imbalanced group distribution (96% vs 4%)
* Further controlled experiments recommended



## 🚀 Tools & Technologies

* Python (Pandas, NumPy, Matplotlib)
* Statistical Testing (Z-test)
* Power BI (Dashboard)


## 🏁 Conclusion

The analysis demonstrates that while ads significantly increase conversion rates, the absolute improvement is modest. Strategic targeting based on time segmentation can enhance campaign effectiveness.


