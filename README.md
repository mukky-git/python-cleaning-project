# python-cleaning-project

# Customer Sales Data Cleaning Project

## Description
This project demonstrates data cleaning on a customer sales dataset.  
The dataset initially contained messy data including missing emails, inconsistent dates, duplicate rows, and negative amounts.  
Python (Pandas) was used to clean, standardize, and prepare the data for analysis.

## Dataset Information
- Columns: CustomerID, Name, Email, Date, Amount, Country
- Original number of rows: 310
- Cleaned number of rows: 294

## Cleaning Steps
1. Removed duplicate rows
2. Filled missing emails with placeholders
3. Corrected email format (removed extra @@ and spaces)
4. Standardized Name and Country columns
5. Fixed inconsistent Date formats
6. Handled negative Amounts

## Tools Used
- Python 3
- Pandas

## How to Use
1. Clone the repository:
```bash
git clone https://github.com/mukky-git/Data_Cleaning_Projects.git


| CustomerID | Name          | Email                                                       | Date       | Amount | Country |
| ---------- | ------------- | ----------------------------------------------------------- | ---------- | ------ | ------- |
| 73         | Jennifer Ade  | [jennifer17@gmail.com](mailto:jennifer17@gmail.com)         | 2021-06-26 | 196.06 | Kenya   |
| 151        | Musa Doe      | [musa43@gmail.com](mailto:musa43@gmail.com)                 | 2021-09-28 | 381.38 | Ghana   |
| 85         | Aisha Ali     | [aisha33@company.ng](mailto:aisha33@company.ng)             | 2023-01-04 | 349.69 | Ghana   |
| 26         | Aisha Otto    | [aisha56@yahoo.com](mailto:aisha56@yahoo.com)               | 2023-05-02 | 272.15 | Kenya   |
| 41         | Samuel Smith  | [samuelsmith63@company.ng](mailto:samuelsmith63@company.ng) | 2022-11-07 | 127.35 | Kenya   |
| 158        | Mike Mensah   | [mike24@gmail.com](mailto:mike24@gmail.com)                 | 2022-01-07 | 421.88 | Nigeria |
| 53         | Grace Oladipo | [grace52@hotmail.com](mailto:grace52@hotmail.com)           | 2023-08-14 | 250.85 | Ghana   |
| 175        | Musty John    | [musty43@mail.com](mailto:musty43@mail.com)                 | 2021-04-20 | 370.99 | Ghana   |
| 74         | Peace Khan    | [peace2@hotmail.com](mailto:peace2@hotmail.com)             | 2024-01-28 | 110.87 | Ghana   |
| 127        | John Ali      | [john59@company.ng](mailto:john59@company.ng)               | 2021-06-03 | 458.57 | Ghana   |


