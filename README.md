# Pushdown Automaton (PDA)

A **Pushdown Automaton (PDA)** is a computational model that extends the concept of a finite automaton by adding a stack for additional memory. This allows PDAs to recognize context-free languages, which are more complex than the regular languages processed by finite automata.

## Overview of Pushdown Automata Implemented

1. **a^m b^m c^n.py**: Accepts strings where the number of 'a's equals the number of 'b's, followed by any number of 'c's.

2. **a^n b^(2n).py**: Accepts strings where the number of 'b's is exactly twice the number of 'a's.

3. **a^n b^(n+2).py**: Accepts strings where the number of 'b's is exactly two more than the number of 'a's.

4. **a^n b^3n.py**: Accepts strings where the number of 'b's is exactly three times the number of 'a's.

5. **a^n b^m c^(m+n).py**: Accepts strings where the number of 'c's equals the sum of the number of 'a's and 'b's.

6. **a^n b^m c^n.py**: Accepts strings where the number of 'c's equals the number of 'a's, with an independent number of 'b's in between.

7. **a^n b^n.py**: Accepts strings where the number of 'a's equals the number of 'b's.

8. **na equal to nb.py**: Accepts strings where the count of 'a' is equal to the count of 'b', regardless of order.

9. **na more than nb.py**: Accepts strings where the count of 'a' is greater than the count of 'b'.

10. **na not equal to nb.py**: Accepts strings where the count of 'a' is not equal to the count of 'b'.

11. **w c w^r.py**: Accepts strings in the format `w c w^r`, where `w` is a substring, `c` is a separator, and `w^r` is the reverse of `w`.

12. **w w^r.py**: Accepts strings in the format `w w^r`, where the second part is the reverse of the first part of the string.

Each of these PDAs demonstrates how the stack can be used to recognize complex patterns in strings. They serve as practical examples of solving problems involving context-free languages.

