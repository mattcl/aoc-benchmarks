# Comparative benchmarks for Advent of Code implementations

A collection of comparative benchmarks between different advent of code
solutions.

These are generated with the goal of normalizing comparisons between different
implementations by running everything on the same hardware and against the same
sets of inputs.

The contained benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine docs, solutions that execute in < 5ms
are less accurate because of the shell startup time correction.


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
