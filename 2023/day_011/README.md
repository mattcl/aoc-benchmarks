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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.4 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.5 | 1.8 | 1.03 ± 0.26 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.04 ± 0.25 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.05 ± 0.25 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.2 | 5.9 | 2.82 ± 0.63 |
| lanjian | input-pting | 3.2 ± 0.5 | 2.4 | 5.9 | 2.87 ± 0.67 |
| lanjian | input-lanjian | 3.6 ± 0.4 | 2.9 | 5.9 | 3.25 ± 0.67 |
| lanjian | input-kcen | 3.7 ± 1.9 | 2.7 | 29.6 | 3.34 ± 1.79 |
| mattcl-py | input-lanjian | 55.1 ± 0.9 | 53.7 | 58.5 | 49.56 ± 9.03 |
| mattcl-py | input-kcen | 55.5 ± 1.1 | 53.5 | 58.9 | 49.94 ± 9.12 |
| mattcl-py | input-mattcl | 56.9 ± 1.3 | 54.8 | 59.9 | 51.19 ± 9.37 |
| pting | input-lanjian | 58.4 ± 2.3 | 54.8 | 67.4 | 52.56 ± 9.75 |
| pting | input-kcen | 58.6 ± 2.2 | 55.5 | 67.9 | 52.68 ± 9.77 |
| pting | input-mattcl | 58.6 ± 1.6 | 55.7 | 62.6 | 52.70 ± 9.67 |
| mattcl-py | input-pting | 59.2 ± 2.9 | 56.7 | 78.4 | 53.29 ± 10.02 |
| pting | input-pting | 62.9 ± 6.3 | 57.9 | 99.5 | 56.59 ± 11.71 |
| kcen | input-lanjian | 84.5 ± 1.7 | 82.0 | 90.9 | 76.04 ± 13.88 |
| kcen | input-kcen | 85.1 ± 1.3 | 82.6 | 88.7 | 76.53 ± 13.93 |
| kcen | input-mattcl | 87.1 ± 3.1 | 83.0 | 97.8 | 78.38 ± 14.49 |
| kcen | input-pting | 90.1 ± 2.2 | 87.5 | 97.2 | 81.02 ± 14.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|