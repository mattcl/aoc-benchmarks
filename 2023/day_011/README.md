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
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.8 | 1.03 ± 0.25 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.25 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.05 ± 0.24 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 2.1 | 4.0 | 2.54 ± 0.54 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.1 | 4.8 | 2.68 ± 0.55 |
| lanjian | input-kcen | 3.3 ± 0.4 | 2.6 | 5.9 | 2.92 ± 0.67 |
| lanjian | input-lanjian | 3.4 ± 0.5 | 2.6 | 6.5 | 3.01 ± 0.72 |
| pting | input-lanjian | 53.2 ± 1.2 | 51.2 | 56.5 | 47.04 ± 8.95 |
| pting | input-mattcl | 53.5 ± 1.2 | 51.7 | 56.4 | 47.38 ± 9.01 |
| pting | input-kcen | 53.8 ± 2.9 | 51.3 | 71.8 | 47.62 ± 9.34 |
| mattcl-py | input-lanjian | 55.0 ± 1.0 | 53.4 | 58.1 | 48.69 ± 9.24 |
| pting | input-pting | 56.0 ± 1.4 | 54.5 | 63.2 | 49.59 ± 9.44 |
| mattcl-py | input-mattcl | 56.2 ± 1.2 | 54.8 | 59.7 | 49.77 ± 9.45 |
| mattcl-py | input-kcen | 56.3 ± 5.0 | 53.4 | 89.1 | 49.83 ± 10.39 |
| mattcl-py | input-pting | 58.5 ± 1.1 | 56.9 | 61.1 | 51.79 ± 9.83 |
| kcen | input-lanjian | 84.8 ± 1.1 | 82.4 | 87.5 | 75.09 ± 14.22 |
| kcen | input-kcen | 86.4 ± 2.0 | 83.8 | 94.6 | 76.46 ± 14.55 |
| kcen | input-mattcl | 87.0 ± 1.7 | 85.0 | 93.9 | 77.04 ± 14.63 |
| kcen | input-pting | 90.9 ± 1.8 | 88.5 | 95.7 | 80.47 ± 15.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|