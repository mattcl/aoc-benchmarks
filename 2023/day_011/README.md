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
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.1 | 1.05 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.4 | 1.1 | 1.07 ± 0.29 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.6 | 5.6 | 3.66 ± 0.90 |
| lanjian | input-pting | 3.3 ± 0.5 | 2.4 | 5.6 | 3.99 ± 1.07 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 2.9 | 5.9 | 4.43 ± 1.13 |
| lanjian | input-kcen | 3.7 ± 0.4 | 2.8 | 6.7 | 4.49 ± 1.13 |
| mattcl-py | input-mattcl | 15.1 ± 0.6 | 13.8 | 18.3 | 18.18 ± 4.20 |
| mattcl-py | input-pting | 15.1 ± 0.6 | 13.8 | 18.7 | 18.21 ± 4.22 |
| mattcl-py | input-lanjian | 15.1 ± 0.6 | 14.1 | 18.2 | 18.27 ± 4.22 |
| mattcl-py | input-kcen | 15.2 ± 0.6 | 14.4 | 18.0 | 18.28 ± 4.21 |
| pting | input-lanjian | 53.2 ± 1.2 | 51.6 | 56.8 | 64.11 ± 14.66 |
| pting | input-mattcl | 53.5 ± 0.9 | 51.7 | 55.9 | 64.52 ± 14.73 |
| pting | input-kcen | 54.3 ± 2.4 | 52.0 | 69.0 | 65.46 ± 15.18 |
| pting | input-pting | 56.3 ± 1.5 | 54.4 | 61.1 | 67.89 ± 15.56 |
| kcen | input-lanjian | 86.1 ± 2.5 | 82.7 | 92.0 | 103.81 ± 23.82 |
| kcen | input-mattcl | 86.7 ± 1.7 | 83.9 | 91.0 | 104.55 ± 23.88 |
| kcen | input-kcen | 87.5 ± 2.1 | 84.9 | 95.7 | 105.48 ± 24.14 |
| kcen | input-pting | 90.0 ± 1.1 | 88.4 | 93.5 | 108.53 ± 24.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|