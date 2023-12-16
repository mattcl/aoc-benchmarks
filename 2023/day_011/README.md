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
| mattcl | input-pting | 0.8 ± 0.2 | 0.3 | 1.2 | 1.00 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.30 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.05 ± 0.29 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.4 | 1.0 | 1.06 ± 0.26 |
| lanjian | input-mattcl | 2.9 ± 0.4 | 2.0 | 5.3 | 3.70 ± 0.92 |
| lanjian | input-pting | 2.9 ± 0.3 | 2.0 | 4.1 | 3.74 ± 0.85 |
| lanjian | input-kcen | 3.3 ± 0.4 | 2.6 | 5.2 | 4.26 ± 0.98 |
| lanjian | input-lanjian | 3.4 ± 0.5 | 2.5 | 6.1 | 4.28 ± 1.07 |
| mattcl-py | input-mattcl | 14.9 ± 0.6 | 13.9 | 18.2 | 19.00 ± 3.96 |
| mattcl-py | input-lanjian | 14.9 ± 0.6 | 13.9 | 18.2 | 19.02 ± 3.95 |
| mattcl-py | input-pting | 15.0 ± 0.7 | 14.1 | 18.1 | 19.08 ± 4.01 |
| mattcl-py | input-kcen | 15.0 ± 0.6 | 13.8 | 18.0 | 19.16 ± 3.98 |
| pting | input-lanjian | 53.1 ± 2.8 | 51.0 | 70.1 | 67.71 ± 14.29 |
| pting | input-kcen | 53.3 ± 1.6 | 51.1 | 61.2 | 67.89 ± 14.03 |
| pting | input-mattcl | 53.4 ± 1.1 | 51.6 | 55.7 | 68.09 ± 13.99 |
| pting | input-pting | 55.7 ± 1.6 | 54.0 | 63.9 | 70.95 ± 14.65 |
| kcen | input-lanjian | 87.2 ± 1.6 | 84.1 | 90.1 | 111.21 ± 22.81 |
| kcen | input-mattcl | 88.8 ± 1.5 | 87.2 | 96.0 | 113.15 ± 23.21 |
| kcen | input-kcen | 89.0 ± 1.7 | 86.7 | 92.5 | 113.45 ± 23.29 |
| kcen | input-pting | 92.6 ± 1.3 | 90.0 | 94.6 | 118.04 ± 24.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|