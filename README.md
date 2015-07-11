It uses conductor solution with semaphores and mutexes. You can identify number of philosophers to eat (min=3, max=999, default=5) It prints the current state and stops working after all philosophers has finished eating. After than it shows statistics.

**Compile:** `gcc -pthread -o philutku2 philutku2.c`  <br />
**Execute:** `./philutku2 number_of_philosophers`  <br />
**Example:** `./philutku2 10`  <br />
**Output:**  <br />
```
Statistics:
Philosopher 1 eaten for 2 times
Philosopher 2 eaten for 1 times
Philosopher 3 eaten for 1 times
Philosopher 4 eaten for 2 times
Philosopher 5 eaten for 3 times
Philosopher 6 eaten for 1 times
Philosopher 7 eaten for 1 times
Philosopher 8 eaten for 2 times
Philosopher 9 eaten for 2 times
Philosopher 10 eaten for 1 times

```
