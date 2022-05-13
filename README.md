# Explanation of the projects
## classification project
In this project, we try to improve the advertising for every customer who comes to the mall with KNN & LogisticRegression models, for which we divided the consumers into 3 groups: 0,1,2.

..* Group 0 - This is a group of consumers who do not buy much in the first place, so we will not invest in advertising for it.
..* Group 1 - This is a group that buys in the mall at an average ratio to other customers, so for example, for them we will publish a club card, so we will make them buy from us in the mall more than than elsewhere and so we will make them more loyal customers.
..* Group 2 - This is the group of customers who are loyal to the mall in the first place and buy a lot. Therefore for this group we can, for example, advertise 1 + 1 promotions for them. Since they are loyal customers anyway with the help of this sale we can make them buy even more at the mall (they were looking to buy a certain product but saw that there is a 1 + 1 sale on another product and will buy it as well).
The division into groups is as follows
The mall gave a score to each consumer for how much he buys in the mall (Column - Spending Score (1-100)). Therefore, with the help of this column, we divided the consumers into three groups:

..* 0 - This is the group that got the score 0-33.
..* 1 - This is the group that received a score of 33-66.
..* 2 - This is the group that received the score 66-100

## regression project - 
In this project the goal is to find out what the price of a second hand car is with LinearRegression model based on numbers of features, such as:
..* model - Audi vehicle type
..* year - registration year
..* price - price in euros
..* transmission - type of gearbox
..* mileage - how much miles the car has already driven
..* fuelType - engine fuel
..* tax - road tax
..* mpg - miles per gallon
..* engineSize - size in litres
