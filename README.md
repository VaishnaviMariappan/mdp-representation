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
        0 : [(1.0, 0, 0.0, False)],
        1 : [(1.0, 2, 0.0, False)],
        2 : [(1.0, 0, 0.0, False)],
        3 : [(1.0, 0, 0.0, False)]
    },

    1 : {
        0 : [(0.85, 2, 0.0, False), (0.15, 1, 0.0, False)],
        1 : [(0.85, 4, 0.0, False), (0.15, 1, 0.0, False)],
        2 : [(1.0, 1, 0.0, False)],
        3 : [(1.0, 1, 0.0, False)]
    },

    2 : {
        0 : [(0.85, 3, 0.0, False), (0.15, 2, 0.0, False)],
        1 : [(0.85, 5, 0.0, False), (0.15, 2, 0.0, False)],
        2 : [(0.85, 1, 0.0, False), (0.15, 2, 0.0, False)],
        3 : [(0.85, 0, 0.0, False), (0.15, 2, 0.0, False)]
    },

    3 : {
        0 : [(1.0, 3, 0.0, False)],
        1 : [(0.85, 6, 0.0, False), (0.15, 3, 0.0, False)],
        2 : [(0.85, 2, 0.0, False), (0.15, 3, 0.0, False)],
        3 : [(1.0, 3, 0.0, False)]
    },

    4 : {
        0 : [(0.85, 5, 0.0, False), (0.15, 4, 0.0, False)],
        1 : [(1.0, 4, 0.0, False)],
        2 : [(1.0, 4, 0.0, False)],
        3 : [(0.85, 1, 0.0, False), (0.15, 4, 0.0, False)]
    },

    5 : {
        0 : [(0.85, 6, 0.0, False), (0.15, 5, 0.0, False)],
        1 : [(0.85, 7, 1.0, True), (0.15, 5, 0.0, False)],
        2 : [(0.85, 4, 0.0, False), (0.15, 5, 0.0, False)],
        3 : [(0.34, 2, 0.0, False), (0.15, 5, 0.0, False)]
    },

    6 : {
        0 : [(1.0, 6, 0.0, False)],
        1 : [(1.0, 6, 0.0, False)],
        2 : [(0.85, 5, 0.0, False), (0.15, 6, 0.0, False)],
        3 : [(0.85, 3, 0.0, False), (0.15, 6, 0.0, False)]
    },

    7 : {
        0 : [(1.0, 7, 0.0, True)],
        1 : [(1.0, 7, 0.0, True)],
        2 : [(1.0, 7, 0.0, True)],
        3 : [(1.0, 7, 0.0, True)]
    },
}
```

## OUTPUT:
![WhatsApp Image 2023-09-16 at 17 59 11](https://github.com/VaishnaviMariappan/mdp-representation/assets/94169913/1bd522b0-1fa8-4667-8306-462b29318cff)


## RESULT:
Thus a real world problem is represented as Markov Decision Problem in the following ways successfully:

1. Text Representation
2. Graphical Representation
3. Python Representation

