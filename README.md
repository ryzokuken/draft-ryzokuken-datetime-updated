# Date and Time on the Internet: Timestamps with additional information

This repository contains a WIP IETF I-D that seeks to replace [RFC 3339](https://tools.ietf.org/html/rfc3339)
by allowing additional information like the timezone and calendar to be specified at the end of the timestamp.

## Status

- [X] `00-front-area.adoc`
- [X] `01-intro.adoc`
- [ ] `02-definitions.adoc`
- [X] `03-two-digit-years.adoc`
- [ ] `04-local-time.adoc`
- [ ] `05-date-time-format.adoc`
- [ ] `06-references.adoc`
- [ ] `07-security.adoc`
- [ ] `aa-iso-8601.adoc`
- [ ] `ab-day-week.adoc`
- [ ] `ac-leap-years.adoc`
- [ ] `ad-leap-seconds.adoc`

## Building

```shell
$ make clean all
```
