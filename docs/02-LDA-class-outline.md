#LDA basics

## Motivation, terms, concepts 
### Why longtiduinal? 

At least 5 reasons:

1. Identification of intraindiviaul change (and stability). Do you increase or decrease with time or age. Is this pattern monotonic? Should this best be conceptualized as a stable process or something that is more dynamic? On average how do people change? 

2. Inter-individual differences in intraindividual change. Does everyone change the same? Do some people start higher but change less? Do some increase while some decrease? 

3. Examine joint relationship among intraindividual change for two or more constructs. If variable X goes up does variable Y also go up across time? Does this always happen or only during certain times? Is this assocaition due to a third variable or does it mean that change occurs for similar reasons?  

4. Determinants of intraindividual change. What are the repeated experiences that can push construct X around. Do these have similar effects at all times? 

5. Determinants of interindividual differences in intraindividual change. Do events, background characteristics, interventions or other between person characteristic shape why certain people change while others don't? 

### Types of change

There are many ways to think of change and stability. We will only have time to go into a few of these types, but it is helpful to think about what type you are interested in when you plan a project or sit down to analyze data. 

1. Differential / rank order consitency/ rank order stability

2. Mean level/ absolute change

3. Individual differences in change

4. Ipsative Change

5. Heterotypic change


### Between person versus within person

Or in other words these are the shortened version of interindividaul differences in change versus intraindividaul differences. Refers to across people versus within a particular person. Often we are interested in both simultaneously. 

Related to Fixed effects and Random effects. 


### Trajectories, curves, change, growth... oh my

How do we refer to 'change'? Usually it is easier to refer to pictorially or in terms of an equation. Putting a word onto it usually causes some confusion, which is why there are a lot of redundent terms in the literature. All of these might refer to the same thing when used within a model. However, the names of some models use these terms differently and thus can refer to different models or conditions that you are working with. In this class I will try to point out the important differences but you will be fine if you supplement your terms with graphs or equations.

## Data structures and data analysis

### MLM & SEM
In this class (and in the field) two primary techniques are used with longitudinal models: MLM and SEM. At some levels they are completely equivalent. At others, one is better than the other and vice versa. 

MLM/HLM is a simple extension of regression. As a result it is easy to interpret and impliment. In terms of longituduinal data it is easier to run models when the time of measurement differs from person to person. For this class we will use lme4 as our MLM program but there are many others we could use e.g., nlme. 

SEM is related to regression in that regression is a subset of SEM techniques. In other words, an SEM program could run a simple regression analysis. 

### Wide and Long form


```r
library(tidyr)
```


## Graphing


```r
library(ggplot2)
```







