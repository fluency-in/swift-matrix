# Swift: Matrix

Write a program that, given a string representing a matrix of numbers, can return the rows and columns of that matrix.

So given a string with embedded newlines like:

> 9 8 7
> 5 3 2
> 6 6 7

representing this matrix:

```plain
    0  1  2
  |---------
0 | 9  8  7
1 | 5  3  2
2 | 6  6  7
```

your code should be able to spit out:

- A list of the rows, reading each row left-to-right while moving
  top-to-bottom across the rows,
- A list of the columns, reading each column top-to-bottom while moving
  from left-to-right.

The rows for our example matrix:

- 9, 8, 7
- 5, 3, 2
- 6, 6, 7

And its columns:

- 9, 5, 6
- 8, 3, 6
- 7, 2, 7

In order to use Swift, you must be running Xcode version 7.3 or greater which is available at [Apple's developer center][appledev].

[appledev]: https://developer.apple.com/xcode/downloads/

The exercises use XCTest.

See [this guide][exercism-xcode-swift] for details about how to create the project in XCode and run the tests.

[exercism-xcode-swift]: https://github.com/exercism/xswift/blob/master/docs/TESTS.md

## Source

Warmup to the `saddle-points` warmup. [http://jumpstartlab.com](http://jumpstartlab.com)

This exercise is from the [Swift][swift] track on [Exercism][exercism]

[exercism]: http://exercism.io
[swift]: http://exercism.io/languages/swift



