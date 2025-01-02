# Insurance Premium Prediction

This project focuses on analyzing and predicting medical insurance premium prices based on various customer attributes. It utilizes Python for data analysis and visualization.

## Dataset
The dataset, `Medicalpremium.csv`, contains information on the following attributes:
- **Age**: Age of the individual
- **Diabetes**: Presence of diabetes (1 for Yes, 0 for No)
- **BloodPressureProblems**: Presence of blood pressure problems (1 for Yes, 0 for No)
- **AnyTransplants**: History of transplants (1 for Yes, 0 for No)
- **AnyChronicDiseases**: Presence of chronic diseases (1 for Yes, 0 for No)
- **Height**: Height of the individual (cm)
- **Weight**: Weight of the individual (kg)
- **KnownAllergies**: Presence of known allergies (1 for Yes, 0 for No)
- **HistoryOfCancerInFamily**: Family history of cancer (1 for Yes, 0 for No)
- **NumberOfMajorSurgeries**: Number of major surgeries undergone
- **PremiumPrice**: Insurance premium price (target variable)

## Requirements
Ensure the following libraries are installed:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

You can install these using:
```bash
pip install numpy pandas matplotlib seaborn
```

## Usage
1. Clone this repository or download the notebook file.
2. Place the dataset (`Medicalpremium.csv`) in the same directory as the notebook.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Run the cells sequentially to:
   - Load and explore the dataset.
   - Check for missing values and data distribution.
   - Visualize relationships between features and the target variable.
   - Build and evaluate predictive models (if included).

## Key Steps
1. **Data Exploration**:
   - Inspect the structure and summary of the dataset.
   - Identify missing values and clean data.

2. **Visualization**:
   - Use `matplotlib` and `seaborn` for data visualization.
   - Explore feature correlations and distribution.
   - Example:
     - A correlation heatmap highlights relationships between variables (e.g., `PremiumPrice` is strongly correlated with `Age` and `NumberOfMajorSurgeries`).

3. **Modeling**:
   - Various regression models were evaluated, including Linear Regression, Lasso, XGBoost Regressor, and Random Forest.

4. **Label Encoding**:
   - A new label `PremiumLabel` was created to categorize premium levels.

## License
This project is open-source and available for use under the MIT License.

