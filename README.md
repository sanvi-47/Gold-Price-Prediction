
This project predicts gold prices using Linear Regression and displays results via a Gradio interface. It trains on historical data (Days vs GoldPrice), evaluates with MSE, and allows users to input a number of days to get a predicted price. The model can be expanded with real data for better accuracy.Implements a supervised machine learning model using Linear Regression for price forecasting. Uses historical time-series data to identify trends in gold prices. Designed with a simple and user-friendly interface using Gradio.
Features
Real-time prediction based on user input (number of days)
Lightweight and fast model suitable for quick predictions
Interactive UI for easy experimentation
Modular code structure for easy enhancements
Scalable design to integrate live financial data APIs
🔹 Tech Stack
Python
Pandas (data preprocessing)
NumPy (numerical operations)
Scikit-learn (model building)
Gradio (UI interface)
🔹 Model Details
Used Linear Regression algorithm for prediction
Split dataset into training and testing sets
Evaluated performance using Mean Squared Error (MSE)
Visualized relationship between input (days) and output (price)
🔹 Workflow
Data collection and preprocessing
Feature selection (Days vs Gold Price)
Model training using Linear Regression
Model evaluation using MSE
Deployment using Gradio interface
🔹 Future Improvements 
Integrate real-time data using APIs (like gold price APIs)
Improve accuracy using advanced models (Random Forest, LSTM)
Add data visualization dashboards
Deploy on cloud platforms (AWS/GCP)
Enhance UI with better design and charts
🔹 Use Cases
Financial trend analysis
Educational ML project
Basic forecasting system prototype






















