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
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.8 | 1.02 ± 0.20 |
| mattcl | input-pting | 1.3 ± 0.1 | 0.7 | 1.7 | 1.03 ± 0.18 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 1.8 | 1.04 ± 0.19 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.3 | 5.2 | 2.42 ± 0.39 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.2 | 5.5 | 2.51 ± 0.44 |
| lanjian | input-kcen | 3.4 ± 0.5 | 2.7 | 6.8 | 2.70 ± 0.55 |
| lanjian | input-lanjian | 3.5 ± 0.5 | 2.7 | 6.3 | 2.77 ± 0.54 |
| pting | input-lanjian | 53.6 ± 1.5 | 51.4 | 58.5 | 42.82 ± 5.95 |
| pting | input-mattcl | 54.0 ± 1.2 | 52.1 | 57.1 | 43.10 ± 5.94 |
| pting | input-kcen | 54.0 ± 1.5 | 51.9 | 60.9 | 43.17 ± 5.99 |
| mattcl-py | input-lanjian | 55.4 ± 1.1 | 53.8 | 58.7 | 44.22 ± 6.07 |
| pting | input-pting | 56.4 ± 1.5 | 54.5 | 64.7 | 45.05 ± 6.25 |
| mattcl-py | input-mattcl | 56.6 ± 2.6 | 54.9 | 73.6 | 45.21 ± 6.50 |
| mattcl-py | input-kcen | 56.7 ± 2.6 | 54.8 | 71.2 | 45.31 ± 6.50 |
| mattcl-py | input-pting | 58.6 ± 1.0 | 56.9 | 62.3 | 46.82 ± 6.42 |
| kcen | input-lanjian | 86.0 ± 1.7 | 83.5 | 91.4 | 68.73 ± 9.45 |
| kcen | input-kcen | 87.0 ± 1.4 | 85.1 | 90.2 | 69.49 ± 9.51 |
| kcen | input-mattcl | 87.2 ± 1.6 | 84.1 | 93.4 | 69.62 ± 9.56 |
| kcen | input-pting | 90.5 ± 1.4 | 88.4 | 94.1 | 72.29 ± 9.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|