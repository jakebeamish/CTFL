
> [TDD](Test-driven%20Development.md), [ATDD](Acceptance%20test-driven%20development.md), and [BDD](Behaviour-driven%20development.md) are similar development approaches, where tests are defined as a means of directing development. Each of these approaches implements the principle of [early testing](Early%20testing%20saves%20time%20and%20money.md) (see section 1.3) and follows a shift-left approach (see section 2.1.5), since the tests are defined before the code is written. They support an iterative development model. These approaches are characterised as follows:
> 
> [Test-driven Development](Test-driven%20Development.md):
> - Directs the coding through test cases (instead of extensive software design) (Beck 2003)
> - Tests are written first, the n the code is written to satisfy the test, and then the tests and code are refactored
> 
> [Acceptance test-driven development](Acceptance%20test-driven%20development.md):
> - Derives tests from acceptance criteria as part of the system design process (Gartner 2011)
> - Tests are written before the part of the application is developed to satisfy the tests
>
> [Behaviour-driven development](Behaviour-driven%20development.md):
> - Expresses the desired behaviour of an application with test cases written in a a simple form of natural language, which is easy to understand by stakeholders - usually using the Given/When/Then format. (Chelimsky 2010)
> - Test cases are then automatically translated into executable tests
>
> For all the above approaches, tests may persist as automated tests to ensure the code quality in future adaptions / refactoring.[^1]

[^1]: Certified Tester Foundation Level Syllabus (v4.0). April 21, 2023. ISTQB. Retrieved from https://www.istqb.org/certifications/certified-tester-foundation-level.