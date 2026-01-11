The SIR mathematical model separates a population into three groups: Susceptible, Infected, and Recovered. The spreadsheet uses Euler's method to approximate Ordinary Differential Equations that define the model. 

S' = -lambda * I * S
I' = (lambda * S - gamma) * I
R' = gamma * I

where the primes are the derivatives of each respective group.

Euler's Formula is defined by the following:
X_(n+1) = X_n + h*f'(X_n, …, Z_n).

Changes such as community compliance with wearing masks is then simulated to see what changes occur in the model.

The variables are left in a way that can be tested and altered with.
