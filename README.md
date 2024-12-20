# CIS_2100_project3_v2
**Stores with best selling items** 
     StoreID BestSellingItem  SalesCount
0  Store_003              TV          12
1  Store_001          Tablet          11
2  Store_002      Smartphone          10

The analysis of individual store sales revealed the top-selling items for three major stores. Store_003 achieved the highest success with the TV, selling 12 units, followed by Store_001, where Tablets dominated sales with 11 units. Store_002 excelled in selling Smartphones, recording 10 sales. These findings highlight how customer preferences can vary significantly between locations, emphasizing the need for store-specific strategies to maximize sales performance.


**Top 10 Best-Selling Items Across the Corporation: **
Product Name
TV            28
Camera        26
Smartphone    25
Tablet        21
Smartwatch    20
Headphones    15
Laptop        13
Name: count, dtype: int64


At the corporate level, TVs emerged as the most popular product, selling 28 units across all stores. Cameras and Smartphones closely followed with 26 and 25 units sold, respectively, while Tablets and Smartwatches rounded out the top five. This data underscores the widespread appeal of versatile electronic products, which collectively account for the majority of sales and reflect broader consumer trends within the corporation.


**Top 5 Frequent Itemsets for Store Store_003:**

**Market basket analysis** at Store_003 revealed that TVs were the most frequently purchased item, appearing in 60% of orders. Other popular items included Smartwatches (53.33%), Smartphones (46.67%), Cameras (33.33%), and Laptops (33.33%). This suggests that customers in this store tend to prefer a mix of entertainment and productivity-related electronics, offering opportunities for targeted promotions.

In Store_001, Cameras led the frequent itemsets, appearing in 60% of orders, followed by TVs at 53.33% and Tablets at 46.67%. Interestingly, combinations such as TVs and Cameras were purchased together in 33.33% of orders, revealing potential bundling opportunities to drive sales further. The high popularity of imaging and display products highlights a specific customer interest in content creation and consumption.





TV - Purchased together in 60.0% of orders.
Smartwatch - Purchased together in 53.33% of orders.
Smartphone - Purchased together in 46.67% of orders.
Camera - Purchased together in 33.33% of orders.
Laptop - Purchased together in 33.33% of orders.


Top 5 Frequent Itemsets for Store Store_001:


Camera - Purchased together in 60.0% of orders.
TV - Purchased together in 53.33% of orders.
Tablet - Purchased together in 46.67% of orders.
TV, Camera - Purchased together in 33.33% of orders.
Smartphone - Purchased together in 33.33% of orders.


Top 5 Frequent Itemsets for Store Store_002:

Smartphone - Purchased together in 46.67% of orders.
Smartwatch - Purchased together in 46.67% of orders.
Camera - Purchased together in 40.0% of orders.
Headphones - Purchased together in 40.0% of orders.
TV - Purchased together in 33.33% of orders.


Store_002 demonstrated a strong demand for Smartphones and Smartwatches, each appearing in 46.67% of orders. Cameras and Headphones followed, both purchased in 40% of transactions, while TVs appeared in 33.33%. This suggests that customers at Store_002 favor personal and mobile electronics, making it an ideal location to prioritize portable and wireless devices in promotional efforts.




**Top 10 Stores with Highest Total Sales:**
     StoreID    Price  Rank
0  Store_001  41700.0     1
2  Store_003  40300.0     2
1  Store_002  33300.0     3

Store_001 achieved the highest total sales across all stores, generating $41,700 in revenue. Store_003 followed closely with $40,300, while Store_002 secured $33,300. These results highlight the strong performance of these stores, driven by the popularity of their top-selling items. The insights gained can be leveraged to replicate their success across other locations and refine inventory planning.


**Report and goals**
The primary goal of this project was to create a comprehensive analysis of sales data for a corporation with multiple stores, leveraging advanced data processing and analytical techniques to extract actionable insights. This work builds on our earlier projects, where we developed the foundational elements of the corporation's digital twin. In Project 1, we established the object-oriented structure of the corporation, defining entities such as Products, Orders, Customers, Stores, and the Corporation itself. In Project 2, we extended this framework to generate realistic sales data, implementing CSV outputs to simulate a year’s worth of transactions. Finally, this project focused on analyzing customer purchasing behavior, identifying best-selling items, and uncovering patterns using market basket analysis to support strategic decision-making. This project successfully demonstrated how object-oriented design, data generation, and analysis can be integrated into a cohesive workflow. The findings not only provide immediate value but also serve as a blueprint for scaling similar analyses in real-world scenarios. With the insights gained, the corporation can strategically enhance its operations, aligning its offerings with customer demands to maximize profitability and customer satisfaction.

For more details on the foundational object-oriented model (Project 1), please see https://github.com/Daeton1/project2_2100

For the data generation scripts and logic (Project 2), please see https://github.com/Daeton1/CIS_2100_deliverable1

**Basket ananlysis** The market basket analysis reveals significant patterns in customer purchasing behavior across the corporation's stores. At Store_003, TVs dominated orders, appearing in 60% of transactions, followed by Smartwatches (53.33%) and Smartphones (46.67%), highlighting a preference for entertainment and mobile electronics. At Store_001, Cameras (60%) and TVs (53.33%) led sales, with Tablets frequently purchased alongside these items, and notable combinations like TVs and Cameras purchased together in 33.33% of orders. Store_002 showed strong demand for Smartphones and Smartwatches, both appearing in 46.67% of orders, alongside Cameras and Headphones, indicating a focus on portable and wireless products. At the corporate level, TVs, Cameras, and Smartphones emerged as the top-selling products, reflecting broad customer preferences for versatile electronics. Stores with the highest total sales, such as Store_001 ($41,700) and Store_003 ($40,300), provide benchmarks for success, demonstrating the value of tailoring inventory and promotional strategies to local demands. Recommendations include bundling frequently purchased items, optimizing inventory for high-demand products, and replicating the strategies of high-performing stores to drive growth across the organization. This analysis demonstrates an end-to-end data science workflow—from object-oriented modeling to data simulation and advanced analytics—showing my ability to handle complex data scenarios, derive strategic insights, and communicate findings to stakeholders

**Methodology**
Our methodology combined a strong conceptual framework with a rigorous analytical approach. We began by creating an object-oriented representation of the corporation’s ecosystem—encompassing products, orders, customers, and stores—thereby mirroring real-world relationships and operations within a digital twin. Building upon this foundation, we generated a full year’s worth of realistic sales transactions in CSV format, laying the groundwork for in-depth market basket analysis. After cleaning and standardizing the dataset, we applied frequency-based metrics and, where appropriate, association rule mining (e.g., the Apriori algorithm) to uncover patterns and correlations among products. This enabled us to identify top-selling items, frequent item co-occurrences, and emergent product groupings, translating raw data into strategic insights. By integrating these findings with store-level and corporate performance metrics, we established a blueprint for data-driven decision-making, guiding inventory optimization, promotional strategies, and long-term organizational growth.









