
# Comprehensive Analysis of Retail Transactional Dataset

This repository contains a comprehensive analysis of a retail transactional dataset. The analysis includes customer demographics, purchasing patterns, product preferences, feedback analysis, and transaction logistics.

## Table of Contents

- [Comprehensive Analysis of Retail Transactional Dataset](#comprehensive-analysis-of-retail-transactional-dataset)
  - [Table of Contents](#table-of-contents)
  - [About Dataset](#about-dataset)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Analysis Sections](#analysis-sections)
    - [Customer Demographics Analysis](#customer-demographics-analysis)
    - [Purchasing Patterns Analysis](#purchasing-patterns-analysis)
    - [Product Preferences Analysis](#product-preferences-analysis)
    - [Feedback Analysis](#feedback-analysis)
    - [Transaction Logistics Analysis](#transaction-logistics-analysis)
    - [Correlation Analysis](#correlation-analysis)
    - [Customer Segmentation](#customer-segmentation)
  - [Summary](#summary)
  - [Conclusion](#conclusion)
  - [Contributing](#contributing)
  - [License](#license)

## About Dataset

The dataset contains detailed information about retail transactions, aimed at providing a comprehensive view of customer behavior and purchasing patterns. Here’s a breakdown of the various attributes and what they entail:

**Customer Information:**

- Customer ID: A unique identifier for each customer.
- Name: Customer’s full name.
- Email: Customer’s email address for communication.
- Phone: Contact number of the customer.
- Address: Physical address of the customer.
- City, State, Zipcode, Country: Geographic details of the customer.
- Age: Age of the customer.
- Gender: Gender of the customer.
- Income: Income bracket or level of the customer.
- Customer Segment: Classification of customers based on behavior or demographics.

**Transaction Details:**

- Last Purchase Date: Date of the customer’s most recent purchase.
- Total Purchases: Total number of purchases made by the customer.
- Amount Spent: Total monetary amount spent by the customer.

**Product Information:**

- Product Category: Category to which the purchased product belongs (e.g.  electronics, clothing, groceries).
- Product Brand: Brand name of the product.
- Product Type: Type or model of the product purchased.

**Feedback:**

- Feedback: Customer’s feedback or rating related to the product or service received.

**Transaction Logistics:**

- Shipping Method: The method used to deliver the purchased products.
- Payment Method: The method of payment chosen by the customer.
- Order Status: Status of the order (e.g., shipped, delivered, canceled).
  
This dataset is valuable for retail businesses as it enables detailed analysis of customer preferences, buying habits, demographic trends, and satisfaction levels. Analyzing such data can help companies optimize their marketing strategies, improve customer service, personalize promotions, manage inventory efficiently, and enhance overall customer experience.

In summary, this dataset provides a holistic view of retail operations, from customer demographics and behavior to transactional specifics and feedback, empowering businesses to make data-driven decisions to drive growth and customer loyalty.

The dataset can be found in **Kaggle**: [Retail Transactional Dataset](https://www.kaggle.com/datasets/bhavikjikadara/retail-transactional-dataset)

## Installation

To run the notebook, you will need Python 3.x and the following libraries:

- pandas
- matplotlib
- seaborn
- scikit-learn

You can install these libraries using pip:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/debjit-mandal/retail-transaction-analysis.git
```

2. Navigate to the project directory:

```bash
cd retail-transaction-analysis
```

3. Open the Jupyter notebook:

```bash
jupyter notebook retail_transaction_analysis.ipynb
```


## Analysis Sections

### Customer Demographics Analysis

In this section, we analyze the demographic attributes of the customers, including age distribution, gender distribution, and income distribution.

### Purchasing Patterns Analysis

This section focuses on analyzing the purchasing behavior of customers, such as the total number of purchases and the total amount spent.

### Product Preferences Analysis

Here, we explore the preferences of customers in terms of product categories and brands.

### Feedback Analysis

This section analyzes customer feedback and ratings to understand customer satisfaction levels.

### Transaction Logistics Analysis

This section analyzes the logistics of transactions, including shipping methods, payment methods, and order statuses.

### Correlation Analysis

This section examines the relationships between numerical variables using a correlation matrix.

### Customer Segmentation

This section segments customers based on their purchasing behavior using KMeans clustering.


## Summary

1. **Customer Demographics:**
   - The dataset shows a varied age distribution, with the majority of customers falling within the 20-40 age range.
   - The gender distribution is fairly balanced.
   - Income levels also display a wide range, indicating a diverse customer base.

2. **Purchasing Patterns:**
   - Most customers have made multiple purchases, with some high-frequency buyers.
   - The total amount spent varies significantly, highlighting different spending behaviors.

3. **Product Preferences:**
   - Clothing and electronics are the most popular product categories.
   - Certain brands dominate specific categories, reflecting brand loyalty.

4. **Feedback Analysis:**
   - Customer feedback is generally positive, but there are areas for improvement based on lower ratings.

5. **Transaction Logistics:**
   - Standard shipping is the most common method, followed by same-day delivery.
   - Credit cards are the preferred payment method.

## Conclusion

This comprehensive analysis of the retail transactional dataset reveals valuable insights into customer demographics, purchasing patterns, product preferences, and transactional logistics. Advanced analyses, including correlation and customer segmentation, provide deeper understanding and actionable intelligence for optimizing marketing strategies, enhancing customer experience, and improving operational efficiency.

## Contributing

Feel free to fork this repository and contribute by submitting a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
