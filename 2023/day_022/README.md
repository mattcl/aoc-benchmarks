# Day 22 benchmarks

[link to problem](https://adventofcode.com/2023/day/22)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 22)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.0 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.02 ± 0.29 |
| lanjian | input-lanjian | 6.8 ± 0.7 | 6.0 | 11.8 | 5.24 ± 1.23 |
| lanjian | input-mattcl | 6.8 ± 0.5 | 6.2 | 9.2 | 5.28 ± 1.15 |
| mattcl-py | input-lanjian | 50.2 ± 0.6 | 48.7 | 52.3 | 38.76 ± 8.05 |
| mattcl-py | input-mattcl | 51.4 ± 0.6 | 50.4 | 53.7 | 39.66 ± 8.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>426</pre>|<pre>61920</pre>|
|input-mattcl|<pre>441</pre>|<pre>80778</pre>|