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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.6 | 1.03 ± 0.26 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.9 | 1.08 ± 0.29 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.10 ± 0.26 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.0 | 5.1 | 2.74 ± 0.61 |
| lanjian | input-pting | 3.0 ± 0.4 | 2.1 | 5.5 | 2.79 ± 0.65 |
| lanjian | input-kcen | 3.4 ± 0.6 | 2.7 | 6.0 | 3.14 ± 0.81 |
| lanjian | input-lanjian | 3.4 ± 0.5 | 2.8 | 6.1 | 3.19 ± 0.78 |
| pting | input-kcen | 52.9 ± 2.0 | 50.1 | 59.7 | 49.06 ± 9.70 |
| pting | input-lanjian | 52.9 ± 3.1 | 50.5 | 74.2 | 49.10 ± 9.96 |
| pting | input-mattcl | 54.5 ± 6.0 | 51.2 | 96.5 | 50.53 ± 11.27 |
| mattcl-py | input-lanjian | 54.5 ± 1.2 | 51.9 | 57.4 | 50.56 ± 9.89 |
| mattcl-py | input-kcen | 54.5 ± 1.2 | 52.4 | 57.2 | 50.56 ± 9.89 |
| pting | input-pting | 55.9 ± 1.1 | 53.6 | 59.0 | 51.87 ± 10.13 |
| mattcl-py | input-mattcl | 56.2 ± 1.5 | 53.9 | 63.0 | 52.15 ± 10.23 |
| mattcl-py | input-pting | 58.4 ± 1.1 | 56.2 | 61.8 | 54.23 ± 10.58 |
| kcen | input-lanjian | 84.4 ± 1.4 | 81.7 | 86.9 | 78.36 ± 15.27 |
| kcen | input-kcen | 84.9 ± 1.8 | 81.9 | 91.3 | 78.79 ± 15.39 |
| kcen | input-mattcl | 86.3 ± 1.8 | 84.2 | 90.4 | 80.10 ± 15.65 |
| kcen | input-pting | 91.5 ± 2.7 | 88.6 | 103.1 | 84.93 ± 16.69 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|