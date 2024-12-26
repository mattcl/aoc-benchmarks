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
| mattcl | input-mattcl | 1.8 ± 0.4 | 1.2 | 2.7 | 1.00 |
| mattcl | input-lanjian | 1.8 ± 0.4 | 1.1 | 2.8 | 1.01 ± 0.28 |
| mattcl | input-kcen | 1.9 ± 0.4 | 1.1 | 3.1 | 1.04 ± 0.29 |
| kcen | input-lanjian | 1.9 ± 0.3 | 1.2 | 3.0 | 1.05 ± 0.28 |
| kcen | input-mattcl | 1.9 ± 0.4 | 1.0 | 2.8 | 1.06 ± 0.29 |
| kcen | input-kcen | 2.0 ± 0.4 | 1.4 | 2.9 | 1.08 ± 0.29 |
| lanjian | input-kcen | 2.6 ± 0.2 | 1.5 | 3.3 | 1.44 ± 0.30 |
| lanjian | input-mattcl | 2.6 ± 0.2 | 1.8 | 3.4 | 1.45 ± 0.30 |
| lanjian | input-lanjian | 2.7 ± 0.4 | 1.9 | 5.5 | 1.46 ± 0.35 |
| mattcl-py | input-lanjian | 37.3 ± 0.8 | 35.9 | 40.0 | 20.48 ± 4.01 |
| mattcl-py | input-mattcl | 37.4 ± 1.3 | 35.8 | 45.3 | 20.52 ± 4.06 |
| mattcl-py | input-kcen | 37.6 ± 0.8 | 36.0 | 40.1 | 20.62 ± 4.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1370100</pre>|<pre>818286</pre>|
|input-lanjian|<pre>1433460</pre>|<pre>855082</pre>|
|input-mattcl|<pre>1465968</pre>|<pre>897702</pre>|