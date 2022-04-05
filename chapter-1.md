### Gödel Escher Bach - MIU System

- Hofstadter in the first chapter introduces formal systems which is one of the central notions of the book. 
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
- Theorems: Strings producible by rules are called __theorems__ (not the same as how its used in mathematics). It means some statement in ordinary language which has been proven to be true by a righteous argument (like the Zeno's or Euclid's Theorm)  
- Instead of being proven, theorems are merely produced, as if by machine, according to certain typographical rules. 

Problem 1: If MI (is true), then MUIU (is true) [[1](https://www.youtube.com/watch?v=9lED9pKtTqQ&t=379s)]

|Statement|Reason|
|--|--|
| MI | Given | 
| MII | Postulate 2|
|MIIII| Postulate 2|
|MIIIIU|Postulate 1|
|MUIU|Postulate 3|


Fun [MIU System Applet](https://tn1ck.github.io/MIU/) by Tom Nick. 


