# Customer Segmentation Analysis

## Project Overview

Customer behavior analysis is essential for businesses that want to improve marketing strategies and customer engagement.

This project performs **Exploratory Data Analysis (EDA)** on a mall customer dataset to identify patterns and factors that influence a customer's **spending score**.

Through visualization and statistical exploration, the analysis highlights relationships between **customer age, annual income, and spending score**, revealing which variables most strongly influence purchasing behavior.

The final insight from the analysis shows that **annual income has the strongest influence on customer spending score**.

---

# Project Objective

The objective of this project is to:

* Explore mall customer data using **Exploratory Data Analysis (EDA)**
* Identify patterns between customer demographics and spending behavior
* Visualize relationships between features using **Seaborn** and **Matplotlib**
* Determine which factors influence the **Spending Score**

---

# Technologies Used

| Technology       | Purpose                                    |
| ---------------- | ------------------------------------------ |
| Python           | Programming language used for the analysis |
| Pandas           | Data loading and manipulation              |
| NumPy            | Numerical operations                       |
| Matplotlib       | Data visualization                         |
| Seaborn          | Statistical data visualization             |
| Jupyter Notebook | Interactive development environment        |

---

# System Requirements

Before running this project, ensure you have the following installed:

* **Python 3.12**
* **Jupyter Notebook**
* Python libraries:

  * pandas
  * numpy
  * matplotlib
  * seaborn

---

# Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Rosemary-Njoroge/AI-Capstone-Project.git

```

### 2. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate it:

Windows

```bash
venv\Scripts\activate
```

Mac/Linux

```bash
source venv/bin/activate
```

### 3. Install Required Packages

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook file containing the analysis.

---

# Dataset

The dataset used in this project is **Mall Customers Data**, which contains demographic and spending information about mall customers.

Typical features include:

* Customer ID
* Gender
* Age
* Annual Income
* Spending Score

---

# Example Usage

Example visualization from the project:

```python
sns.scatterplot(data=data, x="Annual Income (k$)", y="Spending Score (1-100)")
plt.title("Income vs Spending Score")
plt.show()
```

This plot helps reveal how customer income relates to their spending behavior.

---

# AI Prompt Journal

Prompt used: 
**Module:** Learning a new programming language with AI
            Advanced prompting techniques for language learning
**Prompt:** 2.4 Using a tutor, Example 1
**link** https://training.moringaschool.com/courses/9/pages/learning-a-new-programming-language-with-ai?module_item_id=372

The AI gave me a step-by-step guide on how to understand the data, think like a business analyst and connect to visualization. It also asked me questions that helped me be able to use matplotlib and seaborn to create charts that can be used to answer business questions


Prompt used:
**Module:** Generating and improving documentation with AI. 
            3. User guides and Readme files. 
**Prompt:** Prompt template: project readme genetation
**Link** https://training.moringaschool.com/courses/9/pages/generating-and-improving-documentation-with-ai?module_item_id=351

The AI created this readme using the sections I specified on the prompt. This made my work easier and fast

---

# Common Issues and Fixes

### Issue: ModuleNotFoundError

If you see errors like:

```
ModuleNotFoundError: No module named 'pandas'
```

Install the missing library:

```bash
pip install pandas
```

---

### Issue: Dataset Not Found

If the notebook cannot locate the dataset:

```
FileNotFoundError: Mall_Customers.csv
```

Ensure the dataset file is placed in the **same folder as the notebook** or update the file path:

```python
pd.read_csv("data/Mall_Customers.csv")
```

---

### Issue: Plots Not Displaying

Ensure the following line is included in your Jupyter Notebook:

```python
%matplotlib inline
```

---

# Future Improvements

Possible extensions to this project include:

* Applying **K-Means clustering** to identify customer segments
* Creating **cluster profiles for marketing strategies**
* Building **interactive visualizations**
* Developing a **customer segmentation dashboard**

---

# Author

**Rosemary Njoroge**

Aspiring Data Scientist with a focus on **data analysis, visualization, and machine learning**.

---

# License

This project is open-source and available for educational and portfolio use.
