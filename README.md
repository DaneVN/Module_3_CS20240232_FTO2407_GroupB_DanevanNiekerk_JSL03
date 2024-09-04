# [JSL03] Project Submission: Which one is which? Declarative or Imperative?!

Loom Recording Link: [(https://www.loom.com/share/167ac84890474d61907bd7e095969042?sid=34382b13-8431-4ea1-9518-51d132ec4f5e)]

# Project Overview

In this project, you will be presented with two JavaScript code examples, each demonstrating a different programming paradigm: imperative and declarative. Your task is to analyse these examples and determine which one follows an imperative programming style and which one follows a declarative programming style. 

You will present your reasoning for each example, record your presentation using Loom, and submit your findings along with the Loom recording to the Project Tab on the Learning Management System (LMS).

# Instructions

## Step 1: Clone the Repository

Repo Link: https://github.com/CodeSpace-Academy/Module_3_StudentNo_Classcode_Group_Name-Surname_JSL03

1. Access the provided repository containing the starter code and presentation template.
2. Clone the repository.
3. Open the cloned repository in your preferred code editor.

## Step 2: Analyze the Examples

1. In the cloned repository, you will find two JavaScript code examples labeled "Example 1" and "Example 2."
2. Examine each code example and determine which one follows an imperative programming style and which one follows a declarative programming style.

## Step 3: Record Your Presentation

1. Use Loom (https://www.loom.com/).
2. Create a single video presentation for both examples that include the following:

   - Introduction of the example number.
   - Explanation of whether the example is imperative or declarative.
   - Detailed reasoning for your choice, discussing the code logic and style used in the example.
   - Mention any specific code structures or patterns that align with the chosen programming paradigm.
   
3. Keep each video presentation concise, with a maximum length of 2 minutes for each example. Your total recording time should not exceed 5 minutes.

## Step 4: Insert Loom Links

1. After recording, upload your presentation videos to Loom.
2. Obtain the Loom recording links for the video presentation.
3. Edit the `README.md` file in the cloned repository and insert the Loom recording links.
   
## Step 5: Submit Your Project
1. Commit your changes to the Git repository and push them to your GitHub account.
2. Ensure that the repository is public so that it can be accessed.
3. Submit the GitHub project link (URL) that includes your Loom recording link to the [JSL03] Project Tab on the LMS for evaluation.

# Project Evaluation

Your project will be evaluated based on your ability to:

- Accurately identify and differentiate between imperative and declarative programming styles.
- Provide clear and well-reasoned explanations for your choices.
- Present your findings concisely within the specified time limit.
- Follow the submission instructions accurately.

Follow the steps outlined above to complete the project successfully.

# Presentation Talking Points

Example 1:

## Imperative Approach [2 Minutes]
1. **Step-by-Step Explanation:** Start by explaining the code logic in the imperative approach.
   - Mention each step of the process in the code.
   - Describe how the code provides explicit instructions for each action.
   - Discuss the use of variables to track the state and progress of the process.

2. **Emphasis on How:** Highlight how the imperative approach focuses on detailing "how" the task is accomplished.
   - Point out the use of loops, conditions, and explicit instructions.
   - Discuss any mutable variables or states that change during execution.


Example 2:

## Declarative Approach [2 Minutes]
1. **High-Level Process Description:** Explain the code logic in the declarative approach.
   - Describe the cooking process in a high-level, abstract manner.
   - Emphasize that the code defines "what" should happen rather than "how" it should happen.

2. **Use of Data Structures:** Discuss the use of data structures (e.g., arrays, objects) to represent the process steps.
   - Explain how the process steps are organized in a structured format.
   - Mention any abstraction layers or functions used to encapsulate actions.

# Learning Outcome [1 Minute]
- Reflect on what you've learned from analyzing these code examples in different paradigms.

## SCRIPT
Hello I’m dane and ill be taking you through a paradigm discussion :
   To start off, Example 1: The Imperative Approach
   1. Start by explaining the code logic in the imperative approach.
   The program follows these steps: 
     - Set Grill Temp + initialise Seasoning var values
     - While the steak isn't at desired temp carry out these steps as seen here
     - If steak is desired temp return the ‘ready’ message else return this message
     - After all that call the function with the parameters and print the result.

   Because of the nature of Imperative paradigm programming, all the steps are very specifically defined and are executed in the order they are written.

   Variables like steakTemp and desiredDoneness are responsible for tracking the progress of the process (so fun to say) meaning they are indicators of conditions met and they are needed for the program to be able to continue to the next step in the code.

   2. Highlight how the imperative approach focuses on detailing "how" the task is accomplished.
     - the Conditionals as seen here: loops, conditions, and explicit instruction in pseudo code. controls the flow of the code explicitly
   Another characteristic of imperative paradigms is its mutable data, e.g of this are
     - grillTemp value being reassigned when the grill is 'preheating'
     - steakTemp increases as it is 'exposed' to grillTemp(updating with every while loop completed) Which is what will eventually get the program flow to continue as mentioned before with the progress of  the process
 
    - Moving on to Example 2: the Declarative approach.
   1.  Explain the code logic in the declarative approach.
   The code logic is a as follows:
    - the cooking process is declared in the array as objects. As the program encounters these instructions, it executes them  (preheating, seasoning, cooking and printing results)
   A characteristic of Declarative paradigms are that it allows you to describe what needs to happen without specifying the details of how it should happen.
   - Each object in the cookingProcess array summarises a specific step in the cooking process. Instead of directly writing out the code to perform each action, the actions are represented as abstract descriptions
   2. Discuss the use of data structures (e.g., arrays, objects) to represent the process steps.
   The step organization is in a structured format because
    - The array holds items that act as the actions taken in the cooking process. The array is then iterated in the order that the items are arranged. Each action has a case statement and the default if all else fails is to claim ‘invalid step’ therefore, it covers all bases without constricting flow
    - Abstraction layers I found are: the cookingProcess array abstracts the sequence of steps, each object abstracts individual actions, and the function cookSteak abstract the execution logic. This layered abstraction makes the code more modular, readable, and easier to maintain.


    - So, lets Reflect on what was analyzed 
   Imperative Programming involves explicitly defining each step, using loops, conditionals, and variables that change state throughout the process. The code is step-by-step and procedural, with a clear flow of control that dictates exactly how the task should be executed.
   Declarative Programming, on the other hand, abstracts away the details, allowing you to describe the desired outcome without specifying the exact steps to get there. Data structures like arrays and objects represent actions or states, and the execution logic is often handled by underlying functions or systems, making the code more modular, readable, and easier to maintain.
   In short, imperative code tells the computer how to do something, while declarative code tells the computer what to do
   Thanks for watching! Good bye
