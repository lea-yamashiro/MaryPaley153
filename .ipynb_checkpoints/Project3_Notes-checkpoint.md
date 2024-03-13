# Project 3: Food Demand

## Motivation & Overview 

This project is about individual people's **CHOICES**, in particular: 
- what food to eat
- how *much* food to eat

Choices always vary, as humans often behave stochastically, and generally are influenced by infinite factors. Sometimes choices can lead to inexpensive, nutritious diets, but not always. 

In examining demand, we focus on the relationship between **diet, budget,** and **prices**. The overall goal of the project is to be able to give a clear characterization of this relationship for some particular real-world population of interest.

Further notes: 
It's a difficult project, a real economist's problem. We don't have utility functions for every food we can think of. 
So, we're trying to do an optimization – to produce a description of the utility that people derive from food, and THEN: get demand functions that we can recreate out of utility functions, once we have them. 
We want to think about supply, demand, (focus here is on demand), and a *little* bit of welfare. 

## Data Requirements

One of the biggest challenges of this project is finding adequate data. Conceptually, the data we'll work with includes: 
- detailed data on food consumption (or expenditures)
- data on household or individual characteristics that may influence demand, e.g: 
    - household size
    - population composition
        - households with young families are going to be quite different than ones with old people
- Food conversion table, which allows us to map quantities of food into nutritional outcomes
    - we're not going to be using RDIs, but will be doing a different type of analysis with the nutrients, so might not be using the same dataframe generation style as in Project 2. 

## Deliverables 

### A Deliverables

**[A.1] Choice of population with associated expenditure data** 
- Probably most important decision we make
- Lots of different populations that are interesting, but only a few populations have data that can support a careful demand analysis.
- We want to try to capture the variation of expenditures ACROSS populations. 
- Ligon will provide some "curated" datasets that we can use, but we're welcome to find our own
We'll be using data from the WORLD BANK!!
- there's a massive amount of Living Standards Measurement Surveys that the WB does, that we can use and work with

**[A.2] Estimate Demand System**
- Estimate a system of demands for different kinds of food
- Characterize how consumption varies with household need
- Can draw inferences into how changes in household composition influences demand
** MAIN POINT: How do households, depending on composition, value food?**

**[A.3] Presentation**
Self-explanatory, same as Projects 1 and 2.

### B Deliverables

**[B.1] Nutritional content of different foods (table)** 
For all foods we're considering, (for food conversion table discussed before) need to: 
- describe their nutritional content of food
- describe nutritional in terms that allow us to compare with recommended daily allowances
- Note: they'll provide pointers to US Govt. recommendations, but many countries have their own recommendations, which might be better suited to their populations.
- indexed by food, columns by type of nutrient, like in Project 2
    - except, it needs to be adjusted for the given population... 

**[B.2] Nutritional adequacy of diet** 
Given the food actually consumed in the data, **this** is where we use the RDIs, like in project 2
- what can you say about the adequacy of the diets in the population of interest?
- what proportion of households consume enough so that members will exceed or meet dietary recommendations?
- what proportion do not meet these recommendations?


### C Deliverables

**[C.1] Counterfactual Experiments**
Once we have our demand system, we can do counterfactual experiments. 
The populations we have data on consumed the given foods with given income levels and household consumption. 
If everyone's total food expenditures doubled (holding prices fixed): 
- how would this affect nutrition in the population?
- what if relative food prices changed?
- think of other counterfactual experiments that might be interesting.
Doing the work necessary to describe a whole bunch of demand curves that might be related to questions having to do with policy (this is the big payoff, when trying to think about the "usefulness of Economics" in influencing basic needs in our society). 






