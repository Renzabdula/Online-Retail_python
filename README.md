Cohort Analysis & RFM analysis with Python using Online Retail Dataset

In this notebook, we aim to learn the following:
  1. Perform simple data cleaning and exploration
  2. Generate and visualize cohorts based on user retention

In this exercise, we are given an online retail dataset containing transactions occurring for a UK-based and registered, non-store online retail between 01/12/2009 and 09/12/2011.The company mainly sells unique all-occasion gift-ware. Many customers of the company are wholesalers.
We are tasked to determine cohorts based on user retention and to provide insights and recommendations to improve customer loyalty.

Our data contains the following columns:

  1. InvoiceNo: Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'C', it indicates a cancellation.
  2. StockCode: Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product.
  3. Description: Product (item) name. Nominal.
  4. Quantity: The quantities of each product (item) per transaction. Numeric.
  5. InvoiceDate: Invoice date and time. Numeric. The day and time when a transaction was generated.
  6. UnitPrice: Unit price. Numeric. Product price per unit in sterling (Â£).
  7. CustomerID: Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer.
  8. Country: Country name. Nominal. The name of the country where a customer resides.
