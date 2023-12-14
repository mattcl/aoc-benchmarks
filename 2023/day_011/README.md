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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 1.9 | 1.04 ± 0.21 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.1 | 1.05 ± 0.21 |
| mattcl | input-pting | 1.3 ± 3.0 | 0.3 | 43.4 | 1.10 ± 2.49 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.5 | 5.6 | 2.60 ± 0.45 |
| lanjian | input-mattcl | 3.2 ± 0.4 | 2.4 | 5.8 | 2.69 ± 0.50 |
| lanjian | input-lanjian | 3.8 ± 0.4 | 2.9 | 5.9 | 3.15 ± 0.57 |
| lanjian | input-kcen | 3.8 ± 0.4 | 3.0 | 6.4 | 3.18 ± 0.59 |
| mattcl-py | input-lanjian | 55.4 ± 1.0 | 53.5 | 58.1 | 45.93 ± 6.68 |
| mattcl-py | input-kcen | 56.2 ± 1.4 | 54.1 | 61.7 | 46.57 ± 6.82 |
| mattcl-py | input-mattcl | 56.6 ± 1.1 | 54.7 | 59.6 | 46.95 ± 6.84 |
| pting | input-kcen | 58.4 ± 1.9 | 55.6 | 65.1 | 48.41 ± 7.16 |
| pting | input-lanjian | 58.5 ± 1.7 | 55.1 | 63.2 | 48.47 ± 7.14 |
| pting | input-mattcl | 59.0 ± 1.5 | 55.7 | 63.3 | 48.93 ± 7.18 |
| mattcl-py | input-pting | 59.3 ± 2.0 | 57.1 | 70.9 | 49.15 ± 7.29 |
| pting | input-pting | 61.7 ± 1.7 | 57.8 | 65.3 | 51.12 ± 7.52 |
| kcen | input-lanjian | 85.4 ± 1.6 | 82.8 | 89.3 | 70.79 ± 10.31 |
| kcen | input-kcen | 85.6 ± 1.8 | 83.0 | 91.0 | 70.96 ± 10.36 |
| kcen | input-mattcl | 87.0 ± 2.2 | 84.4 | 94.3 | 72.09 ± 10.58 |
| kcen | input-pting | 92.5 ± 7.2 | 88.0 | 129.3 | 76.69 ± 12.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|