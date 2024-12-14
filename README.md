# Ruby NoMethodError Bug
This repository demonstrates a common error in Ruby: attempting to modify an attribute without defining a corresponding setter method.

The `bug.rb` file shows the problematic code.  The `bugSolution.rb` file provides a corrected version.

This example highlights the importance of explicit setter methods (using `attr_writer`, `attr_accessor`, or custom setter methods) when you intend to modify an object's attributes.
