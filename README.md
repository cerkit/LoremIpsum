# LoremIpsum
A .NET class library (and associated sample application) that grabs "Lorem Ipsum" filler text from lipsum.com

Lorem Ipsum taken from [www.lipsum.com](http://www.lipsum.com) courtesy of James Wilson.

To get an API key for use with this library, please contact [Lipsum Help](mailto:help@lipsum.com).

### Release 2.0

**This release introduces breaking changes from v1.0.**

The sample application has been simplified and the static utility classes have been replaced by a `LoremIpsumFactory` class with the appropriate `Create()` and `CreateAsync()` methods.

Everything still works the same, except for the name changes. 

Refer to the [sample application](https://github.com/cerkit/lorem-ipsum/blob/master/LoremIpsumSampleApp/Program.cs) for guidance on how to use the latest changes.
