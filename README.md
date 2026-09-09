**AI Business Intelligence Dashboard**

I'm building this project to learn how businesses can use data and AI to make smarter, more informed decisions across their entire company. 

The goal is to take a business dataset, clean and analyze the data while creating clear visualizations, and eventually use AI to look for patterns and insights that can make recommendations, which helps businesses in the long-run.

**What I'm Learning**
- Cleaning and working with data using Python and Pandas
- Exploring databases and finding patterns within
- Using SQL to learn basics and work with data
- Creating dashboards with Power BI
- Using AI to generate business insights
- Turning data into recommendations and then comparing/contrasting with future data

**Planned Features**
- Uploading a business dataset
- Cleaning and organizing the data
- Analyzing important business metrics
- Finding trends and patterns
- Creating visualizations for better view
- Building a Power BI dashboard
- Adding AI-generated insights
- Generating business recommendations

**Tools**

- Python
- Pandas
- NumPy
- SQL
- Power BI
- Scikit-learn
- AI / LLM API

**Project Status**

In Progress - This is an ongoing project that I'm building to improve my skills in Python, data analytics, AI, and business intelligence.

## Key Findings

- **Furniture generates nearly as much revenue as Office Supplies (\$755K vs \$732K) but only ~3% profit margin** compared to Office Supplies' ~17%. Furniture also has the highest average discount rate (17.3% vs 13.1% for Technology).
- **Tables are the single biggest profit problem in the business, losing \$17,753 overall** — more than 4x the losses of the next-worst sub-category (Bookcases, -\$3,632).
- **Tables are discounted at 25.8% on average** — over 10 points higher than the dataset average (~15.5%), making heavy discounting the most likely direct cause of their losses.
- **Sales show strong, repeating seasonality**: January and February are consistently the weakest months every year, while September, November, and December are consistently the strongest.
- **Tamara Chand is the most valuable customer**, generating \$8,981 in profit — 29% more than the next-highest customer (Raymond Buch, \$6,976).
- **Profit margin analysis reveals hidden risk**: Paper, Labels, and Envelopes have the healthiest average profit margins (~42%), while Binders (-19.5%) and Appliances (-14.9%) only look profitable in raw dollars because high sales volume masks many individual money-losing orders.
- **Shipping times align logically with service tier**: Standard Class averages ~5 days, Second Class ~3.2 days, First Class ~2.2 days, and Same Day ~0.04 days — confirming data integrity in the shipping fields.

## Visualizations

Charts that were created during analysis (see notebook for full code):
- Profit by Category
- Profit by Sub-Category
- Monthly Sales Trend (2023-2026)

## Interactive Dashboard (Tableau Public)
https://public.tableau.com/views/SuperstoreBIDashboard/SuperstoreBIDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

<img width="1998" height="1590" alt="image" src="https://github.com/user-attachments/assets/a59b5cb2-5776-4b82-9d39-2da982004cee" />

## AI-Generated Business Analysis
*Generated using Google Gemini API, grounded in real calculated metrics from this dataset (see notebook for full prompt/code).*

```
Based on the data provided, here is the business analysis addressing your four questions:

1. Which products/sub-categories are performing poorly, and by how much?
The three worst-performing sub-categories by profit are operating at a net loss:
- Tables: -$17,753.21 profit (loss of $17,753.2061)
- Bookcases: -$3,632.07 profit (loss of $3,632.0736)
- Supplies: -$1,171.39 profit (loss of $1,171.3945)

2. Which region should the company focus on, and why?
- To maximize proven growth: The company should focus on the West region, as it is the top profit driver generating $110,798.82, followed by the East region at $94,883.26.
- To address underperformance: Management may need to focus on the Central region, which generated the lowest profit at $39,865.31, as well as the South region at $46,749.43.

3. Who are the most valuable customers?
The top 5 most valuable customers by profit generated are:
1. Tamara Chand: $8,981.32
2. Raymond Buch: $6,976.10
3. Sanjit Chand: $5,757.41
4. Hunter Lopez: $5,622.43
5. Adrian Barton: $5,444.81

4. What should management do next? (Recommendations)
1. Address Unprofitable Sub-Categories: Mitigate or eliminate losses occurring in Tables (-$17,753.21), Bookcases (-$3,632.07), and Supplies (-$1,171.39). This will help improve the overall profit margin of the Furniture category, which is currently generating only $19,729.996 in profit compared to Office Supplies ($126,023.443) and Technology ($146,543.376).
2. Protect and Retain High-Value Customers: Focus retention efforts on key profit-generating accounts like Tamara Chand ($8,981.32) and Raymond Buch ($6,976.10), who represent a key portion of total customer profits across the 800 total customers.
3. Reallocate Capital to High-Margin Categories and Regions: Double down on selling Technology products ($146,543.38 profit) and Office Supplies ($126,023.44 profit) in high-performing markets like the West ($110,798.82 profit) and East ($94,883.26 profit) regions.
```

