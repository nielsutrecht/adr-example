# ADR Example

## Installing ARD Tools

[See here](https://github.com/npryce/adr-tools/blob/master/INSTALL.md)

## Getting started

### Initialise project

`adr init`

This will initialise the repo and create a doc/adr directory (you can override this) with the first ADR explaining that we
will be recording ADRs in this repo :)

### Add an ADR

`adr new Use JUnit 4.12 for testing`

This adds a new ADR (automatically numbered as number 0002) that records our decision to use JUnit 4.12

### Supersede an ADR

`adr new -s 2 Use JUnit 5 for testing`

This creates an additional ADR that supersedes the old one (number 2). Both ADRs refer to each other. 