---
aliases:
  - Cause-effect table
  - Decision table
---


[[Decision Table Testing]] is a technique for testing things where multiple input conditions yield a variety of outputs.

For example, imagine an image upload form where a user can upload images that are in .jpg format, 500x500px in size, and less than 2MB.

The number of cases in a full decision table is $2^n$, where $n$ is the number of inputs. Often this is infeasible, so a subset of chosen cases is tested instead.

| Conditions            |             |                     |               |                                    |                 |                                      |                                |                                                     |
| --------------------- | ----------- | ------------------- | ------------- | ---------------------------------- | --------------- | ------------------------------------ | ------------------------------ | --------------------------------------------------- |
| Format is .jpg        | T           | T                   | T             | T                                  | F               | F                                    | F                              | F                                                   |
| Size is < 2MB         | T           | T                   | F             | F                                  | T               | T                                    | F                              | F                                                   |
| Resolution is 500x500 | T           | F                   | T             | F                                  | T               | F                                    | T                              | F                                                   |
| Output                | ==Success== | Resolution mismatch | Size mismatch | Size mismatch, Resolution mismatch | Format mismatch | Format mismatch, Resolution mismatch | Format mismatch, Size mismatch | Format mismatch, Size mismatch, Resolution mismatch |




> Decision tables are used for [[testing]] the implementation of system requirements that specify how different combinations of conditions result in different outcomes. Decision tables are an effective way of recording complex logic, such as business rules.
> 
> When creating decision tables, the conditions and the resulting actions of the system are defined. These form the rows of the table. Each column corresponds to a decision rule that defines a unique combination of conditions, along with the associated actions. In limited-entry decision tables all the values of the conditions and actions (except for irrelevant or infeasible ones; see below) are shown as Boolean values (true or false).
> 
> Alternatively, in extended-entry decision tables some or all the conditions and actions may also take on multiple values (e.g., ranges of numbers, equivalence partitions, discrete values).
> 
> The notation for conditions is as follows: “T” (true) means that the condition is satisfied. “F” (false) means that the condition is not satisfied. “–” means that the value of the condition is irrelevant for the action outcome. “N/A” means that the condition is infeasible for a given rule. For actions: “X” means that the action should occur. Blank means that the action should not occur. Other notations may also be used.
> 
> A full decision table has enough columns to cover every combination of conditions. The table can be simplified by deleting columns containing infeasible combinations of conditions. The table can also be minimised by merging columns, in which some conditions do not affect the outcome, into a single column. Decision table minimisation algorithms are out of scope of this syllabus.
> 
> In decision table testing, the coverage items are the columns containing feasible combinations of conditions. To achieve 100% coverage with this technique, test cases must exercise all these columns. Coverage is measured as the number of exercised columns, divided by the total number of feasible columns, and is expressed as a percentage.
> 
> The strength of decision table testing is that it provides a systematic approach to identify all the combinations of conditions, some of which might otherwise be overlooked. It also helps to find any gaps or contradictions in the requirements. If there are many conditions, exercising all the decision rules may be time consuming, since the number of rules grows exponentially with the number of conditions. In such a case, to reduce the number of rules that need to be exercised, a minimised decision table or a risk-based approach may be used.[^1]


[^1]: Certified Tester Foundation Level Syllabus (v4.0). April 21, 2023. ISTQB. Retrieved from https://www.istqb.org/certifications/certified-tester-foundation-level.