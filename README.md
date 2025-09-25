# BIO_350_F25

Starting our BIO350 assignments repo.

IC Assignments 1: Chapter 1 of Ecolodgy Handbook 
 - Making a differnece equation  
 -Technical difficulties, SHOULD be better from now on. 
 -It works now 


 IC Assignment 2: Chapter 2 of Ecology Handbook 
 -Exponential Analysis 
 -Making an exponential equation 

 IC Example 1: Log and conditional elements 
 Turned the graph from assignment 2 into a log using the log fn 
 Talked about if else statements in code
 
 IC Assignment 3: Section 3 Landslide Plant model 
- My code simulates the recolonization of a plant population using a simple discrete-time population model with a fixed mortality rate. Starting with an initial number of plants, the model calculates the number of survivors each year and allows the population to grow, without exceeding the carrying capacity. The simulation continues until the population reaches the carrying capacity, recording the number of plants each year. The results are visualized with a line plot showing population growth over time, and the code outputs the total number of years required for the population to reach its maximum size. This demonstrates basic population dynamics and logistic growth under constant mortality.

IC Example 2: Population Data Analysis

This notebook demonstrates how to import, visualize, and analyze population data using Python and pandas. The workflow includes:
-Importing population data from a CSV file into a pandas DataFrame.
-Plotting the population size over time using matplotlib, with a highlighted reference line at a population size of 276.
-Calculating the average population size between days 17 and 60.
-Displaying the result of the average calculation.
-This example provides a practical introduction to basic data analysis and visualization techniques in Python for ecological data. 

IC Assignment 4: Lotka-Volterra Competition

-This program simulates the Lotka–Volterra competition model, which extends logistic growth to include interactions between two species. Using carrying capacities and competition coefficients, the notebook models how a colonizing plant and a threatened plant compete for space over time. The analysis demonstrates the ecological principle of competitive exclusion, showing that coexistence is only possible when both species compete more strongly with themselves than with each other. 

IC Assignment 5: Rabies Removal: SIR Models 

This code simulates the spread of rabies in a fox population using a simple SIR (Susceptible, Infected, Removed) model with daily time steps. It applies difference equations to update the number of susceptible, infected, and removed foxes over a 30-day period, starting from given initial conditions and parameter values for the infection rate (β) and death rate (d). The program prints the daily results for each class and generates a line plot that illustrates how the epidemic evolves over time, including the peak of infections and the eventual number of deaths.