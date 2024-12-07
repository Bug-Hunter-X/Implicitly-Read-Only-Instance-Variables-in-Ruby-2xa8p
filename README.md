# Implicitly Read-Only Instance Variables in Ruby

This example demonstrates a common issue in Ruby where instance variables are implicitly read-only unless explicitly provided a writer method. Attempting to directly modify them results in a `NoMethodError`.

The `bug.rb` file shows the problematic code. The `bugSolution.rb` demonstrates the solution.