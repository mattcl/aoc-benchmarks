# Day 12 benchmarks

[link to problem](https://adventofcode.com/2024/day/12)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 12)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| kcen | input-kcen | 1.9 ± 0.4 | 1.1 | 2.9 | 1.00 |
| kcen | input-mattcl | 1.9 ± 0.3 | 1.2 | 2.8 | 1.03 ± 0.26 |
| mattcl | input-kcen | 2.0 ± 0.4 | 1.0 | 3.0 | 1.03 ± 0.27 |
| mattcl | input-mattcl | 2.0 ± 0.4 | 1.2 | 3.0 | 1.04 ± 0.28 |
| kcen | input-lanjian | 2.0 ± 0.4 | 1.1 | 3.2 | 1.04 ± 0.28 |
| mattcl | input-lanjian | 2.0 ± 0.4 | 1.2 | 3.1 | 1.06 ± 0.27 |
| lanjian | input-kcen | 2.6 ± 0.3 | 1.8 | 5.2 | 1.39 ± 0.29 |
| lanjian | input-mattcl | 2.6 ± 0.2 | 1.9 | 3.3 | 1.39 ± 0.28 |
| lanjian | input-lanjian | 2.7 ± 0.4 | 1.8 | 5.7 | 1.42 ± 0.32 |
| mattcl-py | input-lanjian | 37.4 ± 1.0 | 35.9 | 40.7 | 19.78 ± 3.71 |
| mattcl-py | input-mattcl | 37.7 ± 1.1 | 35.6 | 41.4 | 19.89 ± 3.75 |
| mattcl-py | input-kcen | 37.7 ± 1.1 | 36.1 | 41.6 | 19.94 ± 3.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1370100</pre>|<pre>818286</pre>|
|input-lanjian|<pre>1433460</pre>|<pre>855082</pre>|
|input-mattcl|<pre>1465968</pre>|<pre>897702</pre>|