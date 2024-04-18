# Combined Cycle Power Plant Power Output Prediction

This project aims to predict the power output of a combined cycle power plant using machine learning algorithms. The dataset contains various operating conditions such as temperature, pressure, humidity, and vacuum, along with the corresponding power output.

## Algorithms Used
1. Gradient Boosted Regression Tree
2. Linear Regression
3. K Nearest Neighbors (KNN)

## Methodology
- The dataset was split into two parts: 90% for training and 10% for testing, and 80% for training and 20% for testing.
- We trained the model using both the split to find out the best possible split.
- Performance metrics such as mean squared error (MSE) and R-squared were calculated for each algorithm.
- After evaluation, it was found that the KNN algorithm performed the best in predicting the power output of the combined cycle power plant.

## Files
- `code.ipynb`: Jupyter Notebook containing the data preprocessing, model training, and evaluation code.
- `dataset.csv`: CSV file containing the dataset used for training and testing.
- `README.md`: This file providing an overview of the project.

## Usage
1. Clone the repository to your local machine.
2. Open `powerplant.ipynb` in Jupyter Notebook or any compatible environment.
3. Run the notebook cells sequentially to execute the code.
4. View the results and analysis in the notebook.

## Requirements
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

## Acknowledgments
Special thanks to Vipul Mishra Sir, Harshika Raj, Vishal Rai, Prashant Kumar, Ramkrishna Garai for their valuable insights and contributions to this project.

## License
This project is licensed under the MIT License - see the (LICENSE) file for details.
