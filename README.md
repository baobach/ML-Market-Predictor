# ML-Market-Predictor

This repository contains the necessary resources and files to predict market movements using machine learning techniques.

## Repository Structure

- `environment.yml`: Configuration file specifying the required environment and dependencies.
- `final_model.joblib`: Serialized file of the final machine learning model.
- `SPY1D.csv`: Dataset containing SPY 1D market data from 2008 to 2023.
- `report.ipynb`: Research report detailing the methodology, analysis, and findings.

## Usage Instructions

### Setting Up the Environment

- Use the provided `environment.yml` file to set up the required environment using Anaconda or Miniconda:

```bash
conda env create -f environment.yml
conda activate <environment_name>
```

### Model Implementation

- Load the `final_model.joblib` file into your Python environment using libraries like `joblib`.
- Utilize the model for market movement predictions or further analysis.

### Exploring the Research Report

- Open and explore the `report.ipynb` Jupyter Notebook for detailed insights into the research methodology, analysis, and conclusions drawn.

## Important Notes

- Ensure the necessary dependencies from `environment.yml` are installed before using the model.
- The `SPY1D.csv` dataset is crucial for training and testing the model.

## License

This project is licensed under the [Apache License 2.0](LICENSE).

## Acknowledgments

- [CQF Institution](https://www.cqf.com/): Acknowledgment for their support and resources.
- Prof. Yves Hilpisch: Acknowledgment for guidance and assistance.
- Dr. Paul Wilmott: Acknowledgment for expertise and mentorship.

## Contributions

As the sole contributor, contributions are not currently accepted. However, feedback and suggestions are welcome.

Thank you for your interest in ML-Market-Predictor!
