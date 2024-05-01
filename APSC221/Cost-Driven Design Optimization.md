---
aliases: 
tags: 
source: "[[(APSC221) Jan Sneep - Economics & Business Practices in Engineering.pdf#page=34&selection=160,0,160,31|(APSC221) Jan Sneep - Economics & Business Practices in Engineering, page 34]]"
source page: 
priority: 
author: "[[Hendrix Gryspeerdt]]"
---
Consideration of the [[Life-Cycle Cost]] ("cradle to grave") for designing products, processes, and services.

Will consider discrete and continuous optimization problems that involve a single design variable X.

X = *primary cost driver* = *design variable*

#### 2 main tasks
1. Determine optimal value for a certain alternative's design variable.
2. Select the best alternative, each with  its own unique value for the design variable.

##### Types of costs
1. [[Fixed Costs]]
2. [[Variable Costs]] *directly* related to design variable
3. [[Variable Costs]] that *indirectly* relate to design variable

##### Simple Cost model
$Cost = aX + \frac{b}{X} + k$

parameters:
- $X$ = design variable in question (e.g., weight or velocity)
- $k$ = fixed costs
- $a$ = *directly* varying costs parameter
- $b$ = *indirectly* varying costs parameter

More general: ![[Pasted image 20240424111742.png]]

##### 5 Step outline
1. Identify the design variable (which is the primary cost driver)
2. Write an expression for the cost model in terms of design variable
3. Set the first derivative of the cost model w.r.t. design variable equal to zero. For discrete variables, consider values over the range of discrete values.
4. Solve equation from step 3 to find optima for continuous design variable. (may have multiple optima, check them for which is best).
5. for continuous variable, take second derivative to check if global max/min.