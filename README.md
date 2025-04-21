# High Achieving Students: EDA on Stress, Sleep, Social Life, and Physical Activity

This project is an Exploratory Data Analysis (EDA) focused on understanding how high-achieving students manage stress, maintain a social life, get enough sleep, and stay physically active. The analysis follows a structured EDA process using **Jupyter Notebook** and Python libraries.

## 📊 Objective
The goal of this project is to uncover patterns and correlations between academic success and wellness-related behaviors in students. By exploring these relationships, we can gain insights into how high-achieving students balance performance and personal well-being.

## Tools & Libraries
- **Jupyter Notebook** – for interactive coding and visualization
- **Pandas** – for data manipulation and exploration  
- **NumPy** – for numerical operations  
- **Matplotlib** – for data visualization  
- **Seaborn** – for statistical data visualization  
- **Kaggle** – for sourcing the dataset

## 📅 Dataset
The dataset used in this project is from Kaggle, provided by [Steve1215rogg](https://www.kaggle.com/steve1215rogg).

It offers a detailed view of student lifestyle patterns and their correlation with academic performance (GPA). The dataset contains 2,000 records of students' daily habits, including study, extracurriculars, sleep, socializing, and physical activities. Each student's stress level is derived from study and sleep hours, offering insights into how lifestyle factors may impact academic outcomes.

This dataset is licensed under the [Apache 2.0 License](https://opensource.org/licenses/Apache-2.0).

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

**View the full analysis here: [Exploratory Data Analysis Notebook](Student-Performance-EDA/StudentPerformanceEDA.ipynb)**

## Author
**Brandon Viaje**

