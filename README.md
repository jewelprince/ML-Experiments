# ML-Experiments
# Demand Forecasting with Feature Enrichment (Upgini)

This project explores demand forecasting using machine learning, with an emphasis on **feature enrichment** powered by [Upgini](https://github.com/upgini/upgini). The goal is to demonstrate how adding external features can improve the accuracy of a basic demand forecast model.

## Project Overview
- Built in **Google Colab** with Python.  
- Uses **Upgini** to enrich datasets with additional relevant features.  
- Trains a simple forecasting model to predict demand over time.  
- Compares baseline results vs. results after feature enrichment.

## Tools & Libraries
- Python 3.x  
- Pandas & NumPy  
- Scikit-learn  
- Upgini (for feature enrichment)  
- Matplotlib/Seaborn (for visualization)

## Workflow
1. **Load baseline dataset** for demand forecasting.  
2. **Apply Upgini** to search for and add external features.  
3. Train a **machine learning model** (e.g., linear regression, random forest).  
4. Evaluate model performance before and after enrichment.  
5. Visualize and compare results.  

## Results
Feature enrichment with Upgini highlights the impact of additional context (e.g., economic, weather, or demographic data) on forecasting accuracy.  
*(Detailed results, graphs, and metrics are shown in the Colab notebook.)*

## Repository Structure
- `notebooks/` → Jupyter/Colab notebooks with experiments  
- `data/` → (Optional) baseline datasets (if not too large)  
- `README.md` → Project documentation  

## Future Improvements
- Experiment with more advanced models (XGBoost, LSTMs).  
- Automate feature selection with Upgini.  
- Expand to larger and real-world datasets.  

## License
This project is for **educational and experimental purposes**.  
