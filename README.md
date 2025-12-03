# predict_car_price
This project is to demonstrate used car price prediction machine learning model which can be used by sales team to stock up inventory and provide insights on which car sells more and can help predict price of an used car

## How to get started
In order to get this project running please download the code using the git clone command

  - 'git clone git@github.com:ashrivastav33/predict_car_price.git'

## Note
- We are making an assumption you already are familiar with using Jupyter Notebook using tools like Google Colab or Jupyter etc.
- You will need an internet connection to download/read the dataset or csv file

## Project Structure

### - /data/vehicles.csv    ---> Stores the dataset used for this project
### - /code/predict_car_price_ashri33.ipynb            ---> Stores the code/jupyter notebook used for this project

## Results

### Conclusion

After analyzing data from over 400,000 used vehicle sales, the team developed a linear regression model to predict sale prices based on various vehicle characteristics, including model, condition, and age, achieving an average accuracy of approximately ±20%. Beyond providing recommended listing prices for new vehicles, the model’s greatest value lies in its ability to quantify the impact of specific features on price, helping inform decisions when evaluating potential inventory.

Among all the characteristics analyzed, a vehicle’s age has the most significant influence on its value. However, the relationship is not strictly linear, so there isn’t a simple formula to deduct a fixed amount per year. In general, older vehicles tend to have a stronger negative impact on price compared to newer ones

### Used Vehicle Price Analysis | Findings | Learnings

- Data: 400,000+ used vehicle sales analyzed.

- Model: Linear regression predicts price from features like age, model, condition, manufacturer, and color.

- Accuracy: Average prediction error of ~20%.

- Key Insights:

  - Age: Biggest factor; older cars lower price more.
  - Model & Manufacturer: Certain models (e.g., Skyline GTR 32) and brands (e.g., Ferrari) increase value; others reduce it.
  - Condition: Excellent / Like New boosts price; Salvage / Fair reduces it.
  - Color: Small effect; some colors slightly increase/decrease value.

## Conclusion

### Learning

- It was fun to work on this assignment, I did learn that building a machine learning model requires understanding the dataset, applying the concepts which can take time and practice
- Machine Learning model can initially take time to run if the dataset it huge and we can easily overfit or underfit the model
- Its easy to get lost and keep track of your machine learning model flow, hence keep track of what you are doing either in a notepad or roughbook

## Next Steps and Recommendations

 - We can explore more scenarios to learn meaningful insights from the data
 - Use insights to price cars competitively.
 - Focus on features that impact price most when buying inventory.
 - Improve data quality for better future predictions.
