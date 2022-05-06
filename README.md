# Ridge-regression-model

This model has practical application. The program calculates the goods according to the SKU share of goods for distribution by warehouses (In what quantity and what name should be sent to the distribution warehouse for further distribution to customers).
Principle of operation:
1. Statistical sales data are stored in excel files and have the same form (only the region changes). Therefore, to begin with, we unpack all the files and combine them into one dataset.
2. We do data processing in panadas and numpy to convert it into the required form.
3. Create a Ridge Regression Model
4. Check the accuracy of the data. (model works with 86%-93% accuracy)
