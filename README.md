# Cars Twenty Four :blue_car: :moneybag:

## Problem Statement

predicting the **prices** of used cars across the country.

## About The Dataset
| # | Feature | Description |
|:--|:-------:|:-----------:|
|1|Name| The brand and model of the car.|
|2|Location| The location in which the car is being sold or is available for purchase.|
|3|Year| The year or edition of the model.|
|4|Kilometers_Driven| The total kilometres driven in the car by the previous owner(s) in KM.|
|5|Fuel_Type| The type of fuel used by the car.|
|6|Transmission| The type of transmission used by the car.|
|7|Owner_Type| Whether the ownership is Firsthand, Second hand or other.|
|8|Mileage| The standard mileage offered by the car company in kmpl or km/kg|
|9|Engine| The displacement volume of the engine in cc.|
|10|Power| The maximum power of the engine in bhp.|
|11|Seats| The number of seats in the car.|
|12|New_Price| The price of a new car of the same model.|
|13|Price| The price of the used car in INR Lakhs.|

## Prepairing Dataset For Analysis
| # | Feature | Coorections or Manipulations |
|:--|:-------:|:-----------:|
|1|Name|Name contained the model of the car and the brand name. I created a new feature __Brand__ extracting the brand name.Spelling errors were corrected.|
|2|Location| _*Nothing changed*_|
|3|Year| _*Nothing changed*_|
|4|Kilometers_Driven| _*Nothing changed*_|
|5|Fuel_Type|Col renamed.|
|6|Transmission| _*Nothing changed*_|
|7|Owner_Type|Col renamed|
|8|Mileage|Units were removed. Dtype changed to __float__|
|9|Engine|Units were removed. Dtype changed to __int__|
|10|Power|Units were removed. Dtype changed to __float__|
|11|Seats|Missing value for one car was searched and rewritten.|
|12|New_Price|The col was removed for lots of missing values.|
|13|Price| _*Nothing changed*_|

Apart from these, cars with missing values for ['Engine', 'Mileage', 'Power', 'Seats'] were removed.

:weary: :weary: :weary: