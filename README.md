# Date and Time on the Internet: Timestamps

This repository contains a WIP IETF I-D that seeks to replace [RFC 3339](https://tools.ietf.org/html/rfc3339)
by making the following updates:

1. The usage of 2-digit years is now no longer permitted.
2. The usage of the extended year format (6-digit with sign) is now allowed.
3. Numeric offsets can now include second and sub-second precision.
4. The RFC no longer contains an ABNF grammar describing ISO 8601.

## View

You can view the built HTML version of the draft [here](https://ryzokuken.dev/draft-ryzokuken-datetime-updated/documents/rfc-3339.html).

## Compare

You can compare the differences from the base RFC 3339 [here](https://github.com/ryzokuken/draft-ryzokuken-datetime-updated/compare/original...main).

## Building

```shell
$ make clean all
```
