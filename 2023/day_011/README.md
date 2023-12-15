# Day 11 benchmarks

[link to problem](https://adventofcode.com/2023/day/11)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 11)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.01 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.9 | 1.05 ± 0.21 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.9 | 1.06 ± 0.23 |
| lanjian | input-mattcl | 3.2 ± 0.4 | 2.4 | 6.2 | 2.71 ± 0.55 |
| lanjian | input-pting | 3.4 ± 0.5 | 2.5 | 5.6 | 2.89 ± 0.60 |
| lanjian | input-lanjian | 3.8 ± 0.6 | 3.0 | 7.4 | 3.30 ± 0.70 |
| lanjian | input-kcen | 3.9 ± 0.6 | 2.8 | 6.6 | 3.33 ± 0.70 |
| pting | input-lanjian | 52.8 ± 1.2 | 51.1 | 56.3 | 45.35 ± 6.82 |
| pting | input-kcen | 53.6 ± 2.0 | 51.4 | 61.1 | 46.09 ± 7.07 |
| pting | input-mattcl | 53.8 ± 2.3 | 51.4 | 66.8 | 46.28 ± 7.17 |
| mattcl-py | input-lanjian | 54.9 ± 1.3 | 53.4 | 58.3 | 47.20 ± 7.10 |
| mattcl-py | input-kcen | 55.3 ± 1.3 | 53.9 | 61.8 | 47.55 ± 7.15 |
| mattcl-py | input-mattcl | 55.9 ± 1.1 | 54.4 | 59.6 | 48.05 ± 7.20 |
| pting | input-pting | 56.0 ± 1.6 | 53.5 | 61.1 | 48.13 ± 7.29 |
| mattcl-py | input-pting | 58.5 ± 2.2 | 56.4 | 71.2 | 50.28 ± 7.70 |
| kcen | input-lanjian | 84.3 ± 1.1 | 82.5 | 86.4 | 72.43 ± 10.81 |
| kcen | input-kcen | 85.3 ± 1.3 | 82.7 | 88.5 | 73.31 ± 10.96 |
| kcen | input-mattcl | 86.6 ± 1.9 | 84.5 | 92.2 | 74.45 ± 11.19 |
| kcen | input-pting | 90.2 ± 1.6 | 88.3 | 95.2 | 77.57 ± 11.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|