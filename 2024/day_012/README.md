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
| mattcl | input-mattcl | 1.7 ± 0.3 | 1.1 | 2.7 | 1.00 |
| mattcl | input-kcen | 1.7 ± 0.3 | 0.9 | 2.6 | 1.01 ± 0.27 |
| mattcl | input-lanjian | 1.7 ± 0.3 | 0.9 | 2.6 | 1.04 ± 0.28 |
| kcen | input-kcen | 1.8 ± 0.4 | 1.0 | 2.8 | 1.08 ± 0.30 |
| kcen | input-lanjian | 1.8 ± 0.3 | 0.9 | 2.6 | 1.10 ± 0.29 |
| kcen | input-mattcl | 1.9 ± 0.4 | 1.2 | 2.9 | 1.10 ± 0.30 |
| lanjian | input-kcen | 2.6 ± 0.3 | 1.8 | 3.3 | 1.54 ± 0.33 |
| lanjian | input-mattcl | 2.6 ± 0.3 | 1.8 | 5.2 | 1.55 ± 0.35 |
| lanjian | input-lanjian | 2.6 ± 0.3 | 1.7 | 4.9 | 1.56 ± 0.34 |
| mattcl-py | input-lanjian | 37.2 ± 0.7 | 36.0 | 39.9 | 22.12 ± 4.21 |
| mattcl-py | input-mattcl | 37.5 ± 1.1 | 36.2 | 40.5 | 22.29 ± 4.27 |
| mattcl-py | input-kcen | 37.5 ± 0.9 | 36.2 | 41.3 | 22.30 ± 4.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1370100</pre>|<pre>818286</pre>|
|input-lanjian|<pre>1433460</pre>|<pre>855082</pre>|
|input-mattcl|<pre>1465968</pre>|<pre>897702</pre>|