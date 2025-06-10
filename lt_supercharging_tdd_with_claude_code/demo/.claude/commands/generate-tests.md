**AI Test Suite Generator**

Analyzes requirements from a specification file and generates comprehensive test cases following TDD principles.

**Inputs**

requirements_file: $ARGUMENTS
test_suite_file: $ARGUMENTS

**Instructions**

1. **Analyze Requirements**: Read and parse the requirements file (requirements_file) to understand:

   - Core functionality and features
   - Input/output specifications
   - Business rules and constraints
   - Expected behaviors

2. **Generate Test Suite**: Create test cases in the specified test file (test_suite_file) that include:

   - **Happy Path Tests**: Normal use cases with valid inputs
   - **Edge Cases**: Boundary conditions and limits
   - **Error Handling**: Invalid inputs and error scenarios
   - **Integration Tests**: Component interactions if applicable

3. **Follow TDD Structure**:

   - Write descriptive test names that explain the expected behavior
   - Use Arrange-Act-Assert pattern
   - Start with failing tests (Red-Green-Refactor cycle)
   - Group related tests logically
