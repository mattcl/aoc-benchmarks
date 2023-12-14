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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.9 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.9 | 1.03 ± 0.21 |
| lanjian | input-mattcl | 3.2 ± 0.2 | 2.8 | 5.8 | 2.60 ± 0.45 |
| lanjian | input-pting | 3.2 ± 0.2 | 2.6 | 4.6 | 2.61 ± 0.44 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 3.0 | 5.3 | 3.03 ± 0.57 |
| lanjian | input-kcen | 3.8 ± 0.4 | 2.9 | 6.2 | 3.09 ± 0.59 |
| pting | input-lanjian | 53.0 ± 1.5 | 50.5 | 56.6 | 43.52 ± 6.92 |
| pting | input-kcen | 53.5 ± 2.0 | 51.4 | 61.7 | 43.94 ± 7.07 |
| pting | input-mattcl | 53.8 ± 2.0 | 51.7 | 64.9 | 44.19 ± 7.12 |
| mattcl-py | input-lanjian | 54.8 ± 1.0 | 53.3 | 58.1 | 44.97 ± 7.09 |
| mattcl-py | input-kcen | 55.4 ± 0.9 | 53.9 | 57.3 | 45.45 ± 7.16 |
| pting | input-pting | 56.0 ± 1.5 | 54.2 | 62.4 | 45.99 ± 7.31 |
| mattcl-py | input-mattcl | 56.3 ± 1.0 | 54.7 | 59.2 | 46.24 ± 7.29 |
| mattcl-py | input-pting | 58.5 ± 1.6 | 56.7 | 63.9 | 48.06 ± 7.64 |
| kcen | input-lanjian | 85.1 ± 1.7 | 83.1 | 92.3 | 69.90 ± 11.04 |
| kcen | input-kcen | 85.2 ± 1.3 | 82.9 | 87.8 | 69.98 ± 11.01 |
| kcen | input-mattcl | 85.7 ± 1.3 | 83.7 | 88.4 | 70.38 ± 11.08 |
| kcen | input-pting | 90.7 ± 2.2 | 87.3 | 96.4 | 74.44 ± 11.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|