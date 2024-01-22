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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.9 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.8 | 1.9 | 1.01 ± 0.30 |
| lanjian | input-lanjian | 6.7 ± 0.6 | 5.8 | 12.0 | 5.41 ± 1.25 |
| lanjian | input-mattcl | 6.8 ± 0.4 | 6.2 | 10.2 | 5.48 ± 1.21 |
| mattcl-py | input-lanjian | 49.9 ± 0.5 | 48.8 | 51.2 | 40.08 ± 8.45 |
| mattcl-py | input-mattcl | 51.1 ± 0.5 | 50.0 | 52.6 | 41.01 ± 8.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>426</pre>|<pre>61920</pre>|
|input-mattcl|<pre>441</pre>|<pre>80778</pre>|