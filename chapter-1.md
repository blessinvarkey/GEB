### Gödel Escher Bach - MIU System

Undefined terms: M,I,U
Definition: X = any string of I's and U's 

The first formal system introduced in the book is the MIU system. It follows four rules/postulates:

1. If you posses a string whose last letter is I, you can add on a U at the end.
2. If you have Mx, you may add x to obtain Mxx.
2. If three I's (III) occurs in one of the string in your collection, you may substitute U in place of III
3. If UU occurs inside one of your strings, you can drop it.

The Goal is to get from MI to MU. 

Problem 1: If MI (is true), then MUIU (is true) [[1](https://www.youtube.com/watch?v=9lED9pKtTqQ&t=379s)]

|Statement|Reason|
|--|--|
| MI | Given | 
| MII | Postulate 2|
|MIIII| Postulate 2|
|MIIIIU|Postulate 1|
|MUIU|Postulate 3|


Fun [MIU System Applet](https://tn1ck.github.io/MIU/) by Tom Nick. 