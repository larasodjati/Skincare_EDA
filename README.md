# Skincare Product Analysis

## Description
This project analyzes skincare products to determine the prevalence of harmful ingredients and their impact on product ratings and consumer sentiment. The dataset includes various skincare products, their ingredients, prices, and user ratings.

## Data Sources
- [Skincare Product Ingredients](https://www.kaggle.com/datasets/dominoweir/skincare-product-ingredients): This dataset contains detailed information on various skincare products and their ingredients.
- [Safer Chemical Ingredients List (US EPA)](https://www.epa.gov/saferchoice/safer-ingredients#greencircle): This dataset from the US Environmental Protection Agency (EPA) provides information on chemicals that meet Safer Choice Criteria.

## Analysis
In this study, we will:
1. **Identify Harmful Ingredients**: Utilize a reliable database to classify ingredients based on their safety profiles.
2. **Determine Prevalence**: Calculate how common these harmful ingredients are in various skincare products.
3. **Analyze Consumer Sentiment**: Perform sentiment analysis on consumer reviews to gauge awareness and reactions to harmful ingredients.
4. **Evaluate Product Ratings**: Assess how the presence of harmful ingredients affects product ratings.
5. **Correlation Analysis**: Explore the relationship between harmful ingredients, consumer sentiment, and product ratings.
6. **Provide Insights and Recommendations**: Offer actionable recommendations for manufacturers and regulators based on our findings.

## Summary, Conclusion, and Insights
Prevalence of Harmful Ingredients in Skincare Products:
- Total number of skincare products: 1472
- Total number of skincare products with harmful ingredients: 863
- Prevalence of harmful ingredients: 58.63%

This indicates that a significant portion of skincare products in the dataset contain harmful ingredients, making up more than half of the total products analyzed.

The analysis shows that 58.63% of the skincare products in our dataset contain harmful ingredients. This high prevalence suggests that consumers need to be aware of the products they use. It also indicates a potential area of improvement for skincare product manufacturers to reduce or eliminate harmful ingredients in their formulations.

The presence of harmful ingredients can significantly impact consumer sentiment and product ratings, as shown in subsequent analyses. Manufacturers who prioritize safer ingredients may see a positive impact on consumer satisfaction and product reputation.

![Screenshot of the pie chart of total skincare products with and without harmful ingredients](https://github.com/larasodjati/Skincare_EDA/blob/main/Pie%20Chart%20Skincare%20Products.png)

Sentiment distribution in Skincare product

Sentiment distribution with harmful ingredients:
Positive: 74.04%
Neutral: 23.64%
Negative: 2.32%

Sentiment distribution without harmful ingredients:
Positive: 80.30%
Neutral: 17.90%
Negative: 1.81%

The data shows that products without harmful ingredients tend to have a higher proportion of positive sentiment and a lower proportion of neutral and negative sentiments compared to products with harmful ingredients.

The sentiment analysis reveals significant differences between products with and without harmful ingredients. Products without harmful ingredients tend to receive more positive reviews (80.30%) compared to those with harmful ingredients (74.04%). On the other hand, products with harmful ingredients have a higher proportion of neutral (23.64%) and negative sentiments (2.32%) than those without harmful ingredients (17.90% neutral and 1.81% negative).

These findings suggest that the presence of harmful ingredients in skincare products can negatively impact consumer sentiment, leading to lower product ratings and potentially affecting brand reputation. Manufacturers should consider formulating products with safer ingredients to enhance consumer satisfaction and foster positive reviews.

![Screenshot of the pie chart of sentiment distribution with and without harmful ingredients](https://github.com/larasodjati/Skincare_EDA/blob/main/Pie%20Chart%20Sentiment%20Distribution.png)
