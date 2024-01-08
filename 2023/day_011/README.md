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
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.31 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.3 | 1.05 ± 0.32 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.3 | 4.8 | 3.69 ± 0.90 |
| lanjian | input-pting | 3.2 ± 0.4 | 2.4 | 5.7 | 3.87 ± 1.02 |
| lanjian | input-lanjian | 3.6 ± 0.3 | 2.9 | 5.2 | 4.31 ± 1.09 |
| lanjian | input-kcen | 3.7 ± 4.4 | 2.6 | 65.7 | 4.42 ± 5.48 |
| mattcl-py | input-mattcl | 14.9 ± 0.6 | 13.9 | 18.6 | 18.08 ± 4.30 |
| mattcl-py | input-pting | 15.0 ± 0.6 | 13.9 | 18.3 | 18.12 ± 4.31 |
| mattcl-py | input-kcen | 15.1 ± 0.6 | 14.0 | 18.3 | 18.24 ± 4.34 |
| mattcl-py | input-lanjian | 15.2 ± 2.4 | 13.9 | 47.4 | 18.36 ± 5.19 |
| pting | input-lanjian | 54.5 ± 1.6 | 52.4 | 61.6 | 65.92 ± 15.58 |
| pting | input-mattcl | 54.9 ± 1.3 | 52.7 | 58.6 | 66.49 ± 15.67 |
| pting | input-kcen | 55.5 ± 1.6 | 52.8 | 64.3 | 67.13 ± 15.86 |
| pting | input-pting | 58.4 ± 1.9 | 55.3 | 67.4 | 70.66 ± 16.73 |
| kcen | input-lanjian | 84.4 ± 1.7 | 81.7 | 89.7 | 102.15 ± 24.05 |
| kcen | input-mattcl | 86.0 ± 2.5 | 83.0 | 98.8 | 104.05 ± 24.59 |
| kcen | input-kcen | 86.4 ± 1.6 | 83.1 | 89.7 | 104.64 ± 24.62 |
| kcen | input-pting | 89.5 ± 1.4 | 87.3 | 92.5 | 108.39 ± 25.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|