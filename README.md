# MLExam

# Adult Income Classification
**Description**

This project uses machine learning to predict whether a person earns more than 50K USD per year based on census data from the Adult Income dataset.

The project was created as part of a Machine Learning exam project.
___

# Dataset

### Dataset used:

Adult Income Dataset from UCI Machine Learning Repository

[Adult Dataset (UCI)](https://archive.ics.uci.edu/dataset/2/adult)

**The dataset contains:**
- approximately 48,000 rows
- numerical and categorical features
- binary classification target (<=50K or >50K)

### Models Used
The following model architectures were examined:
- Random Forest
- Histogram-Based Gradient Boosting

**The project includes:**
- data preprocessing
- missing value handling
- one-hot encoding
- hyperparameter tuning using GridSearchCV
- model evaluation and comparison
- Results
- Model	Accuracy
  -   Random Forest	~84.8%
  -   Tuned Random Forest	~86.0%
  -   Gradient Boosting	~86.8%

**Gradient Boosting achieved the highest overall accuracy.**
___

# Technologies
Python <br>
Pandas<br>
Scikit-learn<br>
Matplotlib<br>
Google Colab<br>

**Repository Structure**<br>
.<br>
├── AdultIncomeProject.ipynb<br>
├── README.md<br>
└── report.pdf<br>

___

## Running the Notebook

Open the notebook in:

*Google Colab* <br>
or<br>
*Jupyter Notebook*

Then run all notebook cells, **all imports are included in the project.**
