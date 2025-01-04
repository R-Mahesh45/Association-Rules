# Association Rule Mining Using Apriori Algorithm

This project demonstrates the application of association rule mining using the Apriori algorithm on multiple datasets. The goal is to identify frequent itemsets and generate meaningful association rules by experimenting with different support, confidence, and minimum length values. The results are visualized using various plots for better insights.

## Problem Statement

1. Generate association rules for given datasets using the Apriori algorithm.  
2. Experiment with different support and confidence values to observe changes in the number and quality of rules.  
3. Adjust the minimum length parameter to control the granularity of generated rules.  
4. Visualize the obtained rules using multiple plotting techniques to gain actionable insights.

## Features

- Explore and preprocess datasets for association rule mining.
- Experiment with parameters like support, confidence, and minimum length in the Apriori algorithm.
- Generate and analyze association rules.
- Visualize results using plots such as scatterplots, heatmaps, and bar charts.

## Project Steps

1. **Data Preprocessing**  
   - Load and preprocess datasets.
   - Encode transactions into a suitable format for the Apriori algorithm.

2. **Association Rule Mining**  
   - Apply the Apriori algorithm with varying support, confidence, and minimum length parameters.
   - Generate and evaluate association rules.

3. **Visualization**  
   - Visualize rules using:
     - Scatterplots for support vs confidence.
     - Heatmaps for lift values.
     - Bar charts for frequent itemsets.

4. **Analysis**  
   - Observe how varying parameters affect the number and quality of generated rules.

## Results

The analysis revealed that changing support and confidence values significantly impacts the number of rules generated. Lower support values capture less frequent patterns, while higher values focus on common itemsets. Adjusting the minimum length allows more granular control of the rules.

## Installation

To run the project, install the required libraries:

```bash
pip install pandas mlxtend matplotlib seaborn
```

## Usage

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Run the script to generate rules:
   ```bash
   python association_rules.py
   ```

3. Experiment with parameters like support, confidence, and minimum length in the script.

## Example Output

| **Metric**        | **Value** |
|--------------------|-----------|
| Number of Rules    | 50        |
| Frequent Itemsets  | 30        |
| Max Lift Value     | 2.5       |

## Technologies Used

- **Python**: For implementing the Apriori algorithm.
- **MLxtend**: For generating frequent itemsets and association rules.
- **Matplotlib & Seaborn**: For visualizations.

## Datasets

The project uses encoded transaction datasets such as:
- Book categories (e.g., ChildBks, YouthBks, CookBks, etc.).

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
