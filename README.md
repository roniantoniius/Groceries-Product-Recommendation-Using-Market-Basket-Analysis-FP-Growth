# Groceries Product Recommendation Using Market Basket Analysis

![image](https://github.com/roniantoniius/Groceries-Product-Recommendation-Using-Market-Basket-Analysis-FP-Growth/assets/121453378/5b5da1ba-611a-4128-b6b7-1f029ad70919)
Image sources: Pexels.com

The project "Groceries Product Recommendation Using Market Basket Analysis" aims to solve problems related to improving customer satisfaction and sales in the retail industry. In this context, retailers often struggle to understand customer buying patterns, which can lead to sub-optimal stocking and less effective marketing strategies. The goal of this project is to identify associations between products that are frequently purchased together, thus enabling retailers to recommend relevant products to customers, increase cross-product sales, and optimize product placement in stores. The solution offered was to apply Market Basket Analysis (MBA), an analytics technique capable of discovering association patterns in purchase transaction data. By applying MBA, retailers can better understand customer needs and preferences, and develop more effective sales strategies.

Market Basket Analysis (MBA) is a method used to analyze transaction data to find association patterns between products that are often purchased together. The concept is based on Association Rule Learning techniques, which identify relationships between items in large datasets. In this project, we used three main algorithms to implement MBA: Apriori, Eclat, and FP-Growth. Apriori algorithm works by finding frequently occurring itemsets and then building association rules from them, with advantages in simplicity and easy interpretation. Eclat uses an intersecting technique to find frequent itemsets, which allows efficiency in storage space but can take longer to execute. FP-Growth optimizes the search by building a tree structure that combines similar transactions, thus speeding up the process of mining frequent itemsets. By using the best performing model, the project was able to provide accurate and relevant product recommendations based on customer purchase patterns, ultimately improving the shopping experience and store profitability.


### Model Performance:
- ECLAT algorithm has the highest time complexity (seconds) of 78 when compared to FP-Growth which has the lowest of 1.
- ECLAT and FP-Growth algorithms have the highest number of association rules at around 1750, while Apriori has 750.
- Support in the Apriori algorithm is large enough to reduce the number of rules generated, focusing on itemsets that are more common and significant.
- Confidence of the Apriori algorithm has better performance because it has strong rules.
- The ideal lift value is usually in the range of 1.2 - 1.5 this is proven by the performance of the Apriori algorithm. However, the FP-Growth algorithm has a larger lift which shows a stronger relationship between itemsets A and B than if they were independent.


## Evaluation Result

**FP-Growth** is the best overall performing algorithm for Market Basket Analysis. Its execution time is very fast, it generates a lot of rules that can provide a lot of insights, and the larger lift value indicates a strong itemset relationship.

However, if you are looking for rules that are easier to analyze and rely on, **Apriori** is also a good choice as it produces stronger and more significant rules with lift values in the ideal range.

**ECLAT** is not recommended if execution time is an important factor due to its high time complexity.


## Documentation Result
#### Time Complexity:

![image](https://github.com/roniantoniius/Groceries-Product-Recommendation-Using-Market-Basket-Analysis-FP-Growth/assets/121453378/9b927602-1a75-40ad-9cdd-0794718bd4eb)

#### Count of Rule Association:

![image](https://github.com/roniantoniius/Groceries-Product-Recommendation-Using-Market-Basket-Analysis-FP-Growth/assets/121453378/a6c63c1a-ed00-4e74-aca5-8bc95bb2cbfc)

#### Support:

![image](https://github.com/roniantoniius/Groceries-Product-Recommendation-Using-Market-Basket-Analysis-FP-Growth/assets/121453378/233a000b-e0a0-479c-b64c-77fda428365f)

#### Confidence:

![image](https://github.com/roniantoniius/Groceries-Product-Recommendation-Using-Market-Basket-Analysis-FP-Growth/assets/121453378/8cbb991f-fab5-48e1-ad2f-a410c8f414e3)

#### Lift:

![image](https://github.com/roniantoniius/Groceries-Product-Recommendation-Using-Market-Basket-Analysis-FP-Growth/assets/121453378/1eb7f245-f884-432c-b722-9b376d4f130b)

#### FP-Growth:

![image](https://github.com/roniantoniius/Groceries-Product-Recommendation-Using-Market-Basket-Analysis-FP-Growth/assets/121453378/6d4fd855-a7b6-40ce-b746-a16a2ae12b89)

#### Product Always Sold Association:

![image](https://github.com/roniantoniius/Groceries-Product-Recommendation-Using-Market-Basket-Analysis-FP-Growth/assets/121453378/ecc5be14-8f25-475b-8543-ce6fdb7f113f)
**Toothbrush** dan **toothpaste** memiliki nilai confidence yang tinggi. Sehingga kedua produk tersebut sering sekali dibeli secara bersamaan. Disusul dengan Mop dan Toothpaste

#### Product Recommendation based on Confidence:
![image](https://github.com/roniantoniius/Groceries-Product-Recommendation-Using-Market-Basket-Analysis-FP-Growth/assets/121453378/1c48ef7e-bd35-4222-a420-677786849451)




