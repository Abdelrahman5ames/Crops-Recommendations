

# Crop Recommendations 🌾  

A machine learning project designed to recommend the most suitable crops for farming based on environmental factors such as soil composition, temperature, humidity, rainfall, and more. This project aims to help farmers make data-driven decisions for sustainable agriculture and improved crop productivity.

## 📋 Dataset Overview  
The dataset used in this project contains the following columns and labels:

| **Column Name**     | **Description**                               |  
|----------------------|-----------------------------------------------|  
| **N**               | Nitrogen content in soil                      |  
| **P**               | Phosphorous content in soil                   |  
| **K**               | Potassium content in soil                     |  
| **Temperature**     | Average temperature (in degrees Celsius)      |  
| **Humidity**        | Percentage of air humidity                    |  
| **pH**              | pH value of soil                              |  
| **Rainfall**        | Annual rainfall (in mm)                       |  
| **Label**           | Recommended crop for the given conditions     |  

---

## 🚀 Features  
- **User-Friendly Prediction Model**: Input key environmental conditions, and the system provides the best crop recommendation.  
- **Data Insights**: Leverages soil and climate data for accurate predictions.  
- **Scalable**: The approach can be extended to larger datasets and different regions.  
- **Saved Model Results**: The trained model results have been saved for efficient predictions without needing retraining.  
- **Web Interface**: Built a Flask-based GUI for easy interaction and predictions.

## 🛠️ Tools and Libraries  
- **Programming Language**: Python  
- **Machine Learning Libraries**: Scikit-learn, Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Web Framework**: Flask  
- **Notebook Environment**: Jupyter Notebook  

## 📈 Methodology  
1. **Data Preprocessing**: Cleaned and prepared data for machine learning models.  
2. **Exploratory Data Analysis**: Visualized key trends and relationships between variables.  
3. **Model Training**: Implemented classification algorithms to predict the most suitable crops.  
4. **Saved Model**: Saved the trained model for future use to reduce loading times.  
5. **Evaluation**: Optimized the model to achieve high accuracy in predictions.  

## 🎯 Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/abdelrahman-abozarifa04/Crop-Recommendations.git
   cd Crop-Recommendations
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:  
   ```bash
   jupyter notebook Crop_Recommendations.ipynb
   ```
4. For the web interface, run:  
   ```bash
   python app.py
   ```
5. Follow the instructions in the notebook or web interface to test predictions.

## 📊 Results  
- Model Accuracy: **[Add accuracy percentage or R² score]**.  
- Performance Metrics: Analyzed to ensure robust predictions.  

## 🤝 Contributing  
Contributions are welcome! Feel free to open issues or submit pull requests.  

## 📧 Contact  
**Abdelrahman Abozarifa**  
- GitHub: [@abdelrahman-abozarifa04](https://github.com/Abdelrahman5ames)  
- Email: abdelrahmanahmedkhamiss@gmail.com  

## ⭐ Acknowledgements  
Special thanks to everyone involved in supporting sustainable agriculture through technology!  

