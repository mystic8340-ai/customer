# Customer Analytics Dashboard

This repository contains a Power BI report and the CSV files for an Olist
Brazilian e-commerce dataset. Open the report in Power BI Desktop to explore the
customer and order data.

## Repository contents

- `Powerbi file/cust.pbix` — Power BI report.
- `Dataset/olist_customers_dataset.csv` — customer IDs, location prefixes, and
  city/state.
- `Dataset/olist_orders_dataset.csv` — order status and order/delivery dates.
- `Dataset/olist_order_items_dataset.csv` — products, sellers, prices, and
  freight values per order item.
- `Dataset/olist_order_payments_dataset.csv` — payment methods, installments,
  and payment values.
- `Dataset/olist_order_reviews_dataset.csv` — review scores, comments, and
  review dates.
- `Dataset/olist_products_dataset.csv` — product categories, dimensions, and
  descriptive fields.

## Requirements

- Power BI Desktop (Windows) to open and interact with the `.pbix` report.
- The CSV files included in `Dataset/` to refresh the report's data.

No Python or package-installation requirements are needed to open the report.

## Getting started

1. Clone or download this repository.
2. Open `Powerbi file/cust.pbix` in Power BI Desktop.
3. If Power BI prompts for unavailable source paths, use **Transform data** >
   **Data source settings** to point the report to the matching CSV files in
   `Dataset/`.
4. Refresh the report.

The report's original data-source paths may be specific to the machine on which
it was created.

## Data source

The CSV names and schema correspond to the Olist Brazilian E-Commerce public
dataset, available on
[Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). Refer to
the dataset page for its description and terms of use.
