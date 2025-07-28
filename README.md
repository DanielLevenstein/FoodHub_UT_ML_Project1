# FoodHub Data Analysis

## Project: Python Foundations – FoodHub

### Context

The number of restaurants in New York is increasing day by day. Many students and busy professionals rely on these restaurants due to their hectic lifestyles. Online food delivery services are a great option, providing access to food from their favorite places. 

**FoodHub**, a food aggregator app, connects users with multiple restaurants through a single platform. It manages customer orders, assigns delivery personnel, and collects ratings—all while earning a margin on each order.

---

### Objective

You’ve been hired as a Data Scientist at FoodHub. Your task: analyze customer order data to answer key business questions. The goal is to uncover trends that can help improve customer satisfaction and business performance.

---

### Dataset Description

The dataset records various attributes of food orders, including customer ratings, preparation and delivery times, and cuisine types.

**Data Dictionary:**
- `order_id`: Unique ID of the order  
- `customer_id`: ID of the customer  
- `restaurant_name`: Name of the restaurant  
- `cuisine_type`: Cuisine ordered  
- `cost_of_the_order`: Cost in USD  
- `day_of_the_week`: Weekday vs. weekend  
- `rating`: Customer rating (out of 5)  
- `food_preparation_time`: Time taken by restaurant (minutes)  
- `delivery_time`: Time taken by delivery person (minutes)  

---

### Key Findings

#### Cuisine Performance
- Strong correlation between cuisine type and customer ratings
- Top-rated cuisines: **Indian**, **Mexican**, **Japanese**, **Italian**, **Chinese**

#### Delivery Insights
- Orders with delivery times over 60 minutes still maintained a high average rating of **4.21**
- **Weekends** saw faster delivery times compared to weeknights

#### Revenue
- Average revenue per order: **$3.25**

---

### Recommendations

1. **Improve Search**: Make it easy for users to filter by price and cuisine type.
2. **Cuisine of the Week**: Feature top cuisines weekly with discounts to drive engagement.
3. **Targeted Promotions**: Run special offers for highly rated restaurants like:
   - The Meatball Shop *(Italian)*
   - Blue Ribbon Fried Chicken *(American)*
   - RedFarm Broadway *(Chinese)*
   - Shake Shack *(American)*
   - Blue Ribbon Sushi *(Japanese)*

---

### 🏆 Top Restaurants

#### Overall:

| Restaurant                      | Cuisine   | Avg Rating |
|--------------------------------|-----------|------------|
| Sushi of Gari Tribeca          | Japanese  | 4.6        |
| Blue Ribbon Sushi Bar & Grill  | Japanese  | 4.6        |
| Five Guys Burgers and Fries    | American  | 4.6        |
| The Meatball Shop              | Italian   | 4.5        |
| Han Dynasty                    | Chinese   | 4.4        |

#### Top by Cuisine:

| Cuisine         | Top Restaurant              | Avg Rating |
|-----------------|-----------------------------|------------|
| American        | Five Guys                   | 4.34       |
| Chinese         | Han Dynasty                 | 4.28       |
| Indian          | Tamarind TriBeCa            | 4.40       |
| Italian         | The Meatball Shop           | 4.25       |
| Japanese        | Sushi of Gari Tribeca       | 4.37       |
| Mediterranean   | Jack's Wife Freda           | 4.32       |
| Mexican         | Cafe Habana                 | 4.23       |
| Middle Eastern  | Cafe Mogador                | 4.15       |
| Southern        | Hill Country Fried Chicken  | 4.36       |

---

### 🛠️ Tools Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Jupyter Notebook

---

### 📁 How to Run

1. Clone the repository
2. Open the notebook in Jupyter
3. Run each cell top-to-bottom
4. View the included HTML report for a static overview
