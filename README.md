# health-demand-forecasting-end-to-end-big-data-project
A Tanzania-focused research prototype for health-service demand forecasting, residual-based anomaly detection, and Spark-based data engineering using health-facility context and simulated service-demand data.
# AfyaStream AI

### An End-to-End Big Data and Machine Learning Pipeline
### for Health-Service Demand Forecasting and Anomaly Detection in Tanzania

**From Health Data to Actionable Insight.**

AfyaStream AI is a Tanzania-focused research prototype
exploring how data engineering, time-series forecasting,
and anomaly detection can support health-service planning
and early-warning review.

## Project Objectives

- Forecast monthly health-service demand.
- Detect unusual deviations in forecasted service patterns.
- Compare machine learning models against simple baselines.
- Evaluate performance across regions, services, and facilities.
- Demonstrate a Spark-based data pipeline and local
  streaming replay.

## Technology Stack

- Python
- Pandas and NumPy
- Apache Spark / PySpark
- Scikit-learn
- Matplotlib and Plotly
- Google Colab and Jupyter Notebook

## Data and Research Limitations

Facility context is based on a Tanzania health-facility
cohort. The health-service demand values used in the
current experiments are simulated, not observed hospital
service records.

Reported forecasting and anomaly-detection metrics
therefore describe performance on simulated data. They
must not be interpreted as real-world hospital performance.

The early-warning outputs are signals for review, not
clinical diagnoses.

## Run the Project

1. Open the notebook in Google Colab.
2. Run the notebook cells in order, starting from Stage 1.
3. Review the generated evaluation reports and figures.
4. Read the data and model cards before interpreting results.

## Project Status

Research prototype — simulated service-demand data;
real-world validation remains necessary.
