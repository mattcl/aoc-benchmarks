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
| mattcl | input-mattcl | 1.7 ± 0.4 | 0.9 | 2.9 | 1.00 |
| mattcl | input-kcen | 1.8 ± 0.4 | 1.3 | 2.9 | 1.04 ± 0.31 |
| mattcl | input-lanjian | 1.8 ± 0.4 | 0.9 | 2.8 | 1.05 ± 0.31 |
| kcen | input-mattcl | 1.9 ± 0.4 | 1.0 | 3.0 | 1.08 ± 0.31 |
| kcen | input-kcen | 1.9 ± 0.3 | 1.0 | 2.9 | 1.09 ± 0.31 |
| kcen | input-lanjian | 1.9 ± 0.4 | 1.1 | 2.8 | 1.10 ± 0.31 |
| lanjian | input-kcen | 2.6 ± 0.3 | 1.7 | 4.9 | 1.47 ± 0.37 |
| lanjian | input-lanjian | 2.6 ± 0.2 | 1.8 | 4.8 | 1.48 ± 0.34 |
| lanjian | input-mattcl | 2.6 ± 0.3 | 1.9 | 4.8 | 1.48 ± 0.36 |
| mattcl-py | input-kcen | 37.4 ± 0.9 | 36.0 | 40.6 | 21.39 ± 4.61 |
| mattcl-py | input-lanjian | 37.5 ± 1.0 | 35.8 | 40.7 | 21.45 ± 4.63 |
| mattcl-py | input-mattcl | 37.6 ± 0.9 | 35.9 | 40.5 | 21.50 ± 4.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1370100</pre>|<pre>818286</pre>|
|input-lanjian|<pre>1433460</pre>|<pre>855082</pre>|
|input-mattcl|<pre>1465968</pre>|<pre>897702</pre>|