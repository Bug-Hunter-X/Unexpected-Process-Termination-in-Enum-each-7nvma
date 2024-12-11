This repository demonstrates an uncommon Elixir bug related to premature process termination within `Enum.each`. The `bug.ex` file shows the erroneous code where `Process.exit` is used inside `Enum.each` to halt the iteration early. This results in the loop not processing all elements. The solution in `bugSolution.ex` provides a corrected version demonstrating proper handling of process termination and iteration.