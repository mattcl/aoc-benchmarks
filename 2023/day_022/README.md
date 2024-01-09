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
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.3 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.3 | 0.9 | 2.1 | 1.04 ± 0.28 |
| lanjian | input-mattcl | 6.8 ± 0.4 | 6.2 | 8.9 | 5.08 ± 1.02 |
| lanjian | input-lanjian | 6.8 ± 0.9 | 6.0 | 13.7 | 5.12 ± 1.19 |
| mattcl-py | input-mattcl | 65.7 ± 6.8 | 63.4 | 110.3 | 49.25 ± 10.67 |
| mattcl-py | input-lanjian | 1754.3 ± 98.0 | 1644.4 | 1832.8 | 1315.12 ± 260.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>426</pre>|<pre>61920</pre>|
|input-mattcl|<pre>441</pre>|<pre>80778</pre>|