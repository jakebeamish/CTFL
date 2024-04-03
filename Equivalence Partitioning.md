---
aliases:
  - Equivalence Class Partitioning
  - ECP
  - EP
  - Partition testing
---


[Equivalence Partitioning](Equivalence%20Partitioning.md) is a test case design technique where test cases are designed to execute representatives from equivalence classes. 

> A black-box test technique in which test conditions are equivalence partitions exercised by one representative member of each partition.[^2]

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

> Equivalence Partitioning (EP) divides data into partitions (known as equivalence partitions) based on the expectation that all the elements of a given partition are to be processed in the same way by the [[test object]]. The theory behind this technique is that if a test case, that tests one value from an equivalence partition, detects a [[defect]], this [[defect]] should also be detected by test cases that test any other value from the same partition. Therefore, one test for each partition is sufficient.
>
> Equivalence partitions can be identified for any data element related to the [[test object]], including inputs, outputs, configuration items, internal values, time-related values, and interface parameters. The partitions may be continuous or discrete ordered or unordered, finite or infinite. The partitions must not overlap and must be non-empty sets.
>
> For simple test objects EP can be easy, but in practice, understanding how the [[test object]] will treat different values is often complicated. Therefore, partitioning should be done with care.
> 
> A partition containing valid values is called a valid partition. A partition containing invalid values is called an invalid partition. The definitions of valid and invalid values may vary among teams and organisations. For example, valid values may be interpreted as those that should be processed by the [[test object]] or as those for which the specification defines their processing. Invalid values may be interpreted as those that should be ignored or rejected by the [[test object]] or as those for which no processing is defined in the [[test object]] specification.
> 
> In EP, the coverage items are the equivalence partitions. To achieve 100% [[coverage]] with this technique, test cases must exercise all identified partitions (including invalid partitions) by covering each partition at least once. [[Coverage]] is measured as the number of partitions exercised by at least one test case, divided by the total number of identified partitions, and is expressed as a percentage.
> 
> Many test objects include multiple sets of partitions (e.g., test objects with more than one input parameter), which means that a test case will cover partitions from different sets of partitions. The simplest coverage criterion in the case of multiple sets of partitions is called Each Choice coverage (Ammann 2016). Each Choice coverage requires test cases to exercise each partition from each set of partitions at least once. Each Choice coverage does not take into account combinations of partitions.[^1]

[^1]: Certified Tester Foundation Level Syllabus (v4.0). April 21, 2023. ISTQB. Retrieved from https://www.istqb.org/certifications/certified-tester-foundation-level.
[^2]: Standard Glossary of Terms used in Software Testing (v4.2.1). Jan 31, 2024. ISTQB. Retrieved from https://glossary.istqb.org/. Licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).
