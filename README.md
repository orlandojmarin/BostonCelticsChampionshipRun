# Boston Celtics 2023-2024 Season Analysis  

## Overview  
This project leverages machine learning to analyze and predict the outcomes of the Boston Celtics' 2023-2024 NBA season. Our goal is to explore how statistical metrics impact game results and to gain insights into the team's performance.  

## Goals  
1. Predict the number of points scored by the Celtics and their opponents in each game.  
2. Estimate the number of wins achieved by the Celtics during the season.  
3. Identify the most impactful statistics contributing to game outcomes.  

## Technologies  
- **Python** for data analysis and modeling  
- Key libraries:  
  - **pandas**: Data manipulation  
  - **numpy**: Numerical computations  
  - **scikit-learn**: Machine learning  
  - **matplotlib** and **seaborn**: Data visualization  

## Dataset  
- **Source**: [Basketball Reference](https://www.basketball-reference.com)  
- Dataset filtered for Boston Celtics' 2023-2024 season games.  
- Additional columns were created for analysis:  
  - `Location`: Home or Away  
  - `Result`: Win (W) or Loss (L)  
  - `Predicted_PTS`: Predicted points rounded to the nearest whole number  
  - `Predicted_Result`: Predicted game outcome (W or L)  

## Results  
### Points Prediction Accuracy  
- Mean Absolute Error (MAE): **3.37 points per game** for both Celtics and their opponents.  
- **Prediction Accuracy**:  
  - 31.7% of Celtics’ scores predicted within 1 point.  
  - 81.7% of Celtics’ scores predicted within 5 points.  

### Game Results Prediction Accuracy  
- Accurately predicted **95.1%** of Celtics game results.  
- Predicted a win differential of -2 (64 actual wins vs. 62 predicted wins).  

### Key Factors for Winning Games  
Based on feature importance from Random Forest models:  
1. **Shooting Percentage**: Field Goal % and Three-Point %  
2. **Assists**: Indicates strong team playmaking  
3. **Free Throw Attempts**: Reflects offensive aggression  
4. **Rebounds**: Defensive and total rebounds are critical for possession control  

## Visualizations  
Explore the code (Google Colab) for detailed charts and graphs showcasing:  
- Feature importance rankings  
- Predicted vs. actual game outcomes  
- Insights into shooting efficiency and other key metrics  

## Contributors  
The following contributors brought this project to life:  
- **Orlando Marin**  
- **Tatiana Eng** 
- **Asia Osimeh** 

## Conclusion  
This project showcases the potential of machine learning in sports analytics, emphasizing the importance of data in analyzing team performance. By combining technical methods with basketball insights, we developed a strong framework for predicting game results and pinpointing key factors for success.
