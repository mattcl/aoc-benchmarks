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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.9 | 1.01 ± 0.26 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.8 | 1.04 ± 0.26 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 2.2 | 1.07 ± 0.27 |
| lanjian | input-pting | 3.2 ± 0.4 | 2.3 | 6.0 | 2.81 ± 0.60 |
| lanjian | input-mattcl | 3.3 ± 3.3 | 2.2 | 46.2 | 2.93 ± 3.00 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 2.6 | 5.5 | 3.27 ± 0.68 |
| lanjian | input-kcen | 3.7 ± 0.4 | 3.0 | 6.1 | 3.31 ± 0.70 |
| pting | input-lanjian | 52.9 ± 1.4 | 50.3 | 56.0 | 46.79 ± 8.62 |
| pting | input-kcen | 53.3 ± 1.6 | 51.1 | 59.6 | 47.13 ± 8.70 |
| pting | input-mattcl | 53.4 ± 1.3 | 51.2 | 56.0 | 47.16 ± 8.67 |
| mattcl-py | input-lanjian | 54.9 ± 1.4 | 53.3 | 62.2 | 48.56 ± 8.94 |
| mattcl-py | input-kcen | 55.2 ± 1.7 | 53.3 | 64.0 | 48.79 ± 9.02 |
| pting | input-pting | 55.7 ± 1.1 | 53.7 | 59.5 | 49.27 ± 9.03 |
| mattcl-py | input-mattcl | 56.8 ± 2.6 | 54.4 | 67.7 | 50.24 ± 9.45 |
| mattcl-py | input-pting | 58.3 ± 1.7 | 56.5 | 66.2 | 51.51 ± 9.50 |
| kcen | input-kcen | 85.9 ± 2.1 | 83.7 | 94.0 | 75.93 ± 13.97 |
| kcen | input-lanjian | 86.5 ± 3.1 | 82.9 | 97.8 | 76.44 ± 14.20 |
| kcen | input-mattcl | 86.9 ± 1.5 | 84.3 | 89.5 | 76.84 ± 14.07 |
| kcen | input-pting | 91.0 ± 2.5 | 87.9 | 100.0 | 80.42 ± 14.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|