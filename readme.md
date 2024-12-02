## Table name
-autoUsate

## table structure

- ID | BIGINT - AUTO_INCREMENT -PRIMARY_KEY
- brand | VARCHAR(50) NOT NULL
- model | VARCHAR(50) NOT NULL
- price | DECIMAL(10, 2) NOT NULL
- year | YEAR NOT NULL
- mileage | INT NOT NULL
- fuelType | VARCHAR(20) NOT NULL
- color | VARCHAR(20)
- transmission | VARCHAR(20) NOT NULL
- available | DEFAULT (TRUE)
- description | TEXT(500) NULL