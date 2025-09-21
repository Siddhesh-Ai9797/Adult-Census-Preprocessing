>> Data Preprocessing & Normalization on Adult Census Dataset
This project explores how to clean, preprocess, and normalize real-world data using Python, Pandas, and NumPy. I worked on the Adult Census dataset, which contains demographic and work-related information, to practice handling missing values, discretizing attributes, and applying different normalization techniques.

>> Project Goals
Load and explore a real dataset.
Handle missing values in both numeric and categorical attributes.
Discretize continuous attributes (e.g., Age into categories like Young, Mid-age, Old).
Apply Min-Max normalization and Z-score standardization.
Compare the effects of different normalization methods.
Visualize trends and insights using Matplotlib/Seaborn.

>> Tools & Libraries
Python 3
Pandas for data handling
NumPy for numeric operations
Matplotlib / Seaborn for visualization

>> Key Steps
1) Data Loading & Exploration
Checked shape, column types, and summary statistics.
Explored distributions of numeric and categorical attributes.
2) Handling Missing Values
Counted missing entries per column.
Replaced numeric missing values with column means.
Handled categorical missing values with most frequent values.
3) Discretization
Converted the Age attribute into categories:
Young (18–30)
Mid-age (31–50)
Old (51+)
4) Normalization
Min-Max scaling: scaled education-num into [0,1].
Z-score standardization: applied across all numeric attributes.
5) Comparison Table
Displayed original vs. normalized vs. standardized values side by side for clarity.

>> Sample Insights
Most people in the dataset work around 40 hours per week. Education level correlates strongly with income category. Normalization makes attributes comparable, which is critical for ML models.

>> Why This Project?
I built this project as part of my coursework to strengthen my data preprocessing skills. It’s not just about coding — it’s about telling the story of data: cleaning it, transforming it, and making it ready for machine learning models.
