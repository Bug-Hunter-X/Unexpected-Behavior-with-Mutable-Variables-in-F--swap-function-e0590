This repository demonstrates a common error in F# involving mutable variables and unexpected behavior. The `bug.fs` file shows a function that attempts to swap two mutable variables, but due to pass-by-reference semantics, it fails to produce the expected result. The `bugSolution.fs` demonstrates the correct way to swap variables using tuples or creating a new tuple to avoid unintended side effects.  This example highlights the importance of understanding F#'s mutable variable handling.