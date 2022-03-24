# Gödel, Escher, Bach: an Eternal Golden Braid

## Terminologies

__Recursive Mathematical Function__
- Factorials: n! = n*(n-1!) 

```
def factorial(n):
    if(n>1):
        return n*factorial(n-1)
    else:
        return 1
```
