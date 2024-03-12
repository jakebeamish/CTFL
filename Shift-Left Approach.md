> The [principle of early testing](Early%20testing%20saves%20time%20and%20money.md) (see section 1.3) is sometimes referred to as shift-left because it is an approach where testing is performed earlier in the [SDLC](Software%20Development%20Lifecycle.md). Shift-left normally suggests that testing should be done earlier (e.g., not waiting for code to be implemented or for components to be integrated), but it does not mean that testing later in the [SDLC](Software%20Development%20Lifecycle.md) should be neglected.
>
> There are some good practices that illustrate how to achieve a "shift-left" in testing, which include:
> - Reviewing the specification from the perspective of testing. These review activities on specification often find potential [defects](Defect.md), such as ambiguities, incompleteness, and inconsistencies
> - Writing test cases before the code is written and have the code run in a test harness during code implementation
> - Using [CI](Continuous%20Integration.md) and even better CD as it comes with fast feedback and automated component tests to accompany source code when it is submitted to the code repository
> - Completing static analysis of source code prior to [Dynamic testing](Dynamic%20testing.md), or as part of an automated process
> - Performing [Non-functional testing](Non-functional%20testing.md) starting at the component test level, where possible. This is a form of shift-left as these non-functional test types tend to be performed later in the [SDLC](Software%20Development%20Lifecycle.md) when a complete system and a representative [Test environment](Test%20environment.md) are available
>
> A shift-left approach might result in extra training, effort and/or cost earlier in the process but is expected to save efforts and/or costs later in the process.
> 
> For the shift-left approach it is important that stakeholders are convinced and bought into this concept.