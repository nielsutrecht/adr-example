# 3. Use JUnit 5 for testing

Date: 2018-09-27

## Status

Accepted

Supercedes [2. Use JUnit 4.12 for testing](0002-use-junit-4-12-for-testing.md)

## Context

JUnit 5 was released and has nice additional features

## Decision

We've decided to adopt JUnit 5 because it handles testing for exceptions better and offers dynamic testing capabilities

## Consequences

@Rule annotations we use are deprecated therefor some integration tests might need to be migrated.
