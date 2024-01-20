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
| mattcl | input-pting | 1.0 ± 0.2 | 0.3 | 1.2 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.5 | 1.02 ± 0.26 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.5 | 1.2 | 1.03 ± 0.24 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.4 | 1.4 | 1.05 ± 0.24 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.8 | 3.17 ± 0.67 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.2 | 5.3 | 3.26 ± 0.67 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 3.0 | 6.0 | 3.58 ± 0.80 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.7 | 6.8 | 3.60 ± 0.81 |
| mattcl-py | input-pting | 15.0 ± 0.5 | 14.1 | 17.8 | 15.57 ± 2.96 |
| mattcl-py | input-mattcl | 15.1 ± 0.6 | 14.4 | 18.3 | 15.68 ± 3.00 |
| mattcl-py | input-kcen | 15.1 ± 0.6 | 13.9 | 18.1 | 15.68 ± 3.00 |
| mattcl-py | input-lanjian | 15.2 ± 0.8 | 14.1 | 18.5 | 15.78 ± 3.06 |
| pting | input-lanjian | 53.5 ± 1.6 | 51.2 | 61.0 | 55.51 ± 10.54 |
| pting | input-kcen | 53.8 ± 1.5 | 51.8 | 59.9 | 55.82 ± 10.57 |
| pting | input-mattcl | 54.1 ± 2.2 | 52.1 | 66.3 | 56.14 ± 10.76 |
| pting | input-pting | 56.0 ± 1.1 | 54.4 | 59.7 | 58.10 ± 10.94 |
| kcen | input-lanjian | 86.0 ± 1.3 | 83.7 | 88.9 | 89.16 ± 16.76 |
| kcen | input-kcen | 87.2 ± 1.7 | 84.4 | 91.9 | 90.46 ± 17.04 |
| kcen | input-mattcl | 87.6 ± 1.4 | 85.3 | 90.8 | 90.85 ± 17.08 |
| kcen | input-pting | 90.8 ± 1.2 | 88.2 | 93.0 | 94.12 ± 17.68 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|