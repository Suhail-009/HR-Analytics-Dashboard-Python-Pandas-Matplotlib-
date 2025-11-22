# HR-Analytics-Dashboard-Python-Pandas-Matplotlib-
This project performs medium-complex HR analytics using a 500-row synthetic HR dataset. It includes KPI calculation, attrition analysis, tenure segmentation, salary comparison, and visual insights using Matplotlib.

**📌 Project Overview**

This HR Analytics Dashboard helps analyze workforce structure, attrition patterns, salary trends, and tenure behavior inside an organization. It is suitable for beginners to intermediate data analysts and is an excellent addition to your portfolio or GitHub.


**📂 Dataset**

The project uses a dataset containing 500 employee records with the following columns:
* EmployeeID
* Age
* Gender
* Department
* JobRole
* Salary
* Tenure
* Attrition

You can modify, expand, or replace the dataset as needed.


**🛠️ Technologies Used**
* Python 3
* Pandas – Data loading, cleaning, and analysis
* Matplotlib – Visualizations
* Jupyter Notebook / VS Code (recommended)


**📥 Installation & Setup**
1. Clone or download this repository.
2. Install required libraries:

    __pip install pandas matplotlib__

4. Place the dataset file (hr_data_500.csv) in the project folder.
5. Run the Jupyter Notebook or Python script.


**📊 Features & Analysis Steps**
This project includes the following analyses and charts:

✔ 1. Key HR Metrics (KPIs)
* Total Employees
* Attrition Rate
* Average Salary
* Average Tenure
  
✔ 2. Gender DistributionPie chart showing male vs female workforce ratio.

✔ 3. Attrition by DepartmentBar chart showing departments with highest attrition.

✔ 4. Average Salary by DepartmentUnderstand salary differences across departments.

✔ 5. Tenure Group CreationEmployees grouped into:
* 0–2 years
* 2–5 years
* 5–10 years
* 10+ years
  
✔ 6. Attrition by Tenure GroupShows which group leaves the organization most.


**📈 Visualizations**

The project generates clear visualizations using Matplotlib:

* Pie Charts
* Bar Charts
* Count distributions
  
These charts help HR teams understand attrition trends and workforce structure.


**📁 File Structure**

HR-Analytics-Dashboard/
│
├── hr_data_500.csv
├── hr_analytics.ipynb  # (Analysis Notebook)
├── README.md
└── charts/              # (Optional: exported images)


**🧠 Insights from the Dashboard**

* Identify departments with high attrition.
* Understand which tenure range has the highest turnover.
* Compare average salaries across teams.
* Examine gender distribution.
  
These insights can help HR teams create better retention strategies.


**🚀 Future Improvements**

You can extend the project with:

* Machine Learning model to predict employee attrition
* Correlation heatmaps
* Salary distribution histogram
* Adding overtime, performance rating, education data
* Streamlit interactive dashboard
  
