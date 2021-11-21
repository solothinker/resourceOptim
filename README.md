# resourceOptim
Corona affected different industries. Automobile sector is one of them. It is facing a shortage of chips for vehicle production. Due to that many Chip/IC suppliers are optimizing their resources with maximum benefit.

In my current project, I have tried to implement the **IC distribution optimization** with the help of [PuLP](https://coin-or.github.io/pulp/), Python library for optimization. For this project, I am considering five automobile companies **A**, **B**, **C**, **D** and **E**. With the help of Numpy Random function, a random initial selling price has been generated. These prices have been revised every quarter as well as the minimum and maximum values of IC demand from each automobile company. 

For optimization, the automobile company name has been used as the _Decision Variable_. Selling price and the defined variables has been used to define the _Objective Function_ and min & max IC demands have been used as _Constraints_. After framing the optimization model, it has been used to calculate the IC distribution for each quarter. Needful figures have been drawn to show the results pictorially.

This project helped me to understand about the **Optimization Model Framing**. The selected numbers are completely random but if we could club the right information, we can get to know about the actual Resource (IC/chips) Distribution.  
 
