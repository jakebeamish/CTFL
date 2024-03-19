---
aliases:
  - Equivalence Class Partitioning
  - ECP
---


[Equivalence Partitioning](.md) is a test case design technique where test cases are designed to execute representatives from equivalence classes. 

---

For example, take a function that accepts any integer between 18 and 65. Input values within this range fall within the *valid partition* and values outside the range fall into *invalid partitions*.

The input $x$ can be divided into three partitions:

1. $x < 18$
2. $18 \leq x \leq 65$
3. $x > 65$

Test cases should be written to cover each of these scenarios at least once.

A test case with an input value of 17 will cover the first invalid partition ($x < 18$).

A second test case with an input value that is within the range (for example, 42) will cover the valid partition ($18 \leq x \leq 65$).

A third test case with an input value of 66 will test the second invalid partition ($x < 65$).

---

> Equivalence Partitioning (EP) divides data into partitions (known as equivalence partitions) based on the expectation that all the elements of a given partition are to be processed in the same way by the test object. The theory behind this technique is that if a test case, that tests one value from an equivalence partition, detects a defect, this defect should also be detected by test cases that test any other value from the same partition. Therefore, one test for each partition is sufficient.
