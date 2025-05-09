# THE-FAMOUS-CHOCOLATE-PROBLEM-SHOPKEEPER-PROBLEM-
//"100 chocolates for ₹100" problem, which is a variation of the famous "Hundred Chickens" or "Hundred Horses" type problems.

//Problem Statement (Implied by the Code)
//Buy exactly 100 chocolates for exactly ₹100, where:

//Each chocolate of type A costs ₹3.

/*Each chocolate of type B costs ₹0.5.

Each chocolate of type C costs ₹10.

Find all possible combinations of quantities of these three types of chocolates (x, y, z) such that:

The total number of chocolates is 100:
𝑥
+
𝑦
+
𝑧
=
100
x+y+z=100

The total cost is ₹100:
3
𝑥
+
0.5
𝑦
+
10
𝑧
=
100
3x+0.5y+10z=100

The nested loop tries all integer combinations of x and y from 0 to 100, calculates z = 100 - x - y, and checks if the total cost is ₹100.*/
