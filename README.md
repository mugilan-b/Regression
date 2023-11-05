# Regression <br>
This Python (Jupyter NB 6) project showcases linear and logistic regression performed on a single variable.

## Features: <br>
- **A generator**: capable of generating synthetic data. Synthesizes data distributed normally around a specified line. Variance can be controlled. <br>
- **Learning rates**: You can set learning rate differently for slope and bias. <br>
- **Comparing fit with Generator line**: A plot is shown at the end comparing fit line with generator line, as well as the cost functions of both.

## Generator: <br>
### Linear Regression: <br>
A line is specified. Data points are generated along the line at regular X intervals. A random y-offset is generated (normal distrib) and is added to all points.

![Lin_Reg_Plot](/LinReg.png?raw=true "Linear Regression sample run results")

### Logistic regression: <br>
Data points are generated along X axis at regular intervals. Two parameters are specified. This represents a sigmoid function (of x). This sigmoid function represents the probability of each x Data point having y value 1. If it is not 1 then it becomes 0.

![Log_Reg_Plot](/LogReg.png?raw=true "Logistic Regression sample run results")

## To-do: <br>
- Better visualization
- Multivariable support?
- Pandas integration and real-life data