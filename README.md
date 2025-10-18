# **AtliQ.Co Performance Report**

## **Table of Contents:**

* Executive Summary
* Objectives
* Data Description
* Performance Report:
  * Overall Performance
  * Product Sales
  * Best Periods
  * Customer Demographics
  * Regional Performance
* Further Attention:
  * Customer Anomalies
* Recommendations
* Limitations and Warnings

## **Executive Summary**

**AtliQ.Co** is a hardware and computer accessories manufacturing company with distributors and customers spread across **India**. The company achieved a **total revenue of ₹985 million** and a **net profit of ₹24.5 million**.
The **sales peak** occurred on **January 1, 2019**, with a revenue of **₹2.7 million** and a profit of **₹1.5 million**.

**Electricalsara Stores** emerged as the **most profitable customer**, contributing **37% of the total profit**, which also made the **Central region** appear as the most profitable area.
The product **Prod329** was the most popular among Electricalsara Stores, while **Prod040** was the best-performing product overall, generating a **profit of ₹1 million**. AtliQ.Co’s dataset covers the period from **October 4, 2017**, to **June 26, 2020**.

<p align="center">
  <img src="https://github.com/AlHafidzLuhurDarma/Analisa_AtliQ_Manufaktur_Perangkat_Keras_Komputer/blob/main/gambar/Screenshot%202025-10-13%20121334.png" width=600 height=400>
</p>

## **Objectives**

The purpose of this report is to analyze the **sales performance** and **profitability** of **AtliQ.Co**, a computer hardware manufacturing company, during the period from **October 4, 2017, to June 26, 2020**.
This analysis aims to:

* Identify **customers**, **regions**, and **products** with the highest profit contributions.
* Determine the **best-performing time periods** in terms of financial performance.
* Evaluate the **efficiency of distribution channels** and **product types** (Own Brand vs. Distribution).
* Provide **business insights** and **strategic recommendations** to enhance future profitability.

## **Data Description**

<p align="center">
  <img src="https://github.com/AlHafidzLuhurDarma/Analisa_AtliQ_Manufaktur_Perangkat_Keras_Komputer/blob/main/gambar/Screenshot%202025-10-12%20102139.png" width=700 height=500>
</p>

The data analyzed consists of internal records from **AtliQ.Co** within the period **Q4 2017 – Q2 2020**, covering sales and profit transactions across various customers and products. The data is presented in a **relational table structure** with the following main entities:

* **Customer** – Contains information about distributors or retail customers, including name, customer type, and region.
* **Market** – Contains marketing region data that links customers to geographic zones (North, South, East, Central).
* **Product** – Includes product details such as product code, type (Own Brand / Distribution), and selling price.
* **Sales** – Contains sales transaction data, including order date, order number, revenue, and profit.

**Performance Report**

* **Overall Performance:** Sales reached their highest profit on **January 1, 2019**, with a **revenue of ₹2.7M** and a **profit of ₹1.5M**. The customer **Electricalsara Stores** dominated AtliQ.Co’s financial performance, contributing **37% of total profit**, making the **Central region** appear as the most profitable area. The product with code **Prod329** was the most favored by Electricalsara Stores, while **Prod040** was the most popular overall, generating a profit of **₹1M**. AtliQ.Co’s data covers the period from **October 4, 2017, to June 26, 2020**.

<p align="center">
  <img src="https://github.com/AlHafidzLuhurDarma/Analisa_AtliQ_Manufaktur_Perangkat_Keras_Komputer/blob/main/gambar/Screenshot%202025-10-13%20112835.png" width=600 height=400>
</p>

* **Product Sales:** AtliQ.Co offers **279 products**, consisting of **88 Distribution-type** and **191 Own Brand-type** products. The **Own Brand product with code Prod040** achieved the highest profit of **₹1M (4.6% of total product profit)**.

  * **Own Brand Products** generated **₹55M in revenue** with a **profit of ₹2.1M**, reaching their sales peak on **January 1, 2018**, with **₹4.3M revenue** and **₹86K profit**.
  * **Distribution Products** generated **₹18M in revenue** with a **profit of ₹257K**, also peaking on **January 1, 2018**, with **₹3.6M revenue** and **₹86K profit**.
  * In the provided dataset, **83% of product records lack product type information**, making the analysis of product types **statistically insignificant**.

* **Best Period:** It is important to note that the data only covers transactions from **October 4, 2017, to June 26, 2020 (Q4 2017 – Q2 2020)**, which limits the ability to analyze long-term growth patterns across variables.

  * **Year:** The best-performing year was **2018**, with a total profit of **₹8M**, marking a **7% increase** from the previous year and contributing **₹2.7M** in additional profit.
  * **Quarter:** **Q3** consistently produced the **highest profit growth**, with a **165% increase (₹2.4M)** in 2018 and **5% growth (₹2.4M)** in 2019. Although both years recorded the same profit amount in Q3, the **profit decline in Q2 2018** was the **smallest on record**, dropping only **₹9K (-71%)** compared to Q1 2018.
  * **Season:** The **winter season (December–February)** yielded the **highest profit** at **₹8M (33% of total profit)**, while the **post-monsoon season** recorded the **lowest profit** at **₹5M (20.3% of total)**. There was **no significant seasonal variation**, suggesting that **seasons did not strongly influence customer purchasing behavior**.
  * **Month:** **January** and **November** consistently ranked as the **most profitable months** each year. Across four years, **January** generated **₹99M in revenue** and **₹2.8M in profit**, while **November** (over three years) produced **₹92M in revenue** and **₹3M in profit**. **June** was consistently the **weakest month**, with total sales over three years yielding only **₹1M in profit**.

<p align="center">
  <img src="https://github.com/AlHafidzLuhurDarma/Analisa_AtliQ_Manufaktur_Perangkat_Keras_Komputer/blob/main/gambar/pertumbuhan%20per%20bulan.png" width=700 height=400>
  <img src="https://github.com/AlHafidzLuhurDarma/Analisa_AtliQ_Manufaktur_Perangkat_Keras_Komputer/blob/main/gambar/pertumbuhan%20per%20tahun.png" width=800 heigh=400>
</p>

* **Customer Demographics:** AtliQ.Co’s customers are not individuals but **distributors or retail stores** located across India (and outside India), totaling **38 customers**, consisting of **19 E-Commerce** and **19 Brick & Mortar** clients.

  * Overall, **Brick & Mortar customers** generated **₹744M in revenue** and **₹16M in profit**. **Electricalsara Stores** contributed the most among this group, with **₹9.3M in profit (37% of total Brick & Mortar profit)**, followed by **Premium Stores** with **₹1M (4.2%)**.
  * For **E-Commerce customers**, total **revenue reached ₹24M** with **₹8.5M in profit**. The **profit distribution** was relatively **balanced** compared to Brick & Mortar (where one client dominated), with **Nixon Store** being the **largest contributor** among E-Commerce customers, earning **₹1.7M (7.2% of total E-Commerce profit)**.

* **Regional Performance:** The customer **Electricalsara Shop**, located in the **Delhi NCR region**, contributed significantly to both revenue and profit, making **Delhi NCR account for 52% of total revenue (₹51M)** and **48% of total profit (₹11M)**.

  * In terms of overall regional distribution, the **North Zone** dominated with **6 total markets**, achieving **1.2M units sold**, **₹67M in total revenue**, and **₹15M in profit**. This zone accounted for **68% of total sales**, largely because **Delhi NCR** belongs to the **North Zone**.
  * When **Electricalsara Shop** is excluded (to normalize the distribution), the **North Zone** still remains dominant each year, peaking in **2019** with **67% of the total profit** that year.
  * The **South Zone** performed the weakest — despite having **5 markets**, it contributed **less than 5%** to both **total revenue (₹45M)** and **total profit (₹1M)**.


<p>
  <img src="https://github.com/AlHafidzLuhurDarma/Analisa_AtliQ_Manufaktur_Perangkat_Keras_Komputer/blob/main/gambar/profit%20zona%20tahun.png" width=600 height=400>
  <img src="https://github.com/AlHafidzLuhurDarma/Analisa_AtliQ_Manufaktur_Perangkat_Keras_Komputer/blob/main/gambar/zona.png" width=700 height=400>
</p>

## Further Attention

**Customer Anomalies:**
Customer distribution became a key focus during the analysis, particularly due to the overwhelming dominance of **Electricalsara Stores** in overall profit. The anomaly detection process was conducted using the **K-Means Clustering** method with **3 clusters** identified:

* **Cluster 1** – Consists of **14 customers** with an **average revenue of ₹17M** and a **profit margin of ₹600K**. Although relatively small in number, this group contributes significantly to overall profitability.
* **Cluster 2** – Contains **only 1 customer** with an **average revenue of ₹433M** and a **profit margin of ₹9M**. Despite being a single customer, its sales are far above the average of other customers.
* **Cluster 3** – Includes **23 customers** with an **average revenue of ₹14M** and a **profit margin of ₹200K**. These are smaller-scale customers who contribute to **sales stability** across the dataset.


<p align="center">
  <img src="" width=600 height=600>
</p>

Based on this clustering segmentation, **four customers** were identified as anomalies:

* **Electricalsara Stores** – This one is unsurprising, as it was detected as an **outlier** due to its values being **significantly higher** than all others.
* **Leader** – Exhibits an **exceptionally high profit per sale (₹48)**, which may indicate **products with very large margins** or a **potential pricing record error**.
* **Premium Stores** and **Electricalslytical** – Show **distinct patterns** compared to others, possibly indicating **emerging high-volume potential customers**.

## Recommendations

* **Management Team**

  * **Diversify Revenue Sources:** Avoid overdependence on a single major customer (Electricalsara Stores) by expanding the customer portfolio and reviewing long-term contract policies.
  * **Evaluate Regional Strategy:** Focus market development on the **South** and **East** zones, which still show growth potential. Provide additional **logistics and distribution support** to expand market reach.

* **Marketing and Sales Team**

  * **Target New Customers:** Concentrate promotional campaigns on **E-Commerce** and **Brick & Mortar** customers with profiles similar to **Premium Stores** or **Electricalslytical**, as they demonstrate strong potential.
  * **Optimize Own Brand Products:** Own Brand products have proven to be the most profitable. Strengthen **branding and promotional strategies** for this product segment.
  * **Leverage Seasonal and Sales Momentum:** Utilize **January and November** as peak months for annual promotions, as these months consistently deliver the **highest profits**.

## Limitations and Warnings

* **Data Limitations:** The dataset only covers the period from 2017 to 2020, making it impossible to observe long-term trends.
* **Outlier Dominance:** The customer **Electricalsara Stores** heavily dominates profits, which may introduce bias into the overall conclusions.
* **Lack of External Information:** External factors such as inflation, raw material prices, or competitor activity are not included in the dataset, meaning the analysis reflects only **internal performance**.
* **Potential Overfitting in Clustering:** The **K-Means–based customer segmentation** results may be unstable if new data with different patterns are introduced.
