# Comparative benchmarks for Advent of Code implementations

An (unofficial) collection of comparative benchmarks between different advent of
code solutions.

These are generated with the goal of normalizing comparisons between different
implementations by running everything on the same hardware and against the same
sets of inputs.

The contained benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine docs, solutions that execute in < 5ms
are less accurate because of the shell startup time correction.

[This](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023) is the
pipeline for the current year (2023).


## Why?

Not everyone can or wants to compete on a time-to-submission-based global
leaderboard. Comparing benchmarks against a variety of inputs allows for both
correctness and execution time as an alternative measurement. Even between
languages with inherently different runtime speeds, the ratios of execution
times can indicate optimal or sub-optimal solutions for a given day when viewed
in aggregate.


## Requirements

Participants are required to implement solutions that can handle any official
input, and are requested to conform to the following
[specification](SPECIFICATION.md).


## Starter templates

There are some spec-compliant templates you can use as starting points:

* [python template](https://github.com/mattcl/aoc-python-template) via
  [cookiecutter](https://cookiecutter.readthedocs.io/en/stable/)
* [rust template](https://github.com/mattcl/aoc-template) via
  [cargo-generate](https://github.com/cargo-generate/cargo-generate)
