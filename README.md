# [JSL03] Project Submission: Which one is which? Declarative or Imperative?!

Loom Recording Link: [Insert Link]

# Project Overview

In this project, you will be presented with two JavaScript code examples, each demonstrating a different programming paradigm: imperative and declarative. Your task is to analyse these examples and determine which one follows an imperative programming style and which one follows a declarative programming style. 

You will present your reasoning for each example, record your presentation using Loom, and submit your findings along with the Loom recording to the Project Tab on the Learning Management System (LMS).


# Presentation Talking Points

Example #: 1

## Imperative Approach [2 Minutes]
1. **Step-by-Step Explanation:** 
This function cooks a steak to the user's preferred level of doneness. It alerts the user if the steak is ready or if it still needs to be cooked. 
   
   - Each step of the process:
   The function cookSteak() has two parameters (steakWeight, and desiredDoneness). Both parameters should be numerical values. It outlines the following step-by-step instructions on how to get the steak to its desired level of doneness: 

    Step 1: Preheat the grill <br>
    Step 2: Season the steak <br>
    Step 3: Cook the steak <br>
    Step 4: Serve the steak <br>
    
   - Describe how the code provides explicit instructions for each action.
    1. The "grill is preheated": the grillTemp variable is increased from 0 to 204.
    2. The steak is "seasoned": the variable seasoning contains the seasonings that should be applied to both sides of steak.  
    3. The steak is "cooked": A "while" loop is used to tell the computer to keep checking the steak's temp and adjust the grill temp while its internal temp is below the desired level. During this time a message saying, "Steak needs more cooking" will be displayed.
    4. Once the steak's internal temp has reached the desired level, the message "Steak is ready to serve" will be displayed and the steak will be served.  

   - The use of variables to track the state and progress of the process.
   There's 2 main variables tracking the state and progress of the process: grillTemperature and steakTemperature. 
   While the code is being executed, the values of these 2 variables will be increased periodically. As the grillTemperature's variable increases, so should the steakTemperature variable increase. 
   The process is completed when the grillTemperature is >= the pre-set level of doneness. 


2. **Emphasis on How:** How the imperative approach focuses on detailing "how" the task is accomplished.
   - This is an example of imperative programming because it uses a while loop, a conditional statement, and clear step-by-step instructions on how the code should be executed.  
   - The 2 main variables (steakTemperature and grillTemperature) are mutable and their states change during the execution of the code. 
   


Example #: 2

## Declarative Approach [2 Minutes]
1. **High-Level Process Description:** 
   - This function shows that we want to cook a steak to a desired level of doneness and it must be seasoned with salt and pepper. 
   - The function does not include step-by-step instructions on how the steak should be cooked. It basically gives requirements of what should  be done in order to cook the steak.  
   
2. **Use of Data Structures:** Discuss the use of data structures (e.g., arrays, objects) to represent the process steps.
    The cooking steps are placed inside an array. Each step (item in the array) is an object with different instructions and variables attached to that part of the cooking process.

    e.g. Seasoning the steak is an action and it is related to the grillTemperature. 

    As the for loop is executed, it will iterate over each action object in the cookingProcess array. The loop will then console log the appropriate messages depending on which phase of the process we are on. 

# Learning Outcome [1 Minute]
- I realised that we mostly learned how to code in line with the imperative programming paradigm. 
