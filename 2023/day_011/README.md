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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.8 | 1.00 ± 0.22 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.21 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 2.0 | 1.04 ± 0.21 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.4 | 4.5 | 2.56 ± 0.44 |
| lanjian | input-mattcl | 3.2 ± 0.4 | 2.3 | 5.7 | 2.62 ± 0.53 |
| lanjian | input-kcen | 3.7 ± 0.4 | 2.9 | 6.6 | 3.08 ± 0.59 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 2.9 | 5.2 | 3.08 ± 0.58 |
| mattcl-py | input-lanjian | 55.7 ± 1.3 | 54.2 | 62.0 | 46.21 ± 7.15 |
| mattcl-py | input-kcen | 55.8 ± 1.1 | 54.3 | 58.6 | 46.32 ± 7.14 |
| mattcl-py | input-mattcl | 57.0 ± 1.2 | 55.2 | 61.2 | 47.34 ± 7.31 |
| pting | input-lanjian | 58.1 ± 1.8 | 55.4 | 61.8 | 48.21 ± 7.52 |
| pting | input-kcen | 58.6 ± 1.9 | 56.0 | 66.8 | 48.63 ± 7.60 |
| mattcl-py | input-pting | 58.9 ± 1.1 | 57.2 | 62.2 | 48.85 ± 7.52 |
| pting | input-mattcl | 59.4 ± 2.7 | 55.3 | 72.8 | 49.34 ± 7.86 |
| pting | input-pting | 62.2 ± 1.7 | 59.3 | 66.4 | 51.59 ± 8.01 |
| kcen | input-lanjian | 85.3 ± 2.4 | 82.1 | 92.3 | 70.79 ± 11.01 |
| kcen | input-kcen | 86.2 ± 1.9 | 82.8 | 92.0 | 71.53 ± 11.04 |
| kcen | input-mattcl | 87.7 ± 3.6 | 85.1 | 106.1 | 72.78 ± 11.52 |
| kcen | input-pting | 91.0 ± 1.7 | 88.6 | 96.2 | 75.50 ± 11.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|