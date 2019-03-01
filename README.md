# go-immutable

An attempt to add functional data structures to Go inspired by the
[Vavr project](http://www.vavr.io/).  [Section three](http://www.vavr.io/vavr-docs/#_usage_guide)
of the Vavr user's guide includes a diagram that shows the hierarchy of
these immutable data structures.

There's also an [interesting project](https://github.com/go-functional/core)
as well as an [associated presentation](https://www.youtube.com/watch?v=c8Fwb4KbVJM)
that describes how to perform many functional operations but it seems to
have been largely rejected by the Go community.

Since Go lacks annotations and favors code generation over reflection, this
library will primarily focus on generating boilerplate code for common
Go idioms - The first data structure and the example that will soon be
added will be a HashSet generator.

## References

1. [Vavr Project](http://www.vavr.io/)
2. [Vavr data structure hierarchy](http://www.vavr.io/vavr-docs/#_usage_guide)
3. [Go functional library](https://github.com/go-functional/core)
4. [Go functional presentation](https://www.youtube.com/watch?v=c8Fwb4KbVJM)
