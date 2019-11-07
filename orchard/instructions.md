# Modelling a fruit orchard

To practice our programming, we're going to build basic program that models a fruit orchard.  First, clone this repository using GitHub. Next, create a new NetBeans project inside your newly cloned folder. Call your new project **Orchard**. Finally, create classes inside your new project to satisfy these instructions.

Make frequent commits and push your assignment to GitHub when you've finished. 

## Fruit
- Create an abstract class called Fruit
  - Give it a final double instance variable weight and a boolean instance variable ripe
  - Create an abstract class called FruitTree.
- Give it a double instance variable height and an integer variable age.
  - Give it a constructor that accepts a starting height and sets age to 0
  - Give it an abstract method bearFruit() that returns an array of Fruit objects
  - Give it another method passSeason() that returns void and increases the age by 1.
  
## Apple
- Create a class called Apple
  - Set its default weight to 0.20 and ripe to false
  
## Apple Tree
- Create a class called AppleTree.
  - Initialize its height to 2.5
  - Set its bearFruit() to return an array of apple objects.
    - If its age is less than 3, it returns an empty array
    - If its age is between 3 and 10 it returns 8 apples
    - If it’s older than 10, return an empty array
  - Override the super class's passSeason() method to increase age by 1 and grow the tree by 1.5
  
## Orange
- Create a class called Orange
  - Set its default weight to 0.30 and ripe to false
  
## Orange Tree
- Create a class called OrangeTree.
  - Initialize its height to 4.0
  - Set its bearFruit() to return an array of orange objects.
    - If its age is less than 5, it returns an empty array
    - If its age is between 5 and 15 it returns 12 oranges.
