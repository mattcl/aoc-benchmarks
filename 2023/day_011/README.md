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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.6 | 1.04 ± 0.23 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.05 ± 0.24 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 2.1 | 1.07 ± 0.27 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.1 | 4.0 | 2.61 ± 0.51 |
| lanjian | input-pting | 3.0 ± 0.4 | 2.1 | 5.7 | 2.65 ± 0.59 |
| lanjian | input-kcen | 3.4 ± 0.4 | 2.7 | 4.9 | 2.93 ± 0.63 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.9 | 5.8 | 3.02 ± 0.64 |
| pting | input-kcen | 52.7 ± 1.8 | 50.4 | 63.0 | 45.87 ± 8.45 |
| pting | input-lanjian | 52.8 ± 2.7 | 50.6 | 70.9 | 45.95 ± 8.63 |
| pting | input-mattcl | 53.7 ± 1.7 | 51.0 | 59.6 | 46.76 ± 8.58 |
| mattcl-py | input-kcen | 54.4 ± 1.5 | 51.8 | 59.3 | 47.33 ± 8.66 |
| mattcl-py | input-lanjian | 54.4 ± 1.6 | 52.2 | 62.6 | 47.41 ± 8.69 |
| mattcl-py | input-mattcl | 55.5 ± 0.9 | 53.9 | 58.2 | 48.35 ± 8.78 |
| pting | input-pting | 56.5 ± 3.7 | 54.3 | 81.0 | 49.19 ± 9.48 |
| mattcl-py | input-pting | 58.9 ± 3.4 | 55.9 | 77.7 | 51.25 ± 9.74 |
| kcen | input-lanjian | 84.2 ± 2.2 | 81.0 | 91.8 | 73.28 ± 13.39 |
| kcen | input-kcen | 85.0 ± 4.8 | 81.7 | 108.7 | 74.02 ± 14.03 |
| kcen | input-mattcl | 86.4 ± 1.9 | 83.1 | 90.8 | 75.24 ± 13.71 |
| kcen | input-pting | 91.2 ± 2.7 | 87.6 | 102.0 | 79.38 ± 14.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|