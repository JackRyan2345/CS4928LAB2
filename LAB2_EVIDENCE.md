# CS4928 Lab 2 Evidence

## Baseline
- Pinned SHA: cf437186b2ae2d9100a187e0df3cce3a163e9b4b
- Branch: cs4928-lab2
- Tag: CS4928_BASELINE
- JDK: 21.0.12.1 (JDK 27 failed: Error Prone 2.38.0 crashes in javac)

## Upstream test suite (mvn test)
- Result: PASSED
- Tests run: 138, Failures: 0, Errors: 0, Skipped: 0
- BUILD SUCCESS

## Problem A
- validateName mixes general validation with package-type-specific
  normalisation. Goal: move the varying name-normalisation algorithm behind a stable policy while preserving every existing
  result.