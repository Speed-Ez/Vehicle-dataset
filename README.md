# Vehicle-dataset
###  **Used Cars Dataset from Kaggle**

## **Overview**
This report presents an analysis of car sales trends from 2008 to 2019, highlighting key insights and model performance. The findings provide a comprehensive understanding of consumer preferences and purchasing behaviors, helping to refine sales and marketing strategies.

## **Cleaning and PreprocessingOverview**
- The data contained null values in some columns. This was 1.8% of the entire data values. We dropped missing values
- There are a good number of outlier values in the dataset.
- It is important to understand if the outliers is legitimate or erroneous
In a car dataset where values like price, mileage, or features naturally have a wide range, it is not always wise to remove outliers outright. luxury or premium cars (e.g., selling for 3M) could be real and not erroneous data.
One erroneous oultier in the Year column is the 1988 year which will be remove. The next year after that is 2006
- Price and Kilometer columns, the values above the upper_bound (detected as outliers) are much. From the context of the data, we can infer that these values are legitimate and not erroneous. However these high values in the Price column are concentrated between 5million to 10million, with only 21 values above 10 million up 35million. To avoid a skewed data and a bad model, we will put a cap at 10million by removing values above 10 million. Same thing appplies to the Kilometer column, with only 6 values above 200000 cluster

## **General Insights**
- Peak Sales Year: Car sales reached their highest in 2018.
- Manual vs. Automatic Transmission: Manual cars consistently outperformed Automatic cars in sales from 2008 to 2019, mainly due to their lower cost. However, sales of Manual cars began to decline after 2019.
- Fuel Type Preferences: Diesel and Petrol vehicles were the most popular choices among buyers. Diesel cars, despite their higher cost, achieved superior sales due to better performance and easier maintenance.
- Ownership Trends: Most cars sold were from first owners, indicating that consumers prefer cars in better condition. Cars with multiple owners had lower sales and diminished resale value.
- Drivetrain Preference: Forward Wheel Drive (FWD) cars were the most commonly sold, suggesting a strong market preference for this drivetrain type.

## **Key Recommendations**
🚗 Manual vs. Automatic Pricing
Manual cars have been a favorite because they are more affordable. If automatic cars are to gain more traction, adjusting their pricing or adding incentives (like better financing options) could make them more appealing.

⛽ Diesel Cars' Advantages
Despite being more expensive, diesel cars saw strong sales, likely because they offer better power and performance. Highlighting these perks in marketing campaigns could help attract more buyers who prioritize durability and efficiency.

👤 Focus on First-Time Buyers
Since most cars sold were from first owners, dealerships could target first-time buyers with warranties, financing options, and maintenance packages. Reinforcing the reliability of first-owner cars could also build trust and drive more sales.

🔄 Encourage Longer Ownership
Cars with multiple previous owners tend to lose value faster. Promoting long-term ownership or offering trade-in incentives might help maintain value and keep customers engaged for longer. Maintenance packages could also encourage buyers to keep their cars in better shape.

🛞 Forward Wheel Drive Preference
Forward Wheel Drive cars were the top choice for buyers. Expanding this category and pushing its benefits in marketing could help brands align with consumer demand and boost market share.

By tailoring strategies to these trends, manufacturers and dealerships can better meet customer needs while maximizing sales opportunities.
