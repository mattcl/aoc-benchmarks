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
| kcen | input-kcen | 1.7 ± 0.4 | 0.6 | 2.7 | 1.00 |
| mattcl | input-kcen | 1.8 ± 0.4 | 1.1 | 2.9 | 1.05 ± 0.33 |
| kcen | input-lanjian | 1.8 ± 0.3 | 1.4 | 2.8 | 1.05 ± 0.32 |
| kcen | input-mattcl | 1.8 ± 0.3 | 0.9 | 2.6 | 1.05 ± 0.32 |
| mattcl | input-lanjian | 1.8 ± 0.4 | 1.2 | 2.8 | 1.06 ± 0.33 |
| mattcl | input-mattcl | 1.8 ± 0.3 | 1.2 | 2.8 | 1.07 ± 0.33 |
| lanjian | input-kcen | 2.5 ± 0.3 | 1.7 | 4.4 | 1.49 ± 0.40 |
| lanjian | input-mattcl | 2.6 ± 0.3 | 1.8 | 4.8 | 1.54 ± 0.41 |
| lanjian | input-lanjian | 2.6 ± 0.3 | 1.8 | 5.0 | 1.55 ± 0.41 |
| mattcl-py | input-kcen | 37.3 ± 1.0 | 36.1 | 40.6 | 22.13 ± 5.29 |
| mattcl-py | input-lanjian | 37.4 ± 2.2 | 36.0 | 55.0 | 22.16 ± 5.42 |
| mattcl-py | input-mattcl | 37.4 ± 1.1 | 36.1 | 41.5 | 22.22 ± 5.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1370100</pre>|<pre>818286</pre>|
|input-lanjian|<pre>1433460</pre>|<pre>855082</pre>|
|input-mattcl|<pre>1465968</pre>|<pre>897702</pre>|