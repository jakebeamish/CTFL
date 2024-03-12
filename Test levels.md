---
aliases:
  - test level
  - test levels
  - test stage
---
> A specific instantiation of a [Test process](Test%20process.md).[^2]

> Test levels are groups of [test activities](Test%20Activities%20and%20Tasks.md) that are organised and managed together. Each test level is an instance of the [Test process](Test%20process.md), performed in relation to software at a given stage of development, from individual components to complete systems or, where applicable, systems of systems.
> 
> Test levels are related to other activities within the [SDLC](Software%20Development%20Lifecycle.md). In sequential [SDLC](Software%20Development%20Lifecycle.md) models, the test levels are often defined such that the exit criteria of one level are part of the entry criteria for the next level. In some iterative models, this may not apply. Development activities may span through multiple test levels. Test levels may overlap in time.
> 
> [Test Types](Test%20Types.md) are groups of test activities related to specific quality characteristics and most of those test activities can be performed at every test level.[^1]

---

> In this syllabus, the following five test levels are described:
> - [Component testing](Component%20testing.md) (also known as [unit testing](Component%20testing.md)) focuses on testing components in isolation. It often requires specific support, such as test harnesses or unit test frameworks. [Component testing](Component%20testing.md) is normally performed by developers in their development environments.
> - Component integration testing (also known as unit integration testing) focuses on testing the interfaces and interactions between components. Component integration testing is heavily dependent on the integration strategy approaches like bottom-up, top-down or big-bang.
> - System testing focuses on the overall behaviour and capabilities of an entire system or product, often including [Functional testing](Functional%20testing.md) of end-to-end tasks and the [Non-functional testing](Non-functional%20testing.md) of quality characteristics. For some non-functional quality characteristics, it is preferable to test them on a complete system in a  representative [Test environment](Test%20environment.md), (e.g. usability). Using simulations of sub-systems is also possible. System testing may be performed by an independent test team, and is related to specifications for the system.
> - System integration testing focuses on testing the interfaces of the system under test and other systems and external services. System integration testing requires suitable test environments preferably similar to the operational environment.
> - Acceptance testing focuses on [Validation](Validation.md) and on demonstrating readiness for deployment, which means that the system fulfils the user's business needs. Ideally, acceptance testing should be performed by the intended users. The main forms of acceptance testing are: user acceptance testing (UAT), operational acceptance testing, contractual and regulatory acceptance testing, alpha testing and beta testing.
>
> Test levels are distinguished by the following non-exhaustive list of attributes, to avoid overlapping of test activities:
> - [Test object](Test%20object.md)
> - [Test objectives](Test%20objectives.md)
> - [Test basis](Test%20basis.md)
> - [Defects](Defect.md) and [failures](Failure.md)
> - Approach and responsibilities[^1]



[^1]: Certified Tester Foundation Level Syllabus (v4.0). April 21, 2023. ISTQB. Retrieved from https://www.istqb.org/certifications/certified-tester-foundation-level.

[^2]: Standard Glossary of Terms used in Software Testing (v4.2.1). Jan 31, 2024. ISTQB. Retrieved from https://glossary.istqb.org/. Licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).