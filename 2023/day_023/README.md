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
| mattcl | input-mattcl | 7.7 ± 0.3 | 7.0 | 8.7 | 1.00 |
| mattcl | input-lanjian | 7.8 ± 3.0 | 7.0 | 49.5 | 1.02 ± 0.39 |
| mattcl-py | input-lanjian | 460.6 ± 11.4 | 447.5 | 479.6 | 60.20 ± 2.51 |
| mattcl-py | input-mattcl | 471.2 ± 5.1 | 467.0 | 477.8 | 61.59 ± 2.17 |
| lanjian | input-lanjian | 885.1 ± 3.0 | 881.7 | 887.4 | 115.68 ± 3.91 |
| lanjian | input-mattcl | 916.1 ± 44.8 | 888.4 | 967.8 | 119.74 ± 7.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>2250</pre>|<pre>6470</pre>|
|input-mattcl|<pre>2438</pre>|<pre>6658</pre>|