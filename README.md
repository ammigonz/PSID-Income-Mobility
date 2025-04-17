# 📈 PSID-Income-Mobility  
### Predictive Modeling of Intergenerational Income

## 🧠 Project Overview

This project was completed during my final year as an undergraduate at UC Santa Cruz for a course titled *Machine Learning for Economists*. At the time, I had a strong interest in data science, but my background was primarily in econometrics through my Economics major. This project was pivotal—it marked the beginning of my journey into the world of data and econometric modeling.

The core question I explored: **Is the income of a third-generation American predictable based on personal and familial demographics?** Inspired by the concept of the *American Dream*, I set out to investigate income mobility across generations using real-world economic data.

## 📊 Data & Methodology

The analysis is based on the **Panel Study of Income Dynamics (PSID)** dataset. I examined whether upward economic mobility could be predicted using features such as:

- Family income history
- Educational attainment
- Demographic and household variables

### Modeling Approach

Using R, I built and compared multiple regression models:

- **Ordinary Least Squares (OLS)**
- **Lasso Regression**
- **Ridge Regression**

I incorporated interaction terms and used cross-validation to improve out-of-sample performance, specifically optimizing for **R²**. The final visualizations in the research paper highlight the strong predictive effects of education and family background on future income, shedding light on intergenerational wealth and mobility.

## 📁 Installation & Setup

This project is lightweight and easy to run. It includes just one `.R` script and one `.csv` file.

### Data Download:
Download the dataset directly from [OpenICPSR](https://www.openicpsr.org/openicpsr/project/185941/version/V2/view?path=/openicpsr/185941/fcr:versions/V2/for_students.zip&type=file)

1. Extract the `.csv` file from the ZIP.
2. Replace the file path in the `.R` script with your local directory.
3. Run the script in R or RStudio.

## ▶️ Usage

Once you've downloaded the dataset and updated the path in the script, simply run the `.R` file to reproduce the analysis, model selection process, and visualizations.

## 📄 Final Research Paper

You can read the full analysis and conclusions in my final paper:

📂 `/docs/Grover_Gonzalez Final Paper.pdf`

## 🙋‍♀️ Author

Amber Gonzalez-Pacheco  
Data science enthusiast with a passion for econometrics, income equity, and social mobility research.
