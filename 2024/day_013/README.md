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
| mattcl | input-kcen | 0.7 ± 0.5 | 0.1 | 1.6 | 1.00 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.4 | 1.7 | 1.88 ± 1.30 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.1 | 1.93 ± 1.31 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 2.1 | 1.94 ± 1.31 |
| kcen | input-kcen | 1.4 ± 0.2 | 0.4 | 2.1 | 1.98 ± 1.35 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.6 | 2.0 | 2.05 ± 1.38 |
| lanjian | input-mattcl | 1.4 ± 0.1 | 0.8 | 1.8 | 2.05 ± 1.37 |
| kcen | input-lanjian | 1.4 ± 0.1 | 0.8 | 2.6 | 2.06 ± 1.38 |
| kcen | input-mattcl | 1.4 ± 0.1 | 0.8 | 2.2 | 2.06 ± 1.37 |
| mattcl-py | input-mattcl | 16.5 ± 0.7 | 15.3 | 19.6 | 23.98 ± 15.88 |
| mattcl-py | input-lanjian | 16.6 ± 0.6 | 15.4 | 19.4 | 24.09 ± 15.94 |
| mattcl-py | input-kcen | 16.9 ± 1.0 | 15.5 | 20.0 | 24.54 ± 16.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>29201</pre>|<pre>104140871044942</pre>|
|input-lanjian|<pre>30413</pre>|<pre>92827349540204</pre>|
|input-mattcl|<pre>35997</pre>|<pre>82510994362072</pre>|