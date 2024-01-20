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
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.01 ± 0.28 |
| lanjian | input-mattcl | 7.0 ± 0.5 | 6.3 | 10.2 | 5.28 ± 1.08 |
| lanjian | input-lanjian | 7.3 ± 1.3 | 6.0 | 13.3 | 5.50 ± 1.45 |
| mattcl-py | input-lanjian | 50.5 ± 1.3 | 49.1 | 57.2 | 38.30 ± 7.43 |
| mattcl-py | input-mattcl | 51.3 ± 0.6 | 50.0 | 53.5 | 38.93 ± 7.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>426</pre>|<pre>61920</pre>|
|input-mattcl|<pre>441</pre>|<pre>80778</pre>|