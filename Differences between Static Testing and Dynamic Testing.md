> [Static testing](Static%20testing.md) and [Dynamic testing](Dynamic%20testing.md) practices complement each other. They have similar objectives, such as supporting the detection of [defects](Defect.md) in work products (see section 1.1.1), but there are also some differences, such as:
> - Static and [Dynamic testing](Dynamic%20testing.md) (with analysis of [failures](Failure.md)) can both lead to the detection of [defects](Defect.md), however there are some [Defect](Defect.md) types that can only be found by either static or [Dynamic testing](Dynamic%20testing.md).
> - [Static testing](Static%20testing.md) finds [defects](Defect.md) directly, while [Dynamic testing](Dynamic%20testing.md) causes [failures](Failure.md) from which the associated [defects](Defect.md) are determined through subsequent analysis
> - [Static testing](Static%20testing.md) may more easily detect [defects](Defect.md) that lay on paths through code that are rarely executed or hard to reach using [Dynamic testing](Dynamic%20testing.md)
> - [Static testing](Static%20testing.md) can be applied to non-executable work products, while [Dynamic testing](Dynamic%20testing.md) can only be applied to executable work products
> - [Static testing](Static%20testing.md) can be used to measure [Quality](Quality.md) characteristics that are not dependent on executing code (e.g., maintainability) while [Dynamic testing](Dynamic%20testing.md) can be used to measure [Quality](Quality.md) characteristics that are dependent on executing code (e.g., performance efficiency)
>
> Typical [defects](Defect.md) that are easier and/or cheaper to find through [Static testing](Static%20testing.md) include:
> - [Defects](Defect.md) in requirements (e.g., inconsistencies, ambiguities, contradictions, omissions, inaccuracies, duplication)
> - Design [defects](Defect.md) (e.g., inefficient database structures, poor modularisation)
> - Certain types of coding [defects](Defect.md) (e.g., variables with undefined values, undeclared variables, unreachable or duplicated code, excessive code complexity)
> - Deviations from standards (e.g., lack of adherence to naming conventions in coding standards)
> - Incorrect interface specifications (e.g., mismatched number, type or order of parameters)
> - Specific types of security vulnerabilities (e.g., buffer overflows)
> - Gaps or inaccuracies in [Test basis](Test%20basis.md) [Coverage](Coverage.md) (e.g., missing tests for an acceptance criterion)