# ID3 Decision Tree From Scratch

Implementing the ID3 algorithm from scratch in Python 
(no sklearn.tree, no CART) using a flattened-array tree representation.

## Why from scratch?
sklearn uses CART (Gini + binary splits). This project implements 
the classic ID3 (entropy + information gain + multiway splits) 
to understand the algorithm at a fundamental level.

## Features
- Entropy & information gain computed manually
- Flattened array tree (firstChild / nextSibling pointers)
- No external ML libraries for the model itself
- Tested on Mushroom (100%) and Titanic (78.65%)

## Results
| Dataset  | Accuracy | Notes |
|----------|----------|-------|
| Mushroom | 100.00%  | Perfectly separable |
| Titanic  | 78.65%   | Human data — noisy |

## How to run
...
