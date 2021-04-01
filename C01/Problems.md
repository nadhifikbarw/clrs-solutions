### 1-1 Comparison of running times
---

For each function $f(n)$ and time $t$ in the following table, determine the largest size $n$ of a problem that can be solved in time $t$, assuming that the algorithm to solve the problem takes $f(n)$ microseconds.

#### Answers

Unfortunately without special algortihm we have to do manual computation to solve this problems, the approch is relatively simple, we know that 1 second is 1.000.000 microsecond so to calculate its N we can use formula like this 

$$f(n) = t$$

Using this pattern with $t$ is known we can solve its equation for each $t$ and each $f(n)$

$$t = \{10^6, 6*10^7, 3.6*10^9, 8.64*10^{10}, 2.628*10^{12}, 3.154*10^{13}, 3.154*10^{15}\}$$

|   | 1 second   | 1 minute     | 1 hour         | 1 day              | 1 month             | 1 year              | 1 century           |
|------------|------------|--------------|----------------|--------------------|---------------------|---------------------|---------------------|
| $\lg{n}$  | $2^{10^6}$ | $2^{6*10^7}$ | $2^{3.6*10^9}$ | $2^{8.64*10^{10}}$ | $2^{2.628*10^{12}}$ | $2^{3.154*10^{13}}$ | $2^{3.154*10^{15}}$ |
| $\sqrt{n}$ | e+12       | 3.6e+15      | 1.296e+19      | 7.46496e+21        | 6.718464e+24        | 9.94519296e+26      | 9.94519296e+30      |
| $n$        | $10^6$     | $6*10^7$     | $3.6*10^9$     | $8.64*10^{10}$     | $2.628*10^{12}$     | $3.154*10^{13}$     | $3.154*10^{15}$     |
| $n \lg{n}$ | 62746      | 2801417      | 133378058      | 2755147513         | 71870856404         | 797633893349        | 68654697441062      |
| $n^2$      | 1000       | 7745         | 60000          | 293938             | 1609968             | 5615692             | 56175382            |
| $n^3$      | 100        | 391          | 1532           | 4420               | 13736               | 31593               | 146677              |
| $2^n$      | 19         | 25           | 31             | 36                 | 41                  | 44                  | 51                  |
| $n!$       | 9          | 11           | 12             | 13                 | 15                  | 16                  | 17                  |