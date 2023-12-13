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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.8 | 1.02 ± 0.21 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.8 | 1.04 ± 0.23 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.7 | 1.7 | 1.06 ± 0.20 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.2 | 5.8 | 2.68 ± 0.54 |
| lanjian | input-pting | 3.2 ± 0.4 | 2.4 | 5.7 | 2.73 ± 0.51 |
| lanjian | input-kcen | 3.7 ± 0.4 | 2.9 | 6.2 | 3.19 ± 0.59 |
| lanjian | input-lanjian | 3.8 ± 0.4 | 2.8 | 5.8 | 3.22 ± 0.61 |
| mattcl-py | input-lanjian | 55.2 ± 0.9 | 53.5 | 58.3 | 47.39 ± 7.17 |
| mattcl-py | input-kcen | 55.8 ± 1.1 | 53.9 | 58.8 | 47.90 ± 7.27 |
| mattcl-py | input-mattcl | 56.8 ± 1.0 | 55.4 | 59.0 | 48.74 ± 7.38 |
| pting | input-lanjian | 58.2 ± 1.5 | 55.4 | 63.1 | 49.97 ± 7.63 |
| pting | input-kcen | 58.4 ± 2.2 | 54.8 | 68.4 | 50.14 ± 7.78 |
| mattcl-py | input-pting | 59.4 ± 3.1 | 57.0 | 76.3 | 50.99 ± 8.11 |
| pting | input-mattcl | 59.6 ± 2.7 | 56.2 | 70.8 | 51.17 ± 8.04 |
| pting | input-pting | 61.3 ± 1.5 | 58.3 | 66.4 | 52.59 ± 8.00 |
| kcen | input-lanjian | 85.1 ± 1.8 | 82.1 | 90.6 | 73.02 ± 11.08 |
| kcen | input-mattcl | 86.3 ± 2.3 | 84.1 | 94.4 | 74.09 ± 11.31 |
| kcen | input-kcen | 86.8 ± 3.6 | 83.2 | 98.3 | 74.49 ± 11.63 |
| kcen | input-pting | 90.2 ± 1.3 | 88.0 | 92.7 | 77.38 ± 11.68 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|