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
| mattcl | input-pting | 1.1 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.6 | 1.3 | 1.00 ± 0.25 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.2 | 1.3 | 1.01 ± 0.26 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.6 | 1.02 ± 0.26 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 4.4 | 2.86 ± 0.65 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.4 | 5.5 | 2.90 ± 0.69 |
| lanjian | input-lanjian | 3.6 ± 0.4 | 2.8 | 6.6 | 3.41 ± 0.81 |
| lanjian | input-kcen | 3.7 ± 0.4 | 2.9 | 5.2 | 3.43 ± 0.80 |
| mattcl-py | input-lanjian | 55.8 ± 2.3 | 53.9 | 69.6 | 52.40 ± 11.11 |
| mattcl-py | input-kcen | 55.8 ± 1.0 | 54.2 | 58.2 | 52.40 ± 10.94 |
| mattcl-py | input-mattcl | 57.2 ± 1.2 | 55.0 | 61.2 | 53.75 ± 11.23 |
| pting | input-kcen | 58.4 ± 1.8 | 55.1 | 65.9 | 54.82 ± 11.53 |
| pting | input-lanjian | 58.5 ± 1.8 | 55.0 | 65.3 | 54.95 ± 11.56 |
| mattcl-py | input-pting | 58.8 ± 1.0 | 57.4 | 61.5 | 55.28 ± 11.53 |
| pting | input-mattcl | 59.2 ± 3.0 | 55.1 | 72.3 | 55.59 ± 11.90 |
| pting | input-pting | 61.8 ± 2.2 | 58.0 | 69.2 | 58.04 ± 12.24 |
| kcen | input-lanjian | 86.0 ± 2.9 | 82.7 | 93.9 | 80.77 ± 17.01 |
| kcen | input-kcen | 86.1 ± 2.2 | 83.6 | 94.7 | 80.89 ± 16.94 |
| kcen | input-mattcl | 87.5 ± 2.8 | 84.7 | 99.7 | 82.17 ± 17.28 |
| kcen | input-pting | 90.5 ± 1.7 | 88.4 | 96.3 | 84.99 ± 17.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|