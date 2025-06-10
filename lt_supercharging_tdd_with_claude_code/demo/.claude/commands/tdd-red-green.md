**Red-Green TDD Implementation**

**Input**

test_suite_file: $ARGUMENTS

**Description**

Implements minimal code to make failing tests pass in the TDD Red-Green cycle.

**Context**

We are focusing on the TDD (Test-Driven Development) cycle, specifically the
"Red-Green" phase. You're given a test suite that contains failing tests (test_suite_file). Your
task is to implement the necessary code to make the tests pass.

**Instructions**

1. **Analyze Failing Tests**: Read the test suite to understand:

   - What functionality is being tested
   - Expected inputs and outputs
   - Error conditions being validated

2. **Run Tests**: Execute the test suite to see the failing tests and error messages

3. **Implement Minimal Code**: Write the **minimum amount of code** necessary to:

   - Make the failing test pass
   - Follow the "simplest thing that could possibly work" principle
   - Avoid over-engineering or implementing untested features

4. **Verify**: Run tests again to confirm they pass

## Key Principles

- **Red**: Tests fail (already written)
- **Green**: Make tests pass with minimal code
- **Don't**: Add extra features not covered by tests
- **Focus**: Only on making the current failing test pass
