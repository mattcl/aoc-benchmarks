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
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.5 | 1.02 ± 0.29 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.1 | 1.03 ± 0.28 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.0 | 1.04 ± 0.27 |
| lanjian | input-mattcl | 3.0 ± 0.4 | 2.3 | 5.8 | 3.58 ± 0.84 |
| lanjian | input-pting | 3.2 ± 0.5 | 2.3 | 5.9 | 3.73 ± 0.96 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 3.0 | 6.8 | 4.29 ± 1.00 |
| lanjian | input-kcen | 3.7 ± 0.4 | 2.9 | 5.9 | 4.35 ± 1.02 |
| mattcl-py | input-pting | 15.1 ± 0.6 | 13.8 | 18.3 | 17.72 ± 3.64 |
| mattcl-py | input-lanjian | 15.2 ± 0.7 | 14.0 | 18.2 | 17.81 ± 3.70 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.3 | 18.4 | 17.83 ± 3.67 |
| mattcl-py | input-kcen | 15.4 ± 0.8 | 14.2 | 18.6 | 18.06 ± 3.76 |
| pting | input-lanjian | 53.0 ± 1.5 | 51.1 | 58.0 | 62.26 ± 12.68 |
| pting | input-kcen | 53.7 ± 1.3 | 51.7 | 56.8 | 63.07 ± 12.81 |
| pting | input-mattcl | 53.8 ± 1.3 | 51.9 | 57.8 | 63.19 ± 12.84 |
| pting | input-pting | 56.6 ± 3.1 | 54.2 | 75.7 | 66.42 ± 13.88 |
| kcen | input-lanjian | 84.8 ± 1.2 | 82.9 | 87.9 | 99.56 ± 20.13 |
| kcen | input-mattcl | 87.0 ± 1.7 | 84.2 | 92.7 | 102.18 ± 20.70 |
| kcen | input-kcen | 87.2 ± 3.5 | 84.6 | 105.3 | 102.46 ± 21.08 |
| kcen | input-pting | 89.9 ± 1.5 | 87.5 | 92.8 | 105.64 ± 21.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|