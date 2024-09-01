# Aggregation-Java
Nested method from different class within a method of distinct class 
This demonstrates how we can conduct aggregation in java through the sample given. 
We know that in order to calculate the area of circle we need to do as follow :
1. get the value of squared radius of circle.
2. multiply the squared radius of circle by pi.

In order to integrate the method of calculating the area of a circle within one method (since it only takes 1 parameter : int radius ) , hence we can first create an outer class and then create a main class containing the method to declare your " area " method. The method from the outer class that compute for the squared radius will be reused in a way to minimize code in the main class. 
Therefore, not only you can reuse your code, you can maintain your code script more easily as it was systematically organized and sorted.
