

# Enhancing Portfolio Optimization with Data Fusion and Machine Learning

## Introduction

This project aims to revolutionize portfolio optimization in quantitative finance by integrating advanced machine learning techniques and data fusion methodologies. Traditional methods often face limitations in handling market complexities and effectively integrating diverse data sources. Our approach seeks to overcome these challenges by leveraging the power of machine learning and data fusion, allowing for more accurate and robust portfolio optimization strategies.

## Data Collection

We collect our data from the CSMAR (China Stock Market & Accounting Research) database, a comprehensive platform jointly established by Chinese regulatory authorities and the Shanghai Stock Exchange. This database provides valuable information on Chinese A-share market companies, including financial statements, investor sentiment indices, and sentiment consistency data.

The data is downloaded as CSV files from the CSMAR platform, allowing us to access historical financial asset data and market sentiment data necessary for our analysis.

## Methodology

Our project follows a structured methodology to achieve its goals:

1. **Data Preprocessing**: The downloaded CSV files are cleaned and preprocessed to ensure data quality and consistency. This includes handling missing values, removing outliers, and formatting the data for further analysis.

2. **Feature Engineering**: Relevant features are extracted from the preprocessed data, incorporating both traditional financial indicators and sentiment-based metrics.

3. **Model Selection**: Using the "Qlib" library, we evaluate and select high-quality machine learning models suitable for our dataset, such as Long Short-Term Memory (LSTM) networks, Random Forests, and Gradient Boosting Machines.

4. **Model Reproduction**: We utilize remote development tools like MobaXterm and PyCharm to reproduce and improve the selected machine learning models.

5. **Model Training and Evaluation**: The selected models are trained on the preprocessed data, and their performance is thoroughly evaluated using appropriate metrics, such as mean squared error, Sharpe ratio, and cumulative returns.

6. **Portfolio Optimization**: The trained models are integrated into a portfolio optimization framework, leveraging their predictive capabilities to make informed investment decisions. Techniques like mean-variance optimization and risk parity are employed to construct well-diversified portfolios.

7. **Backtesting and Validation**: The optimized portfolio strategies are backtested on historical data to assess their performance and validate the effectiveness of our approach. Out-of-sample testing is conducted to ensure the robustness and generalization of the models.

## Results

Our team has successfully reproduced three machine learning models, and each model has been run 50 times, demonstrating the feasibility and robustness of our approach. These promising results pave the way for further advancements in the field of portfolio optimization using machine learning and data fusion techniques.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository: `git clone https://github.com/EthanYixuanMi/Machine-Learning-in-Quantitative-Finance.git`
2. Install the required dependencies (e.g., Python, Qlib, Pandas, NumPy, Scikit-learn, etc.).
3. Explore the codebase and understand the data preprocessing, feature engineering, model selection, and portfolio optimization processes.
4. Run the provided Jupyter Notebooks or Python scripts to reproduce the experiments and results.

## References

1. Song, C. (2023). Portfolio Optimization Based on Machine Learning. Advances in Economics, Management and Political Sciences. https://doi.org/10.54254/2754-1169/25/20230500
2. Wang, Y. (2023). Review: Application of Machine Learning to Investment Portfolios. BCP Business & Management. https://doi.org/10.54691/bcpbm.v38i.4351

## Contributing

We welcome contributions from the community! If you have any ideas, suggestions, or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any questions or inquiries, please contact the project maintainer:

- Yixuan Mi: [yixuanmi25@gmail.com]
