# Day 23 benchmarks

[link to problem](https://adventofcode.com/2023/day/23)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 23)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 9.5 ± 0.2 | 8.8 | 10.3 | 1.00 |
| mattcl | input-lanjian | 9.7 ± 3.3 | 8.7 | 55.4 | 1.02 ± 0.34 |
| mattcl-py | input-lanjian | 677.7 ± 13.6 | 664.0 | 692.8 | 71.24 ± 2.23 |
| mattcl-py | input-mattcl | 686.9 ± 14.7 | 670.5 | 705.7 | 72.21 ± 2.32 |
| lanjian | input-mattcl | 889.6 ± 16.2 | 874.0 | 906.4 | 93.52 ± 2.83 |
| lanjian | input-lanjian | 899.2 ± 28.3 | 873.4 | 929.5 | 94.52 ± 3.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>2250</pre>|<pre>6470</pre>|
|input-mattcl|<pre>2438</pre>|<pre>6658</pre>|