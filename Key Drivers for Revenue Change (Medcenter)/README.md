# Exploring key drivers of change of revenue in a Medical Center Project #


## Aim of the project ##

The main goal of the project is to define the __key drivers of change of the revenue__ of the center in 2022 compared to 2021.

## Tasks of the project ##

- To examine to what extent the revenue changed from 2021 to 2022;
- To find out what impacted more - changes in price or changes in clients' behavior;
- To explore deeper the influence of the both factors mentioned above:
    - price (with a breakdown into categories and subcategories of services);
    - clients (age, gender, demand for certain services)

## Content ##

1) Basic analysis
2) Data preparation
3) Exploratory data analysis
4) Check of the influence of different factors on revenue change in 2022, such as:
    - change in clients flow;
    - age and gender;
    - either services are connected with import or not
5) Summary

## Libraries used: ##

- Pandas
- Matplotlib
- Seaborn
- SciPy
- Math

## Data ##

- `record_id` - unique data row ID;
- `service_date` - date of providing the service;
- `service_name` - name of the service provided;
- `service_number` - number of the services provided;
- `service_amount` - paid for the service provided, rubles;
- `insured` - unique patient ID;
- `sex_id` - sex (1 - male, 2 - female);
- `age_for_service_date` - age on the date of providing the service.