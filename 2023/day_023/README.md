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
| mattcl | input-mattcl | 7.6 ± 0.3 | 6.8 | 8.5 | 1.00 |
| mattcl | input-lanjian | 7.7 ± 0.6 | 7.2 | 14.3 | 1.01 ± 0.08 |
| lanjian | input-mattcl | 163.8 ± 1.5 | 161.3 | 166.0 | 21.48 ± 0.77 |
| lanjian | input-lanjian | 166.2 ± 5.5 | 162.2 | 184.7 | 21.79 ± 1.05 |
| mattcl-py | input-lanjian | 468.8 ± 9.3 | 451.6 | 477.8 | 61.47 ± 2.45 |
| mattcl-py | input-mattcl | 472.1 ± 14.0 | 452.1 | 488.7 | 61.90 ± 2.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>2250</pre>|<pre>6470</pre>|
|input-mattcl|<pre>2438</pre>|<pre>6658</pre>|