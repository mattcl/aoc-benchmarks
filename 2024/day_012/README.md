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
| mattcl | input-kcen | 1.7 ± 0.3 | 1.1 | 2.5 | 1.00 |
| mattcl | input-mattcl | 1.7 ± 0.4 | 1.0 | 2.7 | 1.01 ± 0.28 |
| mattcl | input-lanjian | 1.7 ± 0.3 | 0.9 | 2.8 | 1.02 ± 0.28 |
| kcen | input-mattcl | 1.8 ± 0.4 | 1.1 | 2.7 | 1.07 ± 0.29 |
| kcen | input-lanjian | 1.8 ± 0.3 | 1.0 | 2.8 | 1.07 ± 0.28 |
| kcen | input-kcen | 1.9 ± 0.3 | 1.3 | 2.7 | 1.10 ± 0.29 |
| lanjian | input-lanjian | 2.6 ± 0.2 | 1.8 | 3.5 | 1.52 ± 0.32 |
| lanjian | input-mattcl | 2.6 ± 0.2 | 1.8 | 4.2 | 1.55 ± 0.32 |
| lanjian | input-kcen | 2.6 ± 0.3 | 1.8 | 5.2 | 1.55 ± 0.35 |
| mattcl-py | input-mattcl | 37.8 ± 1.0 | 36.5 | 40.8 | 22.20 ± 4.23 |
| mattcl-py | input-lanjian | 37.9 ± 1.1 | 36.6 | 41.0 | 22.25 ± 4.25 |
| mattcl-py | input-kcen | 38.0 ± 1.1 | 36.4 | 42.5 | 22.29 ± 4.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1370100</pre>|<pre>818286</pre>|
|input-lanjian|<pre>1433460</pre>|<pre>855082</pre>|
|input-mattcl|<pre>1465968</pre>|<pre>897702</pre>|