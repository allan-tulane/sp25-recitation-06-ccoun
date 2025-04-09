# CMPS 2200 Recitation 06
## Answers

**Name:** Charlie Coun
**Name:**_________________________


Place all written answers from `recitation-07.md` here for easier grading.



- **2)** The recurrence for work would be W(n) = W(n-1) + W(n-2) + O(1) since we do constant work alongside the recursive calls of (n-1) and (n-2), which comes out to W(n) = O(2^n).

- **3)** The recurrence for span would be S(n) = S(n-1) + O(1) since it is not parallel and fib(n-1) must finish before returning, which comes out to S(n) = O(n).

- **4)** We can see that the counts form the fibonacci sequence, but reversed, with counts[1] = F12 = 89, counts[2] = F11 = 55, counts[3] = F10 = 34, ... etc. This makes sense since the recursive branching causes lower-index fibonnaci calls to be made many times.

- **6)** Because of memoization, each fibonnaci number is only computed at most once, since once it's computed, it's stored in fibs[i] and never recomputed. The work would be W(n) = O(n) since each value is only computed once, and span would be S(n) = S(n-1) + O(1) = O(n) as we still need to computer fib(n-1) before fib(n).

- **8)**
