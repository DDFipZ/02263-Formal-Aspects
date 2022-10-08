# 02263 Formal Aspects MA1
This is where we write stuff about the project
## 2.1 Requirements
### ColouringBasics
What is the purpose of the below functions


- IsRelation
  - Is the wellformed function that checks if the neighboorhood relation value is correct.
  - Looking at two parameters
    - A piece cannot be neighboor to itself
    - A neighboor relation cannot appear twice, even if its constructed reversed
- areNb
  - Checks if two pieces are neighboors by looking at the relation value.
  - Compares the pieces to the relations and if they are in it, then they are a neighbor
- isCorrectColouring
  - Compares the relations value with the colouring value in order to make sure that the colouring is correct
  - Takes each colour set and checks if all the pieces in each set are __not__ neighboors with eachother. If that is true, then they are coloured correctly

