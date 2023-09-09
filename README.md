# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

1. Text representation
2. Graphical representation
3. Python - Dictonary representation

## PROBLEM STATEMENT:

### Problem Description
The start state is a school bus departing from a school carrying children, and the goal is to drop of the child at home.

### State Space
{0,1,2,3,4,5,6,7}

### Sample State
3

### Action Space
* {0} Moving Right
* {1} Moving Down
* {2} Moving Left
* {3} Moving Up

### Sample Action
{3} Moving Up

### Reward Function
* +1 - If the goal is reached
* 0 - Otherwise

## GRAPHICAL REPRESENTATION:
![WhatsApp Image 2023-09-03 at 20 40 02](https://github.com/VaishnaviMariappan/mdp-representation/assets/94169913/5589a508-1dda-4616-b081-35f1a29558f8)


## PYTHON REPRESENTATION:
```python
P = {
    0 : {
        0 : [(0.12, 0, 0.0, False)],
        1 : [(0.87, 2, 0.0, False)],
        2 : [(0.23, 0, 0.0, False)],
        3 : [(0.23, 0, 0.0, False)]
    },

    1 : {
        0 : [(0.45, 2, 0.0, False)],
        1 : [(0.87, 4, 0.0, False)],
        2 : [(0.23, 1, 0.0, False)],
        3 : [(0.23, 1, 0.0, False)]
    },

    2 : {
        0 : [(0.67, 3, 0.0, False)],
        1 : [(0.98, 5, 0.0, False)],
        2 : [(0.67, 1, 0.0, False)],
        3 : [(0.34, 0, 0.0, False)]
    },

    3 : {
        0 : [(0.23, 3, 0.0, False)],
        1 : [(0.98, 6, 0.0, False)],
        2 : [(0.76, 2, 0.0, False)],
        3 : [(0.12, 3, 0.0, False)]
    },

    4 : {
        0 : [(0.76, 5, 0.0, False)],
        1 : [(0.11, 4, 0.0, False)],
        2 : [(0.11, 4, 0.0, False)],
        3 : [(0.32, 1, 0.0, False)]
    },

    5 : {
        0 : [(0.65, 6, 0.0, False)],
        1 : [(0.99, 7, 1.0, True)],
        2 : [(0.65, 4, 0.0, False)],
        3 : [(0.34, 2, 0.0, False)]
    },

    6 : {
        0 : [(0.11, 6, 0.0, False)],
        1 : [(0.11, 6, 0.0, False)],
        2 : [(0.87, 5, 0.0, False)],
        3 : [(0.66, 3, 0.0, False)]
    },

    7 : {
        0 : [(0.98, 7, 1.0, True)],
        1 : [(0.65, 7, 1.0, True)],
        2 : [(0.89, 7, 1.0, True)],
        3 : [(0.88, 7, 1.0, True)]
    },
}
```

## OUTPUT:
![image](https://github.com/VaishnaviMariappan/mdp-representation/assets/94169913/4a5995e9-780c-4e9b-88f8-1cb2983df8e1)



## RESULT:
Thus a real world problem is represented as Markov Decision Problem in the following ways successfully:

1. Text Representation
2. Graphical Representation
3. Python Representation

