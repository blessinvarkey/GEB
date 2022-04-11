### Gödel Escher Bach - MIU System

- Hofstadter in the first chapter introduces _formal systems_ which is one of the central notions of the book. 
- The objective is __not finding the answer, but looking for it.__
- He offers a puzzle 'Can you produce MU?' with a string of letters - MI
- There are three symbols: M,I,U
- There are four rules:
    1. If you posses a string whose last letter is I, you can add on a U at the end.
    2. If you have Mx, you may add x to obtain Mxx to your collection.
        From MIU-> MIUIU
        From MUM-> MUMUM
        From MU-> MUU
    3. If three I's (III) occurs in one of the string in your collection, you may substitute U in place of III
    4. If UU occurs inside one of your strings, you can drop it.
        From UUU->U
- The Goal is to not to find the answer, but to look for it. 

### Theorms, Axioms, Rules
- Theorems: Strings producible by rules are called __theorems__ (not the same as how its used in mathematics).   
- In formal systems, theorems need not be thought of as statements - they are merely strings of symbols. 
- Instead of being proven, theorems are merely produced, as if by machine, according to certain typographical rules. 
- Hofstader gives a free theorem - MI (which is an axiom)

|Statement|type|
|-|-|
|MI|axiom|

Problem 1: If MI (is true), then MUIU (is true) [[1](https://www.youtube.com/watch?v=9lED9pKtTqQ&t=379s)]

|Statement|Reason|
|--|--|
| MI | Given | 
| MII | Rule 2|
|MIIII| Rule 2|
|MIIIIU|Rule 1|
|MUIU|Rule 3|


Fun [MIU System Applet](https://tn1ck.github.io/MIU/) by Tom Nick. 


## What is a Decision Procedure? 
- A Decision Procedure is a "litmus test" for theoremhood
- MU Puzzle involves rules of two opposing tendencies: __lenghtening__ (increase in size) and __shortening__ (shrink - in rigid ways)
- 