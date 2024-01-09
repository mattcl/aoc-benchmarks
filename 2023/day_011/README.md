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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.29 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.5 | 1.3 | 1.07 ± 0.28 |
| lanjian | input-pting | 3.2 ± 0.4 | 2.4 | 6.3 | 3.59 ± 0.93 |
| lanjian | input-mattcl | 3.2 ± 0.5 | 2.4 | 6.2 | 3.64 ± 0.96 |
| lanjian | input-kcen | 3.7 ± 0.3 | 3.1 | 5.3 | 4.21 ± 1.01 |
| lanjian | input-lanjian | 3.8 ± 0.5 | 2.8 | 6.7 | 4.28 ± 1.11 |
| mattcl-py | input-mattcl | 14.9 ± 0.6 | 14.0 | 17.7 | 16.97 ± 3.80 |
| mattcl-py | input-pting | 14.9 ± 0.6 | 13.8 | 17.6 | 16.98 ± 3.81 |
| mattcl-py | input-lanjian | 15.1 ± 0.6 | 13.9 | 17.8 | 17.19 ± 3.87 |
| mattcl-py | input-kcen | 15.1 ± 0.6 | 13.9 | 17.6 | 17.20 ± 3.86 |
| pting | input-mattcl | 54.9 ± 1.0 | 53.0 | 59.1 | 62.40 ± 13.83 |
| pting | input-lanjian | 55.1 ± 1.7 | 52.5 | 60.7 | 62.68 ± 13.99 |
| pting | input-kcen | 55.5 ± 1.7 | 53.0 | 61.0 | 63.11 ± 14.07 |
| pting | input-pting | 57.6 ± 1.5 | 55.1 | 61.3 | 65.51 ± 14.57 |
| kcen | input-lanjian | 85.2 ± 1.9 | 81.9 | 91.3 | 96.83 ± 21.50 |
| kcen | input-kcen | 86.0 ± 1.6 | 83.8 | 92.0 | 97.73 ± 21.67 |
| kcen | input-mattcl | 86.7 ± 1.2 | 84.5 | 88.8 | 98.57 ± 21.82 |
| kcen | input-pting | 90.2 ± 1.7 | 88.1 | 95.5 | 102.59 ± 22.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|