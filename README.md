# Cars-Dataset
## Cars Dataset - Visualization¶
![ford-mustang-stallion-red-57409](https://user-images.githubusercontent.com/60848308/123320045-a1bdf400-d507-11eb-9a8c-874fbc9aa70b.jpeg)

The period between 1970 and 1982 marked a significant shift in the United States car industry. American production shifted from heavy, powerful six and eight-cylinder cars with poor gas mileage to lighter, less powerful, four-cylinder cars with higher fuel efficiency.

The global auto industry, including Americans and their European and Japanese competitors, raised overall miles per gallon (MPG) by focusing on four-cylinder cars and making them more fuel-efficient.

The dataset contains 398 unique cars along with their respective specification, origin country, and model year.

This dataset was taken from the StatLib library which is maintained at Carnegie Mellon University. The dataset was used in the 1983 American Statistical Association Exposition.

Dataset: https://data.world/dataman-udit/cars-data (cars_multi)

Attributes:

- id: string (Unique values - PK)
- mpg: continuous
- cylinders: multi-valued discrete
- displacement: continuous
- horsepower: continuous
- weight: continuous
- acceleration: continuous
- model: multi-valued discrete
- origin: multi-valued discrete (FK)
- car name: string (Unique values)

