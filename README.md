# Unexpected Instance Variable Modification in Ruby

This repository demonstrates a subtle issue in Ruby related to modifying instance variables directly using `instance_variable_set`. While this is perfectly valid Ruby code, it can lead to unexpected behavior if not handled correctly.

The `bug.rb` file shows a basic example. The `bugSolution.rb` doesn't offer an explicit solution, as the bug isn't a true error but rather a potential source of confusion for developers new to Ruby's instance variable handling.