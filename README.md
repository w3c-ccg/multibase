## The Multibase Data Format

This specification describes forward-compatible data model for expressing
raw binary data in a variety of base-encoding formats such as base32,
base58. and base64.

When text is encoded as bytes, we can usually use a one-size-fits-all
encoding (UTF-8) because we're always encoding to the same set of 256 bytes.
When that doesn't work, usually for historical or performance reasons, we
can usually infer the encoding from the context.

However, when bytes are encoded as text (using a base encoding), the
choice of base encoding is often restricted by the context. Worse, these
restrictions can change based on where the data appears in the text. In
some cases, we can only use [a-z0-9]. In others, we can use a larger set
of characters but need a compact encoding. This has lead to a large set
of "base encodings", one for every use-case. Unlike when encoding text to
bytes, we can't just standardize around a single base encoding because
there is no optimal encoding for all cases.

Unfortunately, it's not always clear what base encoding is used; that's
where multibase comes in. It answers the question:

Given data d encoded into text s, what base is it encoded with?

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
