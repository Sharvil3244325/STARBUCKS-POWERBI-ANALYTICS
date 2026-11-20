# Starbucks Beverage Analytics Dashboard

An interactive Power BI dashboard for exploring Starbucks beverage
nutrition, category characteristics, and store locations.

The dashboard brings together beverage-level nutritional measures and
category comparisons to help users explore the Starbucks beverage
portfolio.

## Dashboard Preview

![Starbucks Beverage Analytics
Dashboard](Screenshots/dashboard_preview.png)

## Business Objectives

-   Summarise the beverage portfolio using key nutritional measures.
-   Compare average calories across beverage categories.
-   Explore sugar, protein, and dietary fibre measures.
-   Identify beverages with the highest calorie values.
-   Examine beverage category distribution.
-   Explore the geographical distribution of Starbucks stores.

## Tools and Technologies

  Tool               Purpose
  ------------------ -----------------------------------------------
  Power BI Desktop   Dashboard development and data visualisation
  DAX                Measures and KPI calculations
  Power Query        Data preparation and transformation
  Map visual         Geographical visualisation of store locations

## Dashboard Components

### Executive Summary

The dashboard includes summary measures such as: - Total beverages -
Average sugar - Average calories - Average protein - Average dietary
fibre

### Nutritional Analysis

-   Average calories by beverage category
-   Nutritional comparisons across beverage categories
-   Protein and dietary fibre summary measures

### Product and Category Analysis

-   Beverage category distribution
-   Top five highest-calorie beverages
-   Average calorie comparisons by category

### Geographical Analysis

-   Map visual showing Starbucks store locations using the geographical
    fields available in the dataset.

### Interactive Filtering

The report includes filters for exploring beverage characteristics,
including protein range and beverage preparation type, where configured
in the report.

## Business Questions

1.  Which beverage categories have the highest average calorie content?
2.  Which beverages have the highest calorie values?
3.  How does sugar content vary across the beverage portfolio?
4.  What are the average protein and dietary fibre values?
5.  How are Starbucks store locations distributed geographically?
6.  How can users explore beverages using nutritional and
    preparation-related filters?

## Business Value

The dashboard provides a consolidated view of beverage nutrition and
category characteristics. It can support: - Comparison of nutritional
values across beverages. - Exploration of products with relatively high
calorie or sugar values. - Review of nutritional differences between
beverage categories. - Geographical exploration of store locations.

## Repository Structure

``` text
Starbucks-Beverage-Analytics/
│
├── Dashboard/
│   └── Starbucks_Dashboard.pbix
│
├── Dataset/
│   └── Starbucks.csv
│
├── Screenshots/
│   └── dashboard_preview.png
│
└── README.md
```

Update the example filenames above to match the actual filenames in the
repository.

## How to Use

1.  Download or clone this repository.
2.  Install Microsoft Power BI Desktop.
3.  Open the `.pbix` file in the `Dashboard` folder.
4.  If Power BI requests a data source location, update it to the
    location of the dataset.
5.  Refresh the data if required.
6.  Use the report filters and visuals to explore the dashboard.

## Data Notes and Limitations

-   Nutritional values reflect the source dataset and may vary by
    serving size, product version, or preparation.
-   Geographical analysis depends on the location fields available in
    the dataset.
-   The dashboard describes the data provided; it does not establish
    customer preferences, sales performance, or purchasing behaviour
    unless those measures are separately supported by the source data.

## Author

**Sharvil Khaire**

Data Analytics \| Business Intelligence \| SQL \| Python \| Power BI
