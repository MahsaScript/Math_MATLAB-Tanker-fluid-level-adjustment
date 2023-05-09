# Tanker-fluid-level-adjustment
RBF-Radial Basis Function-back-production (BP)-based neural network is used to control level 

Purpose: control of liquid level in tanks and flow between tanks in industries
Liquids are processed by chemicals or mixing in tanks, but the level of liquids in the tanks must always be controlled and the flow between the tanks must be adjusted if it is not linear.
In this paper, a neural network based on backward generation is used to control level 2 in tank 2 with a set point of 10 cm, and it can track the changes of the set point to 8 cm in 225 seconds.

Control of water reservoirs and tankers using artificial neural network back propagation method

# Solution
There is a strong ability of neural networks in approximating non-linear mappings, which has potential results in the convergence of the iterative training method. Each time in the learning iteration method after processing all the training examples by the network and the network weights are updated.
Level control is one of the control system variables that is more important in process industries. Process industries require liquid pumping as well as storage in tanks and then pumped to another tank. In many cases, liquids are processed by chemicals or mixing in tanks, but the level of liquids in the tanks must always be controlled and the flow between the tanks must be regulated. The quality of the mixed product depends on the level of reactants present in the mixed mixture.

The liquid surface system in the complex industrial process has various system parameters and nonlinear characteristics. Most control functions in real design are usually defined by steady state error, dip, rise time, settle time.

## Parameter
![parameter](https://github.com/RoshaSoft/Tanker-fluid-level-adjustment/assets/85801966/dbfd63dd-7fd7-487c-924c-dc0dd8f7dfdf)

## Trigger
![trigger](https://github.com/RoshaSoft/Tanker-fluid-level-adjustment/assets/85801966/67558918-638e-40cf-953e-309b7e15d840)

## Data
![data](https://github.com/RoshaSoft/Tanker-fluid-level-adjustment/assets/85801966/0afd2fe7-0dfb-47b9-a452-7b7cf79872c1)


## MSE
![MSE](https://github.com/RoshaSoft/Tanker-fluid-level-adjustment/assets/85801966/9c92699d-639b-4b88-ae6b-582e2d2a8dc0)

## Tanker Level
![tanker-level](https://github.com/RoshaSoft/Tanker-fluid-level-adjustment/assets/85801966/91e7093b-b2dc-4268-8348-0a510d3bd818)

## Simulation
![gaussian-simulation](https://github.com/RoshaSoft/Tanker-fluid-level-adjustment/assets/85801966/4e4012c0-3d95-4e7c-b56c-631c4bade545)

## Baysian
![baysian](https://github.com/RoshaSoft/Tanker-fluid-level-adjustment/assets/85801966/0f21a998-0b22-430d-92ff-6baefab99256)

## gaussian-Formula
![gaussian-Formula](https://github.com/RoshaSoft/Tanker-fluid-level-adjustment/assets/85801966/d3f67c55-e692-40c6-a09c-0fc5cf1225f1)

## gaussian plot
![gaussian](https://github.com/RoshaSoft/Tanker-fluid-level-adjustment/assets/85801966/bb1d4e26-34a8-4cd1-8021-ddcf38b92fc6)


## Conclusion


In many cases, liquids are processed in tanks using chemicals or mixed treatments, but the level of liquids in the tanks must always be controlled and the flow between the tanks must be adjusted if it is not linear. Therefore, in this paper, a back-production (BP)-based neural network is used to control level 2 in tank 2 with a set point of 10 cm, and it can convert set point changes to a given set point of 8 cm in 225 seconds. Result of RBF Radial Basis Function Neural Network for Level 2 Control in Tank 2 Steady State Error = 0 cm, 0% Jump, Rise Time 49 Seconds, Settling Time 52 Seconds and can follow the set changes in 51 Seconds slow.
