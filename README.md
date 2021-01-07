# Date and Time on the Internet: Timestamps with additional information

This repository contains a WIP IETF I-D that seeks to replace [RFC 3339](https://tools.ietf.org/html/rfc3339)
by making the following updates:

1. Timestamps can now contain additional information including but not limited to timezone and calendar.
2. The usage of 2-digit years is now no longer permitted.
3. The usage of the extended year format (6-digit with sign) is now allowed.
4. Numeric offsets can now include section and sub-second precision.
5. The RFC no longer contains an ABNF grammar describing ISO 8601.

## View

You can view the built HTML version of the draft [here](https://ryzokuken.dev/draft-ryzokuken-datetime-extended/documents/rfc-3339.html).

## Compare

You can compare the differences from the base RFC 3339 [here](https://github.com/ryzokuken/draft-ryzokuken-datetime-extended/compare/original...master).

## Status

- [X] `00-front-area.adoc`
- [X] `01-intro.adoc`
- [X] `02-definitions.adoc`
- [X] `03-two-digit-years.adoc`
- [X] `04-local-time.adoc`
- [X] `05-date-time-format.adoc`
- [ ] `06-references.adoc`
- [X] `07-security.adoc`
- [X] `aa-iso-8601.adoc`
- [X] `ab-day-week.adoc`
- [X] `ac-leap-years.adoc`
- [X] `ad-leap-seconds.adoc`

## Building

```shell
$ make clean all
```
