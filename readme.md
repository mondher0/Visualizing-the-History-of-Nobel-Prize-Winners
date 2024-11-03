# Nobel Prize Data Analysis

## Overview

This project analyzes Nobel Prize data to uncover insights about laureates, including their birth countries, genders, and trends over decades. The analysis highlights significant patterns, such as the most common birth country and gender of laureates, as well as trends related to female winners.

## Dataset

The analysis uses the Nobel Prize dataset, which is expected to be in CSV format and should include the following relevant columns:

- `year`: The year the Nobel Prize was awarded.
- `category`: The category of the Nobel Prize (e.g., Physics, Chemistry, Peace, etc.).
- `prize`: The prize amount awarded.
- `motivation`: The motivation or reason for the award.
- `prize_share`: The share of the prize awarded to each laureate.
- `laureate_id`: The unique identifier for each laureate.
- `laureate_type`: The type of laureate (e.g., individual, organization).
- `full_name`: The name of the Nobel laureate.
- `birth_date`: The birth date of the laureate.
- `birth_city`: The city of birth of the laureate.
- `birth_country`: The country of birth of the laureate.
- `sex`: The gender of the laureate.
- `organization_name`: The name of the organization associated with the laureate (if applicable).
- `organization_city`: The city of the organization.
- `organization_country`: The country of the organization.
- `death_date`: The death date of the laureate (if applicable).
- `death_city`: The city of death of the laureate (if applicable).
- `death_country`: The country of death of the laureate (if applicable).

### Example Data Structure
Here is a sample structure of the dataset:

| year | category  | prize | motivation                   | prize_share | laureate_id | laureate_type | full_name           | birth_date | birth_city | birth_country          | sex    | organization_name | organization_city | organization_country | death_date | death_city | death_country |
|------|-----------|-------|------------------------------|-------------|--------------|----------------|---------------------|------------|------------|------------------------|--------|-------------------|------------------|----------------------|-------------|------------|----------------|
| 1903 | Physics   | 10000 | For her work in radioactivity | 1           | 1            | individual      | Marie Curie         | 1867-11-07 | Warsaw     | Poland                 | Female |                   |                  |                      | 1934-07-04 | Passy      | France         |
| 1921 | Physics   | 20000 | For his services to Theoretical Physics | 1 | 2            | individual      | Albert Einstein      | 1879-03-14 | Ulm       | Germany                | Male   |                   |                  |                      | 1955-04-18 | Princeton  | USA            |
| 1964 | Peace     | 50000 | For his work in civil rights | 1           | 3            | individual      | Martin Luther King Jr.| 1929-01-15 | Atlanta   | USA                    | Male   |                   |                  |                      | 1968-04-04 | Memphis    | USA            |

## Analysis Highlights

1. **Most Common Birth Country of Nobel Laureates**: The analysis identifies the country with the most laureates.
2. **Most Common Gender of Nobel Laureates**: This part examines the gender distribution among laureates.
3. **Decade with the Highest Ratio of US-born Nobel Prize Winners**: The analysis calculates the ratio of US-born laureates over the years.
4. **Decade and Nobel Prize Category with Highest Proportion of Female Laureates**: It finds the combination of decade and category where female winners are most prominent.
5. **First Woman to Receive a Nobel Prize**: Identifies the first female laureate and her category.
6. **Individuals or Organizations Winning Multiple Nobel Prizes**: The analysis lists those who have received more than one Nobel Prize.

## Requirements

To run this analysis, you will need:

- Python (3.x recommended)
- Pandas library
- NumPy library

You can install the required libraries using pip:

```bash
pip install pandas numpy
