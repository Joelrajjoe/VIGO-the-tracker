# VIGO - The Tracker

## Overview
VIGO - The Tracker is an AI-powered fitness tracking application designed to predict calorie expenditure based on user-specific biometric and exercise data. The system integrates machine learning models to provide personalized and real-time fitness insights, bridging the gap between conventional tracking and AI-driven analytics.

## Features
- **AI-Powered Calorie Prediction**: Uses machine learning models to estimate calories burned.
- **User-Friendly Dashboard**: Interactive UI built with Gradio.
- **Historical Data Tracking**: Enables users to monitor progress over time.
- **Real-Time Workout Insights**: Provides personalized workout efficiency analysis.
- **Seamless Cloud Execution**: Fully developed and executed in Google Colab.

## Technology Stack
- **Development Platform**: Google Colab
- **Machine Learning Models**: Random Forest Regression, SVR, Logistic Regression
- **Data Processing**: pandas, numpy, scikit-learn
- **Deployment**: Google Colab with ngrok for remote access
- **UI Framework**: Gradio

## Installation & Usage
Since the project is fully executed in **Google Colab**, you can run it directly without local installation. 

### Steps to Run in Google Colab
1. Open the Google Colab Notebook:
2. Run all cells sequentially.
3. Enter personal and workout details in the Gradio UI.
4. View real-time calorie predictions and analytics.

## Data Sources
- **Datasets Used**:
  - `exercise.csv` (Workout data)
  - `calories.csv` (Caloric expenditure data)
- **Preprocessing Techniques**:
  - Feature Selection
  - Label Encoding
  - Standardization

## Model Performance
| Model                | MAE  | MSE  | R² Score |
|----------------------|------|------|----------|
| Support Vector Regressor (SVR) | 0.57 | 1.51 | 0.9996 |
| Logistic Regression  | 6.22 | 85.18 | 0.9788 |
| Random Forest       | 1.68 | 6.94 | 0.9982 |

The **Random Forest Regressor** was selected as the final model due to its superior performance.

## Future Improvements
- Implement deep learning models for enhanced accuracy.
- Integrate real-time heart rate tracking.
- Store user data using Firebase for multi-user tracking.

## Contributors
- **Joelraj J** - joelraj712@gmail.com
- **Mentor**: Ms. Sowmya

## Acknowledgments
Special thanks to **TechSaksham – A joint CSR initiative of Microsoft & SAP** for the opportunity to develop this project as part of the **AICTE Internship on AI: Transformative Learning**.

## Contact
For any queries or contributions, please reach out at joelraj712@gmail.com.

