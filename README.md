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
* {0) Moving Right
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
        0 : [(1.0, 2, 0.0, False)],
        1 : [(1.0, 4, 0.0, False)],
        2 : [(1.0, 1, 0.0, False)],
        3 : [(1.0, 1, 0.0, False)]
    },

    2 : {
        0 : [(1.0, 3, 0.0, False)],
        1 : [(1.0, 5, 0.0, False)],
        2 : [(1.0, 1, 0.0, False)],
        3 : [(1.0, 0, 0.0, False)]
    },

    3 : {
        0 : [(1.0, 3, 0.0, False)],
        1 : [(1.0, 6, 0.0, False)],
        2 : [(1.0, 2, 0.0, False)],
        3 : [(1.0, 3, 0.0, False)]
    },

    4 : {
        0 : [(1.0, 5, 0.0, False)],
        1 : [(1.0, 4, 0.0, False)],
        2 : [(1.0, 4, 0.0, False)],
        3 : [(1.0, 1, 0.0, False)]
    },

    5 : {
        0 : [(1.0, 6, 0.0, False)],
        1 : [(1.0, 7, 1.0, True)],
        2 : [(1.0, 4, 0.0, False)],
        3 : [(1.0, 2, 0.0, False)]
    },

    6 : {
        0 : [(1.0, 6, 0.0, False)],
        1 : [(1.0, 6, 0.0, False)],
        2 : [(1.0, 5, 0.0, False)],
        3 : [(1.0, 3, 0.0, False)]
    },

    7 : {
        0 : [(1.0, 7, 1.0, True)],
        1 : [(1.0, 7, 1.0, True)],
        2 : [(1.0, 7, 1.0, True)],
        3 : [(1.0, 7, 1.0, True)]
    },
}
```

## OUTPUT:
![image](https://github.com/VaishnaviMariappan/mdp-representation/assets/94169913/d3e2533d-52f3-4d40-ad66-7f982af55ff9)


## RESULT:
Thus a real world problem is represented as Markov Decision Problem in the following ways successfully:

1. Text Representation
2. Graphical Representation
3. Python Representation

