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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.4 | 1.6 | 1.01 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 2.6 | 1.02 ± 0.25 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.25 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.3 | 5.7 | 2.67 ± 0.56 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.2 | 5.7 | 2.68 ± 0.57 |
| lanjian | input-lanjian | 3.5 ± 0.3 | 3.0 | 5.0 | 3.06 ± 0.63 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.7 | 6.5 | 3.09 ± 0.68 |
| pting | input-lanjian | 53.5 ± 1.6 | 51.2 | 58.2 | 46.94 ± 8.88 |
| pting | input-kcen | 53.5 ± 1.1 | 51.5 | 55.8 | 46.99 ± 8.83 |
| pting | input-mattcl | 53.9 ± 1.9 | 52.2 | 61.6 | 47.29 ± 9.00 |
| mattcl-py | input-lanjian | 55.0 ± 1.0 | 53.6 | 59.5 | 48.28 ± 9.07 |
| mattcl-py | input-kcen | 55.8 ± 1.8 | 53.5 | 66.3 | 49.00 ± 9.30 |
| mattcl-py | input-mattcl | 56.3 ± 1.2 | 54.6 | 59.8 | 49.37 ± 9.29 |
| pting | input-pting | 56.7 ± 3.2 | 54.0 | 77.4 | 49.79 ± 9.72 |
| mattcl-py | input-pting | 58.3 ± 1.0 | 56.8 | 60.9 | 51.21 ± 9.61 |
| kcen | input-lanjian | 85.6 ± 4.6 | 82.4 | 107.9 | 75.10 ± 14.60 |
| kcen | input-kcen | 86.3 ± 1.8 | 83.8 | 92.1 | 75.75 ± 14.24 |
| kcen | input-mattcl | 86.7 ± 1.5 | 83.9 | 92.1 | 76.06 ± 14.28 |
| kcen | input-pting | 90.8 ± 1.8 | 88.3 | 97.2 | 79.67 ± 14.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|