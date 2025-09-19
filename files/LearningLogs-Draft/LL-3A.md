# Learning Log 3A — Decision Trees and Entropy

Learning Objective: Explain rooted tree terminology, practice reading and building simple decision trees, and justify a split by comparing simple entropy counts.

## Task A — Tree vocabulary in context

In your own words, define root, parent, child, leaf, and edge, then describe how these parts work together in a decision tree you might use in everyday life.

### Answer guide:

Root = starting node, no parent; leaves = no children.

Every non-root node has exactly one parent; edges connect parent to child.

Short example, e.g., “Decide lunch”: root=“Hungry?”, children=“Budget?”, leaves=“Eat/Skip.”

Look for all five terms used correctly and one real-world example.

## Task B — Pick the best first split (Example from class)

Using the "Soccer League: Cancel Game" data, choose the single best attribute to split on first. Explain your choice by comparing the simple “mixed Yes/No” counts shown in class.

### Answer guide

Outlook gives overall entropy 10, better than Temperature, Windy, Humidity which give 14.
