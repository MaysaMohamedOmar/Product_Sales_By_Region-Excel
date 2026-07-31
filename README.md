## Product Sales by Region

# Introduction
In this project. I used a dataset in Excel to create insights on a company's sales figures in different regions. The findings gathered can be used by stakeholders such as shareholders and managers to find solutions on where to boost product sales and which regions are performing well.

Three questions I hope to answer:

1.Which region has the most sales and which has the lowest sales?

2.How are the salespeople performing?

3.Do products with promotions have higher sales?

# Tools and features used
- Excel
- Conditional formatting
- Count function
- Groupby function
- Name Manager feature
- Charts and graphs
- Go-To dialog box

# Data cleaning

After importing the data, I had to clean the data before manipulating it to find the key data I need.

<img width="1901" height="758" alt="Screenshot 2026-07-30 172111" src="https://github.com/user-attachments/assets/8ec3ee98-d87f-4a6f-a95b-2bfbbe2950d7" /> 


<img width="1837" height="776" alt="Screenshot 2026-07-30 172626" src="https://github.com/user-attachments/assets/290155ff-306c-4a97-8b31-ed2578b7b394" />

As shown, I was able to change data types to ensure columns with money had a currency format and columns with dates had a date format. 
I also used the COUNTBLANK function to calculate the number of null values in the table.

<img width="1793" height="695" alt="Screenshot 2026-07-30 191227" src="https://github.com/user-attachments/assets/a240e254-84eb-4fcb-ba18-79faa5d301df" />

I was able then able to fill in the null values in the Promotion column by replacing blank cells with NOPROMO.
I used conditional formatting after creating a Sales column to represent any sale above £5,000 in green and any sale below £1,000 in red. 


# Visualisation

<img width="702" height="402" alt="Screenshot 2026-07-30 230308" src="https://github.com/user-attachments/assets/63fc2ae3-f09b-43a9-8132-7fad78633bd1" />

This bar chart shows how much each region made in terms of sales.

<img width="781" height="397" alt="Screenshot 2026-07-30 223421" src="https://github.com/user-attachments/assets/301e1ab3-0f16-41c4-aea9-0fb7ff7fdece" />

With this bar chart, I was able to see the sales performance of each sales worker.

<img width="777" height="455" alt="Screenshot 2026-07-30 223445" src="https://github.com/user-attachments/assets/d62174fa-c81f-4f98-8b10-1b6979830907" />

This pie chart shows the total sales and  each slice to show specific promo code that is linked with sales or no promo code at all. 
