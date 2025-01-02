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
| mattcl | input-kcen | 1.8 ± 0.4 | 0.7 | 2.9 | 1.00 |
| mattcl | input-mattcl | 1.8 ± 0.4 | 0.8 | 2.8 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 1.8 ± 0.4 | 0.9 | 2.9 | 1.04 ± 0.31 |
| kcen | input-kcen | 1.9 ± 0.4 | 1.1 | 2.9 | 1.06 ± 0.30 |
| kcen | input-mattcl | 1.9 ± 0.4 | 1.0 | 2.9 | 1.09 ± 0.31 |
| kcen | input-lanjian | 1.9 ± 0.4 | 1.0 | 3.0 | 1.10 ± 0.31 |
| lanjian | input-mattcl | 2.6 ± 0.2 | 1.8 | 3.4 | 1.46 ± 0.33 |
| lanjian | input-kcen | 2.6 ± 0.3 | 1.8 | 4.8 | 1.46 ± 0.35 |
| lanjian | input-lanjian | 2.6 ± 0.2 | 1.8 | 3.5 | 1.47 ± 0.34 |
| mattcl-py | input-kcen | 37.4 ± 1.1 | 35.9 | 41.0 | 21.29 ± 4.58 |
| mattcl-py | input-lanjian | 37.5 ± 0.7 | 36.4 | 40.4 | 21.34 ± 4.56 |
| mattcl-py | input-mattcl | 37.6 ± 0.9 | 36.2 | 40.5 | 21.43 ± 4.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1370100</pre>|<pre>818286</pre>|
|input-lanjian|<pre>1433460</pre>|<pre>855082</pre>|
|input-mattcl|<pre>1465968</pre>|<pre>897702</pre>|