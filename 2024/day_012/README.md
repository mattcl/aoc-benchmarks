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
| kcen | input-kcen | 1.9 ± 0.4 | 0.8 | 3.0 | 1.00 |
| mattcl | input-mattcl | 1.9 ± 0.4 | 1.2 | 2.8 | 1.01 ± 0.28 |
| kcen | input-mattcl | 2.0 ± 0.4 | 1.0 | 3.0 | 1.02 ± 0.28 |
| mattcl | input-kcen | 2.0 ± 0.4 | 1.1 | 2.9 | 1.03 ± 0.28 |
| mattcl | input-lanjian | 2.0 ± 0.4 | 1.1 | 2.8 | 1.03 ± 0.28 |
| kcen | input-lanjian | 2.0 ± 0.4 | 1.1 | 2.9 | 1.03 ± 0.28 |
| lanjian | input-kcen | 2.6 ± 0.2 | 1.7 | 3.3 | 1.36 ± 0.30 |
| lanjian | input-lanjian | 2.6 ± 0.3 | 1.8 | 5.0 | 1.36 ± 0.32 |
| lanjian | input-mattcl | 2.6 ± 0.3 | 1.8 | 4.8 | 1.36 ± 0.31 |
| mattcl-py | input-mattcl | 37.6 ± 0.8 | 36.5 | 40.7 | 19.53 ± 3.97 |
| mattcl-py | input-lanjian | 37.9 ± 0.9 | 36.3 | 41.1 | 19.67 ± 4.01 |
| mattcl-py | input-kcen | 38.1 ± 1.1 | 36.1 | 40.9 | 19.78 ± 4.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1370100</pre>|<pre>818286</pre>|
|input-lanjian|<pre>1433460</pre>|<pre>855082</pre>|
|input-mattcl|<pre>1465968</pre>|<pre>897702</pre>|