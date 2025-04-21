# High Achieving Students: EDA on Stress, Sleep, Social Life, and Physical Activity

This project is an Exploratory Data Analysis (EDA) focused on understanding how high-achieving students manage stress, maintain a social life, get enough sleep, and stay physically active. The analysis follows a structured EDA process using **Jupyter Notebook** and Python libraries.

## 📊 Objective
The goal of this project is to uncover patterns and correlations between academic success and wellness-related behaviors in students. By exploring these relationships, we can gain insights into how high-achieving students balance performance and personal well-being.
    
# [![Read More](https://img.shields.io/badge/Read-More-blue?style=for-the-badge&logo=readthedocs)](Student-Performance-EDA/StudentPerformanceEDA.ipynb)

## Tools & Libraries
- **Jupyter Notebook** – for interactive coding and visualization
- **Pandas** – for data manipulation and exploration  
- **NumPy** – for numerical operations  
- **Matplotlib** – for data visualization  
- **Seaborn** – for statistical data visualization  
- **Kaggle** – for sourcing the dataset

<table>
  <tr>
    <td><a href="https://jupyter.org/" target="_blank"><img src="https://jupyter.org/assets/homepage/main-logo.svg" width="50"/></a></td>
    <td><a href="https://pandas.pydata.org/" target="_blank"><img src="https://pandas.pydata.org/static/img/pandas_white.svg" width="50"/></a></td>
    <td><a href="https://numpy.org/" target="_blank"><img src="https://numpy.org/images/logo.svg" width="50"/></a></td>
    <td><a href="https://matplotlib.org/" target="_blank"><img src="https://matplotlib.org/_static/images/logo2.svg" width="50"/></a></td>
    <td><a href="https://seaborn.pydata.org/" target="_blank"><img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" width="80"/></a></td>
    <td><a href="https://www.kaggle.com/" target="_blank"><img src="https://www.kaggle.com/static/images/site-logo.svg" width="50"/></a></td>
  </tr>
</table>


## 📅 Dataset
The dataset used in this project is from Kaggle, provided by [Steve1215rogg](https://www.kaggle.com/steve1215rogg).

It offers a detailed view of student lifestyle patterns and their correlation with academic performance (GPA). The dataset contains 2,000 records of students' daily habits, including study, extracurriculars, sleep, socializing, and physical activities. Each student's stress level is derived from study and sleep hours, offering insights into how lifestyle factors may impact academic outcomes.

This dataset is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

You can access the dataset [here](https://www.kaggle.com/datasets/steve1215rogg/student-lifestyle-dataset).

## EDA Process
The analysis follows these main steps:
1. **Data Cleaning** – handling missing values and formatting
2. **Exploratory Visualizations** – to uncover patterns and distributions
3. **Correlation Analysis** – exploring relationships between features
4. **Insights** – summarizing key takeaways

## Key Insights

- **Extracurricular Activities**: Hours spent on extracurriculars were consistent across all stress levels, showing no significant impact on student stress.
  
- **Daily Activities**:
  - Low-stress students spend more time sleeping and exercising compared to studying.
  - Moderate-stress students study more and exercise less than low-stress students.
  - High-stress students study the most, but spend less time sleeping and exercising.
  
- **Socializing**: Low and moderate-stress students spend more time socializing than high-stress students.

- **Outliers**: Certain high-stress students exhibit outlier behavior in study hours and physical activity, possibly indicating coping mechanisms like avoiding homework or using exercise to manage stress.

- **Stress and GPA**: 
  - High-stress students generally perform well academically, with GPAs ranging from 3.0 to 4.0.
  - Moderate-stress students tend to have GPAs between 2.5 and 3.5, while low-stress students’ GPAs range from 2.5 to 3.0.

- **Health vs. Academic Performance**: 
  - High-stress students often neglect self-care (sleep, exercise, socializing), despite performing well academically.
  - Moderate and low-stress students manage to balance their academics with self-care, which results in more well-rounded success.

---

**✍️ Analysis by:** Brandon Viaje

**🗓️ Published on:**  *November 24, 2024*  

---
