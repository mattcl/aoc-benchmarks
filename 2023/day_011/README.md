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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.29 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.3 | 1.3 | 1.03 ± 0.28 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.7 | 1.04 ± 0.29 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.1 | 3.8 | 3.48 ± 0.82 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.4 | 4.2 | 3.52 ± 0.81 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.6 | 6.3 | 4.00 ± 1.03 |
| lanjian | input-kcen | 3.5 ± 0.5 | 2.8 | 6.6 | 4.05 ± 1.05 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 14.1 | 17.9 | 17.73 ± 3.98 |
| mattcl-py | input-mattcl | 15.3 ± 2.0 | 13.9 | 42.5 | 17.88 ± 4.61 |
| mattcl-py | input-kcen | 15.3 ± 0.7 | 14.0 | 19.0 | 17.91 ± 4.05 |
| mattcl-py | input-pting | 15.4 ± 3.2 | 14.2 | 57.9 | 17.95 ± 5.42 |
| pting | input-lanjian | 53.3 ± 1.6 | 51.2 | 59.8 | 62.24 ± 13.92 |
| pting | input-kcen | 53.7 ± 1.3 | 51.6 | 57.1 | 62.74 ± 13.98 |
| pting | input-mattcl | 54.1 ± 1.3 | 51.8 | 57.6 | 63.19 ± 14.08 |
| pting | input-pting | 56.6 ± 1.8 | 54.3 | 66.1 | 66.09 ± 14.79 |
| kcen | input-lanjian | 85.5 ± 1.8 | 83.5 | 92.3 | 99.86 ± 22.22 |
| kcen | input-kcen | 86.2 ± 1.6 | 83.8 | 90.6 | 100.63 ± 22.37 |
| kcen | input-mattcl | 86.6 ± 1.1 | 84.6 | 88.7 | 101.12 ± 22.43 |
| kcen | input-pting | 91.2 ± 2.6 | 88.6 | 99.7 | 106.51 ± 23.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|