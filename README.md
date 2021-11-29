GUI Tax Calculator
For this Tech Check, we are going to revisit the tax calculator program from an earlier Tech Check and turn it into a PyQt GUI application.

The total withheld tax amount is calculated by combining the amount of provincial tax withheld and the amount of federal tax withheld, minus a per-dependent deduction from the total tax withheld. The user will enter their pre-tax weekly salary amount and the number of dependents they wish to claim. The program will calculate and output the amount of provincial tax withheld, amount of federal tax withheld, the dependent tax deduction, and the user’s final take-home amount.

Provincial withholding tax is calculated at 6.0%. Federal withholding tax is calculated at 25.0%. The tax deduction for dependents is calculated at 2.0% of the employee’s salary per dependent.
