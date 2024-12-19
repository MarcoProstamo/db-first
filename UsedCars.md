# Used Cars

### Context:

Data Table for the single car.

| name                | type          | null | default | attribute               | key     | note                                                                            |
| ------------------- | ------------- | ---- | ------- | ----------------------- | ------- | ------------------------------------------------------------------------------- |
| id                  | BIGINT(20)    | no   | none    | UNIQUE - AUTO-INCREMENT | PRIMARY | Unique identifier for each car record                                           |
| vin                 | CHAR(17)      | no   | none    | UNIQUE                  |         | Vehicle Identification Number, a globally unique identifier for the car         |
| original_color      | CHAR(35)      | no   | none    |                         |         | The color of the car as it was originally painted by the manufacturer           |
| car_manufacturer    | VARCHAR(100)  | no   | none    |                         |         | Name of the car's manufacturer (e.g., Honda, Mercedes-Benz)                     |
| kilometer_count     | BIGINT(20)    | no   | none    |                         |         | Total kilometers driven by the car, reflecting its mileage                      |
| fuel_type           | CHAR(1)       | no   | none    |                         |         | Fuel type: P = Petrol, D = Diesel, E = Electric, H = Hybrid, G = Gas, O = Other |
| model_name          | VARCHAR(100)  | no   | none    |                         |         | Specific model of the car (e.g., Civic, Corolla)                                |
| year_of_manufacture | YEAR          | no   | none    |                         |         | Year the car was manufactured (e.g., 2020)                                      |
| registration_state  | VARCHAR(50)   | no   | none    |                         |         | State or region where the car is registered                                     |
| price               | DECIMAL(10,2) | no   | none    |                         |         | Selling price of the car in local currency                                      |
