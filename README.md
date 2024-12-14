# PHP Function Redeclared without Error

This example demonstrates a potential issue in PHP where functions can be redeclared without causing an error. While PHP doesn't throw an error for this, it can lead to unexpected behavior because the latter declaration overrides the previous one. This can cause subtle and hard-to-debug issues in larger projects.

## How to Reproduce
1. Create a PHP file (bug.php) with the code provided in `bug.php`.
2. Run the script using a PHP interpreter.
3. Observe that the output reflects the behavior of the second function definition, not the first.

## Solution
The best approach to prevent this issue is to ensure that functions are defined once and only once in your code. Proper code organization, refactoring, and consistent naming conventions can help avoid accidental redefinitions.
