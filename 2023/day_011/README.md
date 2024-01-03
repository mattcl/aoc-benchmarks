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
| mattcl | input-pting | 1.0 ± 0.1 | 0.3 | 1.2 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.4 | 1.4 | 1.01 ± 0.20 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.2 | 1.3 | 1.02 ± 0.20 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.3 | 1.5 | 1.04 ± 0.20 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.2 | 5.8 | 3.21 ± 0.59 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.7 | 4.9 | 3.21 ± 0.55 |
| lanjian | input-lanjian | 3.6 ± 0.5 | 2.8 | 7.8 | 3.70 ± 0.74 |
| lanjian | input-kcen | 3.6 ± 0.4 | 3.1 | 6.5 | 3.76 ± 0.71 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.3 | 18.7 | 15.82 ± 2.38 |
| mattcl-py | input-pting | 15.2 ± 0.6 | 13.9 | 18.0 | 15.83 ± 2.37 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 13.9 | 18.5 | 15.86 ± 2.38 |
| mattcl-py | input-lanjian | 15.6 ± 2.8 | 13.9 | 42.1 | 16.23 ± 3.71 |
| pting | input-kcen | 55.5 ± 1.4 | 52.3 | 59.5 | 57.68 ± 8.47 |
| pting | input-mattcl | 55.7 ± 1.5 | 53.2 | 60.0 | 57.88 ± 8.50 |
| pting | input-lanjian | 56.5 ± 5.9 | 52.9 | 96.9 | 58.70 ± 10.45 |
| pting | input-pting | 58.5 ± 1.8 | 55.9 | 64.4 | 60.87 ± 9.01 |
| kcen | input-lanjian | 88.6 ± 1.7 | 86.0 | 93.8 | 92.14 ± 13.44 |
| kcen | input-kcen | 89.5 ± 1.2 | 87.8 | 92.6 | 93.04 ± 13.51 |
| kcen | input-mattcl | 90.8 ± 2.7 | 86.9 | 101.8 | 94.35 ± 13.92 |
| kcen | input-pting | 94.2 ± 1.8 | 91.7 | 99.3 | 97.97 ± 14.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|