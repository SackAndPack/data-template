# Data Dictionary

This document describes the structure and content of the dataset used in this project.

## Dataset: `sample_data.csv`

| **Column Name**    | **Data Type** | **Description**                              | **Example Value**         |
|---------------------|---------------|----------------------------------------------|---------------------------|
| `id`               | Integer       | Unique identifier for each record.           | `101`                     |
| `name`             | String        | Name of the individual or entity.            | `John Doe`                |
| `age`              | Integer       | Age of the individual in years.              | `34`                      |
| `gender`           | String        | Gender of the individual.                    | `Male`, `Female`          |
| `income`           | Float         | Annual income in USD.                        | `54000.50`                |
| `purchase_date`    | Date          | Date of the last purchase (YYYY-MM-DD).      | `2023-10-12`              |
| `product_category` | String        | Category of the purchased product.           | `Electronics`             |

---

## Sample Data

Below is an example of how the data might look:

| id  | name       | age | gender | income   | purchase_date | product_category |
|-----|------------|-----|--------|----------|---------------|------------------|
| 101 | John Doe   | 34  | Male   | 54000.50 | 2023-10-12    | Electronics      |
| 102 | Jane Smith | 28  | Female | 62000.00 | 2023-11-01    | Home Appliances  |
| 103 | Bob Brown  | 45  | Male   | 45000.00 | 2023-09-15    | Furniture        |

---

## Notes
- Missing values in `income` should be replaced with `NULL` or interpolated.
- Dates are formatted as `YYYY-MM-DD` to ensure consistency.
- `product_category` is a categorical variable with predefined values (e.g., Electronics, Furniture, etc.).

---

This ensures the data dictionary:
1. **Is easy to find**: Located in the `docs/` folder and referenced in the main `README.md`.
2. **Describes useful columns**: Includes column names, data types, descriptions, and example values.
3. **Includes sample data**: Provides a small snippet of what the dataset looks like.
