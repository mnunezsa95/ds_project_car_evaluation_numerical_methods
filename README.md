# Rusty Bargain Car Valuation App
## Overview
Rusty Bargain, a leading used car sales service, is developing a mobile application to attract prospective customers by enabling them to swiftly determine the market value of their cars. The primary feature of the app is an accurate machine learning model that predicts car values based on historical data, including technical specifications, trim versions, and past prices.

## Description
This project involves building a robust and efficient machine learning model to provide accurate car market valuations. The data utilized includes detailed technical specifications, trim variations, and historical pricing data for various car models. The model will be integrated into the Rusty Bargain app, enhancing user experience through quick and reliable valuations.

## Objectives
The project focuses on three key objectives:

1. Prediction Quality: Develop a model that reliably estimates car market values, ensuring users receive accurate and dependable information.
2. Prediction Speed: Optimize the prediction process for rapid valuation, enhancing user experience within the Rusty Bargain app.
3. Training Efficiency: Streamline model training to minimize time and computational resources while maintaining high prediction accuracy.

## Methodology
The approach involves:
- Exploring various machine learning algorithms suitable for regression tasks.
- Evaluating their performance metrics.
- Refining the chosen model to meet Rusty Bargain’s rigorous standards for prediction accuracy, speed, and efficiency.

## Findings
Each model exhibited distinct capabilities and constraints. Notably:
- Light GBM Model: Achieved the lowest RMSE score with optimal hyperparameters, proving to be the most accurate.
- Decision Tree Regressor: Fastest training speed.
- Random Forest Regressor: Second lowest RMSE score but slower training speed compared to Light GBM.

The LightGBM model's integration into the Rusty Bargain app marks a significant enhancement in predictive accuracy and speed for vehicle valuations. Despite a slightly slower prediction time, LightGBM's efficiency and precision ensure a seamless user experience, providing prompt and reliable valuations based on comprehensive data.

## Libraries
The following libraries were utilized in this project:
- LightGBM
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

## Conclusion
The adoption of LightGBM underscores Rusty Bargain's strategic approach to leveraging advanced machine learning techniques to enhance app capabilities. By optimizing both prediction accuracy and speed, Rusty Bargain ensures its users benefit from dependable and efficient vehicle valuations, setting a new standard in the industry.

