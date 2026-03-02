# YANG XML

This is the repository for the document `draft-yn-netmod-yang-xml`
(XML Encoding of YANG Data).

The document  mimics RFC 7951 (JSON Encoding of YANG Data), whilst
incoporating content from RFC 7951.  The XML has comments indicating
where content was sourced.


## Build Artifacts and Diffs

https://netmod-wg.github.io/yang-xml

GitHub workflow actions are used to automatically build, test, and
publish the three drafts, in the `html`, `txt`, and `xml` formats.
This automation occur for both the `main` branch and every PR-branch.

The webpage also provide links to:
  - diff the `main` branch against RFC 7950.
  - diff the `main` branch against Datatracker.
  - diff a PR-branch against the `main` branch.


## Contributing

All contributions are made using pull requests (PRs).

Please see the [contributing](https://github.com/netmod-wg/yang-xml/blob/main/CONTRIBUTING.md) page for details.


## Command Line Usage

Formatted text and HTML versions of the draft can be built using `make`.

```sh
$ make clean && make
```

Command line usage requires that you have the necessary software installed.
You will need `make`, `python`, `xml2rfc`, and `rfcfold`.
