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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.9 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.01 ± 0.28 |
| lanjian | input-lanjian | 6.8 ± 0.6 | 6.2 | 11.6 | 5.19 ± 1.08 |
| lanjian | input-mattcl | 6.9 ± 0.6 | 6.3 | 10.3 | 5.29 ± 1.10 |
| mattcl-py | input-lanjian | 50.3 ± 0.8 | 49.0 | 54.3 | 38.61 ± 7.36 |
| mattcl-py | input-mattcl | 51.3 ± 0.6 | 49.8 | 52.4 | 39.42 ± 7.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>426</pre>|<pre>61920</pre>|
|input-mattcl|<pre>441</pre>|<pre>80778</pre>|