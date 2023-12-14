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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.23 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.4 | 1.7 | 1.04 ± 0.24 |
| mattcl | input-kcen | 1.3 ± 0.1 | 0.7 | 1.8 | 1.05 ± 0.23 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.3 | 2.58 ± 0.55 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.4 | 4.8 | 2.62 ± 0.53 |
| lanjian | input-lanjian | 3.8 ± 0.5 | 2.9 | 6.1 | 3.12 ± 0.68 |
| lanjian | input-kcen | 3.8 ± 0.4 | 2.9 | 5.6 | 3.13 ± 0.68 |
| mattcl-py | input-lanjian | 55.8 ± 1.5 | 53.7 | 63.6 | 45.95 ± 8.54 |
| mattcl-py | input-kcen | 55.8 ± 0.9 | 54.5 | 59.2 | 45.95 ± 8.48 |
| mattcl-py | input-mattcl | 57.2 ± 1.3 | 55.1 | 61.9 | 47.04 ± 8.71 |
| pting | input-lanjian | 57.8 ± 1.3 | 55.4 | 60.5 | 47.61 ± 8.81 |
| pting | input-kcen | 58.5 ± 1.3 | 55.3 | 61.1 | 48.18 ± 8.92 |
| mattcl-py | input-pting | 58.7 ± 1.1 | 56.9 | 61.2 | 48.34 ± 8.93 |
| pting | input-mattcl | 59.1 ± 1.9 | 55.6 | 63.9 | 48.66 ± 9.08 |
| pting | input-pting | 61.8 ± 1.9 | 58.8 | 66.6 | 50.85 ± 9.47 |
| kcen | input-lanjian | 84.7 ± 1.3 | 82.5 | 88.5 | 69.72 ± 12.86 |
| kcen | input-kcen | 86.3 ± 3.0 | 83.6 | 97.7 | 71.02 ± 13.29 |
| kcen | input-mattcl | 87.5 ± 2.6 | 84.0 | 95.9 | 71.98 ± 13.40 |
| kcen | input-pting | 90.5 ± 1.7 | 87.4 | 95.3 | 74.51 ± 13.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|