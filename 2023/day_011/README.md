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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.2 | 1.7 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 ± 0.24 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 2.0 | 1.02 ± 0.25 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.6 | 1.6 | 1.03 ± 0.21 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.1 | 5.6 | 2.70 ± 0.52 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.3 | 5.4 | 2.70 ± 0.51 |
| lanjian | input-lanjian | 3.5 ± 0.3 | 2.8 | 4.9 | 3.10 ± 0.58 |
| lanjian | input-kcen | 3.6 ± 3.4 | 2.4 | 51.4 | 3.25 ± 3.11 |
| pting | input-lanjian | 53.2 ± 1.4 | 51.0 | 56.9 | 47.38 ± 8.13 |
| pting | input-mattcl | 53.4 ± 1.8 | 51.4 | 61.0 | 47.61 ± 8.22 |
| pting | input-kcen | 53.4 ± 1.5 | 51.6 | 58.5 | 47.61 ± 8.17 |
| mattcl-py | input-lanjian | 55.0 ± 1.3 | 53.2 | 61.3 | 49.01 ± 8.39 |
| mattcl-py | input-kcen | 55.3 ± 1.1 | 53.9 | 58.8 | 49.29 ± 8.41 |
| mattcl-py | input-mattcl | 56.3 ± 1.5 | 54.3 | 62.1 | 50.19 ± 8.61 |
| pting | input-pting | 56.4 ± 2.4 | 54.2 | 65.8 | 50.28 ± 8.78 |
| mattcl-py | input-pting | 58.0 ± 1.3 | 55.6 | 61.9 | 51.70 ± 8.84 |
| kcen | input-lanjian | 84.8 ± 1.9 | 82.2 | 91.7 | 75.57 ± 12.92 |
| kcen | input-mattcl | 86.4 ± 2.0 | 84.0 | 92.6 | 76.99 ± 13.16 |
| kcen | input-kcen | 86.6 ± 5.9 | 82.6 | 118.9 | 77.18 ± 14.09 |
| kcen | input-pting | 89.9 ± 1.9 | 87.8 | 97.6 | 80.07 ± 13.68 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|