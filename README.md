## The Multibase Data Format

This specification describes a forward-compatible data model for expressing
raw binary data in a variety of base-encoding formats such as base32,
base58. and base64.

Raw binary data is often encoded using a mechanism that enables the data
to be included in human-readable text-based formats. This mechanism is often
referred to as "base-encoding the data". Base-encoding is often used when
expressing binary data in hyperlinks, cryptographic keys in web pages, or
security tokens in application software. There are a variety of base-encodings,
such as base32, base58, and base64. It is not always possible to differentiate
one base-encoding from another. The purpose of this specification is to provide
a mechanism to be able to deterministically identify the base-encoding for a
particular string of data.

You can view an HTML version of the specification here:

[https://w3c-dvcg.github.io/multibase/](https://w3c-dvcg.github.io/multibase/)

We encourage contributions meeting the [Contribution
Guidelines](CONTRIBUTING.md).  While we prefer the creation of issues
and Pull Requests in the GitHub repository, discussions often occur
on the
[public-credentials](http://lists.w3.org/Archives/Public/public-credentials/)
mailing list as well.

### Other useful links
* [Multiformats Website](https://multiformats.io/)
* [Multibase Website](https://multiformats.io/multibase/)
* [Public group email archive](https://lists.w3.org/Archives/Public/public-credentials/)
