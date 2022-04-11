# Gödel, Escher, Bach: an Eternal Golden Braid

## Introduction
- First line of this introduction is "Author: ". Hmmmm....
- Bach's Musical Offering is awesome: it contains a 6-part fugue on a theme by Frederick the Great.
- A canon is made up of multiple transformed copies of a theme played against each other. 
- The copies can be displaced in time or pitch; played at different speeds (diminution, augmentation); or inverted. There is a notion of a retrograde copy, too.
- A transformation from which the original is fully recoverable is called an isomorphism. (This is a general notion, applicable not only to themes BTW.)
- Fugues are like canons but a bit looser. They start with one voice and as the next voice enters (+5 or -4), the previous voices become the countersubject.
- One of canons in the Musical Offering, The Endlessly Rising Canon (Canon per Tonos) features a 6-step modulation that returns to its starting point (Cm → Dm → Em → F#m → A♭m → B♭m → Cm) and is an example of a strange loop.
- Escher's Waterfall and Ascending and Descending contain strange loops.
- Escher's Drawing Hands and Print Gallery contain a wilder kind of strange loop, because the levels show different degrees of reality and fantasy. Think about it![[1](https://cs.lmu.edu/~ray/notes/geb/)]

## Terminologies


__Axiom__    
__Theorem__    
__Rules__    
__Rules of Production__   
__Decision Procedure__


__Formal System__   
__Isomorphism__


__Recursive Mathematical Function__
- Factorials: n! = n*(n-1!) 

```
def factorial(n):
    if(n>1):
        return n*factorial(n-1)
    else:
        return 1
```
- Godel: Every mathematical system is incomplete. 
- Anything you think you know will have something that is off

### Explain recursion to a 4 year old

Aaron Krolik via Quora [[1](https://www.quora.com/How-should-I-explain-recursion-to-a-4-year-old)]

"Someone in a movie theater asks you what row you're sitting in. You don't want to count, so you ask the person in front of you what row they are sitting in, knowing that you will respond one greater than their answer. The person in front will ask the person in front of them. This will keep happening until word reaches the front row, and it is easy to respond: "I'm in row 1!" From there, the correct message (incremented by one each row) will eventually make its way back to the person who asked.

GEB deals with the limitations of the mind and logic. Take this old unsolvable riddle: “All Cretans are liars. I am a Cretan." So, are all Cretans liars? Or consider a card, on both sides of which is printed this sentence: “The statement on the other side of this card is false." Or change the lines. On one side of the card is printed: “The statement on the other side of this card is false." And on the flip side: “The statement on the other side of this card is true." So, what is true? And what is false? [[2](https://www.livemint.com/Sundayapp/umPh3ARDU4D1XzsobuUQ4J/Gdel-Escher-Bach-When-logic-flies-out-of-the-window.html)]

Why is this a good explanation?

It gets across three points:

- There are some questions that may be inherently recursive and that some questions are easier to solve recursively.
- The question I am asking ("what row am I in?") can be rephrased recursively as: "how many people are in front of me + 1?" with a base case of zero people in front of me.
- It also illustrates the idea of a recursive call stack and how calls are pushed on then popped off the stack."