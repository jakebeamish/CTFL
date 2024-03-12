

| [[Functional testing]]                                | [[Non-functional testing]]         | [[Black-box test technique\|Black-box testing]] | [[White-box test technique\|White-box testing]] |
| ----------------------------------------------------- | ---------------------------------- | ----------------------------------------------- | ----------------------------------------------- |
| Evaluate the functions that the system should perform | Evaluate how well the system works | Evaluate the system against the specification   | Evaluate the internal structure of the system   |




> A lot of test types exist and can be applied in projects. In this syllabus, the following four test types are addressed:
> 
> [[Functional testing]] evaluates the functions that a component or system should perform. The functions are “what” the test object should do. The main objective of functional testing is checking the functional completeness, functional correctness and functional appropriateness.
> 
> [[Non-functional testing]] evaluates attributes other than functional characteristics of a component or system. [[Non-functional testing]] is the testing of “how well the system behaves”. The main objective of [[non-functional testing]] is checking the non-functional software quality characteristics. The ISO/IEC 25010 standard provides the following classification of the non-functional software quality characteristics: 
> - Performance efficiency
> - Compatibility
> - Usability
> - Reliability
> - Security
> - Maintainability
> - Portability
> 
> It is sometimes appropriate for [[non-functional testing]] to start early in the life cycle (e.g., as part of reviews and component testing or system testing). Many non-functional tests are derived from functional tests as they use the same functional tests, but check that while performing the function, a non-functional constraint is satisfied (e.g., checking that a function performs within a specified time, or a function can be ported to a new platform). The late discovery of non-functional defects can pose a serious threat to the success of a project. [[Non-functional testing]] sometimes needs a very specific test environment, such as a usability lab for usability testing.
> 
> Black-box testing (see section 4.2) is specification-based and derives tests from documentation external to the test object. The main objective of black-box testing is checking the system's behaviour against its specifications.
> 
> [[White-box test technique|White-box testing]] (see section 4.3) is structure-based and derives tests from the system's implementation or internal structure (e.g., code, architecture, work flows, and data flows). The main objective of [[White-box test technique|white-box testing]] is to cover the underlying structure by the tests to the acceptable level.
> 
> All the four above mentioned test types can be applied to all test levels, although the focus will be different at each level. Different test techniques can be used to derive test conditions and test cases for all the mentioned test types. [^1]

[^1]: Certified Tester Foundation Level Syllabus (v4.0). April 21, 2023. ISTQB. Retrieved from [https://www.istqb.org/certifications/certified-tester-foundation-level](https://www.istqb.org/certifications/certified-tester-foundation-level).