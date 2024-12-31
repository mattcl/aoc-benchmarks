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
| mattcl | input-kcen | 1.8 ± 0.4 | 1.2 | 2.8 | 1.00 |
| kcen | input-kcen | 1.8 ± 0.4 | 1.0 | 2.7 | 1.02 ± 0.30 |
| mattcl | input-lanjian | 1.8 ± 0.4 | 0.9 | 2.8 | 1.03 ± 0.30 |
| mattcl | input-mattcl | 1.8 ± 0.4 | 1.0 | 2.8 | 1.03 ± 0.30 |
| kcen | input-mattcl | 1.9 ± 0.4 | 1.2 | 2.8 | 1.09 ± 0.30 |
| kcen | input-lanjian | 1.9 ± 0.3 | 1.1 | 2.8 | 1.09 ± 0.29 |
| lanjian | input-lanjian | 2.6 ± 0.2 | 1.8 | 4.8 | 1.46 ± 0.34 |
| lanjian | input-mattcl | 2.6 ± 0.2 | 1.8 | 4.2 | 1.46 ± 0.33 |
| lanjian | input-kcen | 2.6 ± 0.2 | 2.1 | 4.2 | 1.47 ± 0.33 |
| mattcl-py | input-lanjian | 37.8 ± 1.1 | 35.9 | 40.9 | 21.32 ± 4.50 |
| mattcl-py | input-mattcl | 37.8 ± 1.0 | 36.4 | 40.5 | 21.34 ± 4.50 |
| mattcl-py | input-kcen | 38.0 ± 1.2 | 36.2 | 44.5 | 21.46 ± 4.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1370100</pre>|<pre>818286</pre>|
|input-lanjian|<pre>1433460</pre>|<pre>855082</pre>|
|input-mattcl|<pre>1465968</pre>|<pre>897702</pre>|