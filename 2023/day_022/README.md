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
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.9 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 2.3 | 0.9 | 34.2 | 1.05 ± 1.82 |
| lanjian | input-mattcl | 7.0 ± 0.6 | 6.0 | 9.6 | 5.40 ± 1.15 |
| lanjian | input-lanjian | 8.0 ± 7.7 | 6.2 | 73.5 | 6.15 ± 6.00 |
| mattcl-py | input-lanjian | 51.1 ± 4.4 | 49.0 | 83.7 | 39.25 ± 8.33 |
| mattcl-py | input-mattcl | 51.7 ± 0.5 | 50.3 | 52.8 | 39.73 ± 7.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>426</pre>|<pre>61920</pre>|
|input-mattcl|<pre>441</pre>|<pre>80778</pre>|