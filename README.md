# PHP Type Juggling Bug
This example demonstrates a common error in PHP caused by loose typing and type juggling.  The `calculateSum` function unexpectedly handles a string within a numerical array, leading to an incorrect sum.  The solution shows how to explicitly type check to avoid this issue.

## How to Reproduce
1. Save the code in `bug.php`.
2. Run the script using a PHP interpreter: `php bug.php`.
3. Observe the unexpected output due to type juggling.

## Solution
The solution file, `bugSolution.php`, provides a corrected version of the function using type checking to handle only numeric values.