# Day 13 benchmarks

[link to problem](https://adventofcode.com/2024/day/13)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 13)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-kcen | 1.3 ± 0.3 | 0.3 | 1.8 | 1.00 |
| kcen | input-kcen | 1.3 ± 0.3 | 0.3 | 1.9 | 1.01 ± 0.34 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.6 | 1.9 | 1.05 ± 0.31 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.5 | 2.2 | 1.06 ± 0.31 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.6 | 2.2 | 1.06 ± 0.31 |
| lanjian | input-mattcl | 1.4 ± 0.1 | 1.0 | 1.8 | 1.09 ± 0.30 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.6 | 1.9 | 1.10 ± 0.32 |
| kcen | input-lanjian | 1.5 ± 0.2 | 0.9 | 2.3 | 1.11 ± 0.31 |
| kcen | input-mattcl | 1.5 ± 0.2 | 0.6 | 2.4 | 1.11 ± 0.32 |
| mattcl-py | input-lanjian | 16.7 ± 0.7 | 15.2 | 19.7 | 12.63 ± 3.23 |
| mattcl-py | input-mattcl | 16.7 ± 0.6 | 15.3 | 19.5 | 12.65 ± 3.23 |
| mattcl-py | input-kcen | 16.8 ± 0.6 | 15.5 | 19.5 | 12.70 ± 3.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>29201</pre>|<pre>104140871044942</pre>|
|input-lanjian|<pre>30413</pre>|<pre>92827349540204</pre>|
|input-mattcl|<pre>35997</pre>|<pre>82510994362072</pre>|