# PySpark Housing Price Prediction

### 🌟 **Overview**
In a dynamic housing market, accurately predicting property prices is essential for buyers, sellers, and real estate agents. This project leverages PySpark's big data processing capabilities to analyze extensive datasets and build robust machine learning models for housing price prediction.

### 🏗️ **Project Workflow**
1. **Data Preprocessing:** 
   - Cleaned and prepared data.
   - Encoded categorical features (e.g., furnishing status and location).
   - Scaled numerical data for consistency.
   
2. **Feature Engineering:** 
   - Derived features like per-square-foot price and neighborhood demand indicators.
   - Included property valuation trends for enhanced predictions.

3. **Model Training:** 
   - Algorithms used: Linear Regression and Decision Trees.
   - Linear Regression selected for deployment based on best RMSE and MAE scores.

4. **Evaluation and Optimization:** 
   - Assessed models with metrics like RMSE and MAE.
   - Fine-tuned the chosen model to improve performance.

5. **Deployment:** 
   - Integrated the model into a Flask application hosted on Render.
   - User-friendly interface with price outputs in ₹.

### 📈 **Technologies Used**
- **PySpark**: For big data processing and model training.
- **Flask**: For the web application interface.
- **Render**: Hosting platform for deployment.
- **Python Libraries**: Scikit-learn, pandas, matplotlib, seaborn, numpy.

### 💡 **Key Features**
- Predicts housing prices with high accuracy.
- Considers critical factors like area, bedrooms, bathrooms, and neighborhood amenities.
- User-friendly web interface for real-time predictions.

### 📊 **Dataset**
The dataset contains critical features for predicting housing prices:

Numerical: Area, bedrooms, bathrooms, parking, etc.
Categorical: Furnishing status, neighborhood, etc.
Derived features: Per-square-foot price, demand indicators, etc.
### ⚙️ **Deployment**
This application is deployed on Render. You can access it here.

### 📜 **License**
This project is licensed under the MIT License - see the LICENSE file for details.

### 🤝 **Contributing**
Contributions are welcome! Feel free to open issues or submit pull requests.

### The project is hosted on online 
Access through the following link: **https://hosuing-market-price-analysising.onrender.com/**
