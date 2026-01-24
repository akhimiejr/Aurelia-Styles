# Aurelia-Styles
# 1.1 Overview
Aurelia Styles is a multi-store fashion retail brand specializing in premium Afro-
contemporary apparel, footwear, and accessories. With stores across multiple regions
in Nigeria, the company serves a diverse customer base segmented by age, gender, and
loyalty status (VIP vs Regular). Aurelia Styles prides itself on blending traditional
Nigerian designs with modern fashion trends, offering products that cater to both
everyday wear and special occasions.
The company operates a mix of physical stores and sales channels, including in-store,
online, and mobile app platforms, allowing customers to shop conveniently while
providing comprehensive data on purchasing patterns. Aurelia Styles is committed to
delivering high-quality products, personalized customer experiences, and strategic
promotions that drive engagement and loyalty.
# 1.2 Aim of the Project
- Calculate key performance indicators (KPIs)such as total sales,net sales, and units sold.
- Perform aggregations, joins, and conditional queries to extract insights.
- Explore products,customers, sales,and stores to identify performance trends.
- Develop practical SQL skills using real-world retail data.
- Translate SQL query results into actionablebusiness decisions.
- Support inventory management, marketing strategies, and business growth through data-driven analysis.
- Analyze customer segments and understand purchasing behavior.
# 1.3 Data Description
#### i. Product Table Contains information about each product, including:
- product_id – Unique identifier for each product
- product_name – Name of the product
- product_category – Category of the product (e.g., Footwear,
- Traditional Attire, Accessories)
#### ii. Stores Table Provides details about store locations, including:
- store_id – Unique store identifier
- store_name – Name of the store
- region – Geographic region of the store
- state – State where the store is located
#### iii .Customer Table Contains details about each customer, including:
- customer_id – Unique identifier for each customer
- customer_name – Customer’s full name
- gender – Gender of the customer
- age_group – Age segment (Youth, Adult, Older)
- segment – Loyalty status (VIP, Regular)
#### iv. Channels Table Contains information about the sales channels:
- channel_id – Unique identifier for each channel
- channel_type – Type of channel (InStore, Online, Mobile App)
#### v. Sales Table Contains transactional sales data, including:
- sale_id – Unique identifier for each transaction
- customer_id & product_id – Links to customers and products
- store_id – Store where the sale occurred
- units_sold – Quantity sold
- sales_amount – Total sales before discount
- discount_applied – Discount applied on the transaction
- net_sales_amount – Sales after discount
- order_status – Status of the order (e.g., Completed)
- date – Transaction date
- channel_id – Sales channel (InStore, Online, Mobile App)
# 2.Analysis
## 2.1 Problem Statement
Aurelia Styles collects large volumes of transactional data from multiple stores, products, customers, and sales
channels. However, this data is underutilized, making it difficult for management to monitor sales performance,
understand customer behavior, and identify trends across products and regions.
Without effective analysis, the company struggles to make data-driven decisions on inventory management,
promotions, and store operations, which can impact revenue, customer satisfaction, and overall business
growth. This case study aims to help learners use SQL to transform raw data into actionable insights, enabling Aurelia
Styles to track KPIs, analyze sales and customer segments, and support informed business decisions.
## 2.2 Rationale for the Project
