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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.25 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.5 | 1.05 ± 0.23 |
| mattcl | input-lanjian | 1.2 ± 3.2 | 0.2 | 46.2 | 1.09 ± 2.84 |
| lanjian | input-pting | 2.9 ± 0.3 | 2.1 | 5.1 | 2.60 ± 0.53 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.1 | 4.4 | 2.61 ± 0.50 |
| lanjian | input-lanjian | 3.2 ± 0.4 | 2.4 | 5.9 | 2.80 ± 0.57 |
| lanjian | input-kcen | 3.4 ± 0.5 | 2.6 | 6.3 | 2.99 ± 0.69 |
| pting | input-kcen | 53.4 ± 1.4 | 51.2 | 56.7 | 47.09 ± 8.02 |
| pting | input-lanjian | 54.9 ± 2.1 | 52.0 | 61.7 | 48.45 ± 8.35 |
| mattcl-py | input-kcen | 55.6 ± 1.2 | 53.9 | 60.6 | 49.04 ± 8.31 |
| mattcl-py | input-lanjian | 56.2 ± 1.0 | 54.3 | 58.7 | 49.59 ± 8.39 |
| pting | input-pting | 56.7 ± 1.4 | 54.7 | 59.7 | 50.00 ± 8.50 |
| mattcl-py | input-mattcl | 57.5 ± 1.1 | 55.7 | 59.7 | 50.73 ± 8.59 |
| mattcl-py | input-pting | 59.2 ± 1.0 | 57.6 | 61.8 | 52.24 ± 8.84 |
| pting | input-mattcl | 64.1 ± 15.9 | 52.5 | 98.3 | 56.58 ± 16.95 |
| kcen | input-lanjian | 85.2 ± 1.4 | 83.0 | 89.0 | 75.14 ± 12.70 |
| kcen | input-kcen | 86.2 ± 1.8 | 83.9 | 93.0 | 76.07 ± 12.90 |
| kcen | input-mattcl | 89.4 ± 2.1 | 86.4 | 96.3 | 78.90 ± 13.40 |
| kcen | input-pting | 92.9 ± 1.8 | 90.0 | 96.7 | 82.00 ± 13.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|