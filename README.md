# High Achieving Students: EDA on Stress, Sleep, Social Life, and Physical Activity

This project is an Exploratory Data Analysis (EDA) focused on understanding how high-achieving students manage stress, maintain a social life, get enough sleep, and stay physically active. The analysis follows a structured EDA process using **Jupyter Notebook** and Python libraries.

## 📊 Objective

The goal of this project is to uncover patterns and correlations between academic success and wellness-related behaviors in students. By exploring these relationships, we can gain insights into how high-achieving students balance performance and personal well-being.

<p align="center">
  <a href="Student-Performance-EDA/StudentPerformanceEDA.ipynb">
    <img src="https://img.shields.io/badge/Read-More-blue?style=for-the-badge&logo=readthedocs"/>
  </a>
</p>

---

## Tools & Libraries

<table>
  <tr>
    <td><a href="https://jupyter.org/" target="_blank"><img src="https://jupyter.org/assets/homepage/main-logo.svg" width="45"/></a></td>
    <td><a href="https://pandas.pydata.org/" target="_blank"><img src="https://pandas.pydata.org/static/img/pandas_white.svg" width="45"/></a></td>
    <td><a href="https://numpy.org/" target="_blank"><img src="https://numpy.org/images/logo.svg" width="45"/></a></td>
    <td><a href="https://matplotlib.org/" target="_blank"><img src="https://matplotlib.org/_static/images/logo2.svg" width="45"/></a></td>
    <td><a href="https://seaborn.pydata.org/" target="_blank"><img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" width="80"/></a></td>
    <td><a href="https://www.kaggle.com/" target="_blank"><img src="https://www.kaggle.com/static/images/site-logo.svg" width="45"/></a></td>
  </tr>
</table>

## Dataset Overview

<details>
<summary><strong>Click to expand</strong></summary>

<br>

The dataset used in this project is from Kaggle, provided by [Steve1215rogg](https://www.kaggle.com/steve1215rogg).  

It offers a detailed view of student lifestyle patterns and their correlation with academic performance (GPA). The dataset contains 2,000 records of students' daily habits, including study, extracurriculars, sleep, socializing, and physical activities. Each student's stress level is derived from study and sleep hours, offering insights into how lifestyle factors may impact academic outcomes.

**License:** [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0)  
**Access it here:** [Student Lifestyle Dataset](https://www.kaggle.com/datasets/steve1215rogg/student-lifestyle-dataset)

</details>

## EDA Process

1. **Data Cleaning** – handling missing values and formatting  
2. **Exploratory Visualizations** – to uncover patterns and distributions  
3. **Correlation Analysis** – exploring relationships between features  
4. **Insights** – summarizing key takeaways  

---

## Key Insights

- **Extracurricular Activities:** Hours spent were consistent across stress levels — minimal impact on stress.
  
- **Daily Activities:**
  - Low-stress students: more **sleep & exercise**, less studying.
  - Moderate-stress students: more studying, less exercise.
  - High-stress students: study the most, **least** sleep/exercise.

- **Socializing:** Low and moderate-stress students socialize more than high-stress students.

- **Outliers:** Some high-stress students show extreme behaviors, suggesting coping mechanisms like overstudying or using exercise to destress.

- **Stress vs. GPA:**
  - High-stress → GPA **3.0–4.0**
  - Moderate-stress → GPA **2.5–3.5**
  - Low-stress → GPA **2.5–3.0**

- **Balance is Key:**  
  High-stress = higher academic performance but poorer wellness.  
  Moderate/low-stress = better **overall** balance.
  
<table>
  <tr>
    <td style="font-size: 20px; font-weight: bold;">Analysis By</td>
    <td style="font-size: 20px; font-weight: bold;">Published On</td>
  </tr>
  <tr>
    <td style="font-size: 18px;">Brandon Viaje</td>
    <td style="font-size: 18px;">November 24, 2024</td>
  </tr>
</table>
