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



Review of Analysis Presentation Concepts
Biological Analysis

Amplicon Sequencing vs. Whole Genome Sequencing
Amplicon sequencing looks at just one specific part of the genome, like the 16S rRNA gene in bacteria, to get a quick snapshot of which species are present. It’s cheaper and faster, but limited to that one region. Whole genome sequencing gives you everything, the entire genetic blueprint—so you not only know what’s there but also what functions those organisms might have. Amplicon is good for a community overview, while whole genome is for deeper functional and evolutionary questions.

DNA Barcoding
DNA barcoding is basically using a short stretch of DNA as an ID tag to figure out what species you’re looking at. If you find an unknown sample, you sequence that short region and compare it to a reference library to see where it fits. It’s like scanning a product at the store, but for species, and it’s especially helpful in ecology and even in catching mislabeled food.

Diversity Metrics – Alpha vs. Beta Diversity
Alpha diversity tells you how diverse one sample is on its own, for example, how many species are present and how evenly they’re distributed. Beta diversity compares across samples to see how different communities are from each other. Together, these two perspectives help us understand both the richness of a single environment and how much variation exists between environments.

Data Analysis

Extrapolation and Normalization
When we normalize data, we’re putting everything on the same scale so comparisons make sense—for example, adjusting sequencing reads so one sample with more total reads doesn’t unfairly dominate. Extrapolation is when we use the data we have to make a reasonable guess about what’s beyond it, like estimating the number of rare species we didn’t catch in a survey. Both are important tools to deal with real-world datasets that are often messy or incomplete.

Lag Analysis
Lag analysis looks for delayed relationships between variables. For example, if prey numbers go up this year, predator numbers might not increase until the following year, and lag analysis helps us see that connection. It’s especially useful in time series studies where cause and effect don’t line up perfectly in time.

Modeling Concepts

Generalized Mixed Effect Model
A GLMM is what you use when your outcome variable isn’t a simple continuous number—maybe it’s counts, like the number of birds observed, or yes/no data, like whether a species is present. It lets you model those outcomes while still accounting for random effects, like variation between different sites. This makes it really flexible for ecological or health studies where the data aren’t “nice and normal.”

Linear Mixed Effect Model
A linear mixed effect model is used when you have repeated or grouped data that share some structure, like measuring multiple trees within the same forest. It accounts for both the overall trend (the fixed effects) and the differences between groups (the random effects). Without it, you might overstate results because you’d be ignoring that not all observations are independent.

Allometric Scaling Models
Allometric scaling is about how traits change with size—for example, how metabolic rate increases with body mass but not in a straight line. These models often follow a predictable curve or power law, like the famous three-quarters scaling rule. They’re a simple but powerful way of showing that biology has consistent patterns across very different organisms.

Linear vs. Logistic Regression
Linear regression is your go-to when you want to predict a continuous outcome, like height or weight, and it assumes a straight-line relationship with the predictors. Logistic regression comes into play when your outcome is a yes/no type of question, like whether a plant survives or not. It’s less about predicting an exact number and more about predicting probabilities.

Non-linear Regression
Sometimes relationships just aren’t straight lines, it lets you fit curves to data, which is often more realistic for biological systems that plateau, accelerate, or change in unexpected ways. It’s trickier to fit, but it gives a much better picture when linear assumptions don’t hold up.

Random Forests
Random forests are a machine learning method that works by building a whole bunch of decision trees and averaging their results. Think of it like asking a hundred people the same question and taking the majority answer—it smooths out errors and gives a more reliable prediction. They’re especially good for complex datasets and can also show you which variables matter most.

Cross-Validation and Model Accuracy
Cross-validation is basically a way to test how well your model will work on new data. You split your data into training and testing sets, build the model on one, and then see how it does on the other. This helps catch overfitting, where the model memorizes the training data but fails on anything new, and gives you confidence that your results are actually meaningful. 

IC Assignment 6 
This code simulates the population dynamics of a beetle species using an age-structured matrix model. It compares two scenarios: one with no control measures and one where traps remove 5% of second- and third-year beetles each year. The model projects the population for 50 years, tracking each age class and the total population. The results are visualized in a plot, showing how even a small increase in adult mortality from trapping can significantly reduce long-term beetle numbers.

