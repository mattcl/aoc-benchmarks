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
| kcen | input-lanjian | 1.9 ± 0.4 | 1.1 | 2.7 | 1.00 |
| kcen | input-kcen | 1.9 ± 0.4 | 1.2 | 2.9 | 1.00 ± 0.26 |
| kcen | input-mattcl | 2.0 ± 0.4 | 1.2 | 2.7 | 1.01 ± 0.26 |
| mattcl | input-kcen | 2.0 ± 0.4 | 1.2 | 2.8 | 1.02 ± 0.27 |
| mattcl | input-lanjian | 2.0 ± 0.3 | 1.3 | 3.0 | 1.02 ± 0.26 |
| mattcl | input-mattcl | 2.0 ± 0.4 | 1.3 | 3.6 | 1.04 ± 0.27 |
| lanjian | input-mattcl | 2.6 ± 0.3 | 1.4 | 4.8 | 1.35 ± 0.30 |
| lanjian | input-kcen | 2.6 ± 0.3 | 1.8 | 4.8 | 1.35 ± 0.29 |
| lanjian | input-lanjian | 2.7 ± 0.3 | 1.8 | 4.4 | 1.37 ± 0.29 |
| mattcl-py | input-lanjian | 37.7 ± 1.0 | 36.5 | 41.5 | 19.43 ± 3.64 |
| mattcl-py | input-mattcl | 37.7 ± 0.9 | 36.2 | 40.8 | 19.44 ± 3.63 |
| mattcl-py | input-kcen | 37.9 ± 0.9 | 36.4 | 40.7 | 19.52 ± 3.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1370100</pre>|<pre>818286</pre>|
|input-lanjian|<pre>1433460</pre>|<pre>855082</pre>|
|input-mattcl|<pre>1465968</pre>|<pre>897702</pre>|