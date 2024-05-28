# 🚒 Wildfire Prediction Hackathon 2024

## Overview
**Wildfire Prediction Hackathon** hosted by Wat.AI, Waterloo.AI, and DSC. This one-day hackathon brought together innovative minds to tackle the critical challenge of predicting wildfire growth. Our team participated with the aim of developing a robust model that can forecast future fire spread using diverse environmental data.

## Team Members
- **Mevan Solanga** 
- **Sheldon Lewis** 
- **Samudra Perera** 
- **Vansh Jain**
- **Xiangru Mo** 

## Project Goal
Our goal is to create a predictive model that forecasts wildfire growth. The model leverages multiple data sources, including weather conditions, fire weather indices, topography, fire fuel, and past fire growth data. Accurate predictions can help in early intervention and effective management of wildfire incidents, ultimately saving lives, property, and natural resources.

## Dataset
The dataset encompasses various aspects of environmental data:

- **Fire Growth Data**: Tracks day-to-day progression of fires.
- **Fire Weather Index Data**: Indicators such as the Fine Fuel Moisture Code (FFMC), Duff Moisture Code (DMC), and more.
- **Weather Data**: Relative humidity, wind speed, wind direction, temperature, and precipitation.
- **Topography Data**: Digital Elevation Model (DEM) and slope information.
- **Fire Fuel Data**: Types of vegetation and fuel that contribute to fire spread.
- **Fire Hotspot Data**: Collected from satellite sensors, detailing specific fire hotspots.

### Dataset Structure
- `fire/`: Contains fire growth data.
- `fire_weather/`: Contains fire weather index data.
- `weather/`: Contains weather data.
- `topography/`: Contains topography data.
- `fuels/`: Contains fire fuel data.
- `fire_hotspot/`: Contains satellite-based fire hotspot data.

## Methodology
Our approach involves the following steps:
1. **Data Preprocessing**: Cleaning and normalizing the data to ensure consistency and accuracy.
2. **Feature Engineering**: Extracting relevant features from the dataset to improve model performance.
3. **Model Development**: Implementing machine learning algorithms to predict wildfire growth.
4. **Evaluation**: Assessing model performance using metrics like accuracy, precision, recall, and the mean Intersection over Union (mIoU).
5. **Optimization**: Fine-tuning the model to achieve the best possible predictive accuracy.

## Tools and Technologies
- **Programming Languages**: Python
- **Libraries**: PyTorch, NumPy, pandas, rasterio, scikit-learn, matplotlib
- **Platforms**: Kaggle, Google Colab

## Results
Our model demonstrated a strong ability to predict wildfire growth, with the following metrics:
- **Accuracy**: 74.859%
- **Precision**: XX%
- **Recall**: XX%
- **mIoU**: XX%

These results indicate the potential of our model to assist in wildfire management and prevention efforts.

## Challenges
Throughout the hackathon, we faced several challenges:
- Handling large and complex datasets.
- Balancing the trade-off between model complexity and performance.
- Ensuring the model generalizes well to unseen data.

## Future Work
Moving forward, we aim to:
- Integrate additional data sources to further enhance prediction accuracy.
- Develop real-time prediction capabilities.
- Collaborate with wildfire management agencies to deploy our model in operational settings.

## Acknowledgments
We would like to thank Wat.AI, Waterloo.AI, and DSC for organizing this hackathon and providing us with the opportunity to contribute to such a crucial cause. Additionally, we extend our gratitude to the mentors and fellow participants for their invaluable support and insights.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
