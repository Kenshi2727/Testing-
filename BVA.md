Question 1:

18-99  | n-m

Boundaries-

   17 | 98
   18 | 99
   19 | 100

Test cases: 17,18,19,98,99,100




Question 2:

60-100 | n-m

   Eq. class => 60<=marks<=100

Valid values--> 60,70,80,90,100




Question 3:

age  | Eq. Class |  pay

<=25  | Class 1   | 15000
26-39 | Class 2   | 15000
40-64 | Class 3   | 16500
<=65  | Class 4   | 17325

4 equivalence classes.





Question 4:

Age < 8 -> Eligible
Age > 35 and < 45 -> Eligible
Age > 60 -> Eligible

Equivalence Classes:

Age < 8 -> Valid
8 <= Age <= 35 -> Invalid
35 < Age < 45 -> Valid
45 <= Age <= 60 -> Invalid
Age > 60 -> Valid

===>5 equivalence classes




Question 5:


Conditions:
Min order quantity = 5
20% discount for quantity >= 100

Equivalence Classes:
Quantity < 5 -> Invalid
5 <= Quantity < 100 -> Valid, no discount
Quantity >= 100 -> Valid, 20% discount

Boundary Value Analysis:
4 -> Just below minimum
5 -> Minimum
6 -> Just above minimum
99 -> Just below discount boundary
100 -> Discount boundary
101 -> Just above discount boundary

Answer: 4, 5, 6, 99, 100, 101




Question 6:


Conditions:
Service < 2 years -> 0% bonus
2 < Service < 5 years -> 10% bonus
5 <= Service < 10 years -> 25% bonus
Service >= 10 years -> 35% bonus
Service < 0 -> Invalid

Equivalence Partitions:
Service < 0 -> Invalid
0 <= Service < 2 -> 0% bonus
2 <  Service < 5 -> 10% bonus
5 <= Service < 10 -> 25% bonus
Service >= 10 -> 35% bonus

Answer: 5 equivalence partitions




           