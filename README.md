# SQLpath_Algo

> This repo is meant to be for easily inspecting the back-end algo and database of the 'Vice City Metro Rail' project. Original Files are at https://github.com/mr-loop-1/ViceCity-MetroProject & https://github.com/mr-loop-1/projektDBMS. 

**This is my path algorithm in MySQL and it's tailor-made for a 'specific' kind of map.**

### Instructions
1. Create a database using the database.sql file
2. Run all the code in algo.sql file in the same database to create the procedures.
3. From the map, take any two stations A and B,
              
              CALL insertMain(A, B)
4. The path is stored in `stack_Compare` table
              
              SELECT * FROM stack_Compare

The route map which made the basis of the algorithm is shown below and the same is used for designing the database.

![map](https://user-images.githubusercontent.com/92433908/148652055-23a37e70-3713-4932-941d-d31d4bd1835e.jpg)
