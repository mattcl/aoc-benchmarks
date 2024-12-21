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
| mattcl | input-kcen | 1.8 ± 0.3 | 0.7 | 2.7 | 1.00 |
| kcen | input-kcen | 1.9 ± 0.4 | 0.9 | 3.2 | 1.00 ± 0.28 |
| kcen | input-mattcl | 1.9 ± 0.3 | 1.1 | 2.7 | 1.02 ± 0.26 |
| kcen | input-lanjian | 1.9 ± 0.3 | 1.0 | 2.7 | 1.02 ± 0.26 |
| mattcl | input-mattcl | 1.9 ± 0.4 | 1.2 | 3.3 | 1.03 ± 0.28 |
| mattcl | input-lanjian | 1.9 ± 0.4 | 1.3 | 3.1 | 1.04 ± 0.28 |
| lanjian | input-kcen | 2.5 ± 0.4 | 1.3 | 4.7 | 1.33 ± 0.32 |
| lanjian | input-mattcl | 2.6 ± 0.3 | 1.8 | 5.2 | 1.41 ± 0.31 |
| lanjian | input-lanjian | 2.6 ± 0.3 | 1.8 | 5.3 | 1.42 ± 0.32 |
| mattcl-py | input-lanjian | 37.1 ± 0.9 | 35.3 | 40.1 | 20.09 ± 3.68 |
| mattcl-py | input-mattcl | 37.2 ± 0.9 | 35.7 | 40.2 | 20.10 ± 3.68 |
| mattcl-py | input-kcen | 37.4 ± 1.1 | 36.1 | 40.9 | 20.22 ± 3.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1370100</pre>|<pre>818286</pre>|
|input-lanjian|<pre>1433460</pre>|<pre>855082</pre>|
|input-mattcl|<pre>1465968</pre>|<pre>897702</pre>|