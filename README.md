# Personal Wellbeing and Productivity Analyzer

### ML-Based Productivity Prediction

A Python-based mini-project that explores how digital habits, lifestyle patterns and wellbeing indicators relate to personal productivity.

The project combines data analysis, individual wellbeing reports, habit recommendations and a basic machine learning model to estimate productivity scores.

## About the Project

In our daily lives, factors such as screen time, sleep, physical activity, stress and focus can be associated with productivity.

Through this project, we analyse these factors using a dataset of 3,500 records and build a system that provides insights into digital habits and personal wellbeing.

## Key Features

* **Data Analysis:** Explore digital habits, lifestyle patterns and wellbeing indicators.
* **Data Visualisation:** Generate graphs to understand the distribution of important indicators.
* **Individual Wellbeing Report:** Generate a report for a selected individual using their dataset ID.
* **Habit Recommendations:** Provide general suggestions based on comparisons with dataset median values.
* **Productivity Prediction:** Use Linear Regression to estimate productivity scores.
* **Model Evaluation:** Evaluate predictions using MAE and R² score.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

## Dataset

We used the **Digital Lifestyle Benchmark Dataset (2025)**.

| Detail          | Information  |
| --------------- | ------------ |
| Records         | 3,500        |
| Features        | 24           |
| Format          | CSV          |
| Original Author | Tarek Masryo |
| License         | CC BY 4.0    |

**Dataset Source:** [Hugging Face – Digital Lifestyle Benchmark Dataset](https://huggingface.co/datasets/tarekmasryo/digital-lifestyle-benchmark-dataset)

The dataset is synthetic and is used for educational and analytical purposes.

## Machine Learning Results

We implemented a Linear Regression model to predict productivity scores.

| Evaluation Metric         | Result |
| ------------------------- | -----: |
| Mean Absolute Error (MAE) |   7.07 |
| R² Score                  |   0.00 |

The R² score indicates that the model explains very little of the variation in productivity scores on the test data. These results highlight the limitations of the current model and provide scope for further improvement.

## Project Structure

```text
personal-wellbeing-productivity-analyzer/
│
├── dataset/
│   └── README.md
│
├── images/
│   ├── README.md
│   └── wellbeing_distributions.png
│
├── notebooks/
│   ├── README.md
│   └── productivity_analyzer.ipynb
│
├── reports/
│   ├── README.md
│   └── Project Report PDF
│
├── requirements.txt
└── README.md
```

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/agambafna/personal-wellbeing-productivity-analyzer.git
   ```

2. Open the project folder.

3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Download the dataset from the source mentioned above.

5. Open `notebooks/productivity_analyzer.ipynb` using Jupyter Notebook or Google Colab.

6. Upload the downloaded CSV dataset to your notebook environment and update the dataset path if required.

7. Run the notebook cells in order.

## Contributors

* **Vaishnavi Suroshe** – 24
* **Agam Bafna** – 6
* **Vedant Mohod** – 26

## Limitations

* The dataset is synthetic and may not represent real-world populations.
* Correlation does not imply causation.
* Habit recommendations are general suggestions, not medical or psychological advice.
* The current Linear Regression model has limited predictive performance.

## Future Scope

* Experiment with more advanced machine learning algorithms.
* Improve feature selection and model performance.
* Add interactive dashboards for data exploration.
* Explore additional patterns in digital habits and wellbeing.

---

**Academic Mini-Project | Computer Science & Engineering**
