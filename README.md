# Ruby Bug: Unexpected Instance Variable Modification

This repository demonstrates a potential issue in Ruby when directly modifying instance variables using `instance_variable_set`.  Directly manipulating instance variables bypasses any potential validation or encapsulation enforced by methods, leading to unexpected behavior and reduced code maintainability. The solution highlights the preferred approach of using methods for data access and modification.

## Bug
The `bug.rb` file shows how directly using `instance_variable_set` can change an object's state unexpectedly. This can make debugging and maintaining the code harder.