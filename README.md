# Predictive Fault Detection in Photovoltaic Inverters using semi supervised learning

## Introduction

This project addresses the problem of fault detection and prevention in photovoltaic inverters through predictive analysis using semi-supervised machine learning techniques. Photovoltaic inverters, essential components for solar energy conversion, may experience failures that decrease their efficiency and availability, negatively impacting energy production. The primary objective is to predict faults and anomalies in these inverters using operational and meteorological data.

The proposed solution involves developing a fault prediction model based on Long Short-Term Memory (LSTM) neural networks and anomaly detection techniques such as Isolation Forest. Over 2 million operational data points from five inverters located in a photovoltaic plant were processed, integrating additional meteorological information obtained through the Open-Meteo API. Dimensionality reduction and normalization techniques were applied to optimize the performance of the models.

This solution is advantageous because, unlike conventional approaches, it can predict faults proactively, allowing for preventive measures and reducing downtime. Additionally, the use of time series-based models enables the capture of more complex and specific patterns, improving prediction accuracy.

The results obtained demonstrate that the LSTM model accurately predicted anomalies, although there is room for improvement in terms of temporal anticipation. This work lays the groundwork for future detailed research on the implementation of these models in real-world settings and their optimization to further enhance the efficiency of photovoltaic plants.

## Objectives

- Develop a predictive model for fault detection in photovoltaic inverters.
- Analyze operational and meteorological data to identify patterns leading to failures.
- Implement and evaluate machine learning techniques, including LSTM and Isolation Forest.

## Data

- **Operational Data:** More than 2 million records from five photovoltaic inverters.
- **Meteorological Data:** Collected via the Open-Meteo API.

## Methodology

1. **Data Collection:** Gather operational and meteorological data.
2. **Data Preprocessing:** Apply normalization and dimensionality reduction.
3. **Model Development:** Utilize LSTM networks and anomaly detection techniques.
4. **Evaluation:** Assess model performance in terms of accuracy and prediction capability.

## Results

- The LSTM model successfully predicted anomalies with considerable accuracy.
- Identified areas for improvement in the anticipation of fault occurrences.

## Future Work

- Explore further enhancements in model architecture and hyperparameters.
- Implement the model in real-world scenarios to evaluate practical applicability.
- Investigate the integration of additional data sources for improved prediction.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the Open-Meteo API for providing meteorological data.
- Appreciation to the team and resources that supported this research.

