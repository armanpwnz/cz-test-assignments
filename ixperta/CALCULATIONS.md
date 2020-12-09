# Calculations 

## Description

Create Single Page Application in React according to specification below and attached screens.
Application is inspired by Dr. Kawashima Brain Training in simplified form. 

1. Application has two screens, Home and Calculations
1. On Home Screen, User can set up Number of Calculations (NoC) and start solving calculations by clicking on Start button (see `Home.png`)
1. After clicking on Start button, User is redirected to Calculations Screen where he will be presented with Grid of Arithmetic Calculation Components, Stopwatch with passed time information and current state of Finished Calculations (see `Calculations.png`)
1. Calculation Components are generated dynamically based on number of operations, example values `3 + 9 =`, `7 - 5 =`, `2 * 9=` in case of NoC `3` (see Constraints below, minimum value 20, NoC `3` just as example)
1. Calculation Components contains arithmetic calculation and input for entering result.
1. User can submit result of calculation by entering value to result input field and pressing "Enter" key on keyboard to Submit. Calculation component will then change its background color based on the correctness of the result and counter of finished calculations is increased. Once submitted, User cannot change result he entered and have to move to the next Calculation.
1. Once all Calculations are resolved, Stopwatch will be stopped presenting elapsed time Information highlighted
1. User can Navigate back to Home Page to start again with different number of calculations.
1. Any Extensions or Modifications are welcomed while preserving Core Functionality

---
## Constraints

- Number of calculations in required, `20 <= NoC <= 60`
- Calculations are in form of `n o m = r` where *n* and *m* are operands, Non-Negative Integers in range `1 <= n, m <= 10`, *o* is arithmetic operator and *r* is result
- Calculations could be based on any of the following arithmetic operations: multiplication, addition or subtraction
- Do not use floating point numbers for simplicity

---
## Bonus Points

 - Add Division Calculation based on Small Multiplication Table (no division reminders allowed)
 - Attention to Details in Visual Representation e.g using libraries like Bootstrap, Material UI ...
 - Unit/E2e Tests
 