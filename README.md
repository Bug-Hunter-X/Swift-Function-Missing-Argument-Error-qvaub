# Swift Function Missing Argument Error

This repository demonstrates a common error in Swift: forgetting to provide all required arguments when calling a function.

The `bug.swift` file shows the erroneous code, while `bugSolution.swift` provides a corrected version.

The problem arises from the line:

`let area2 = calculateArea(length: 20, width: )`

The `width` argument is missing, leading to a compiler error in Swift.

The solution involves providing all necessary arguments to the function.