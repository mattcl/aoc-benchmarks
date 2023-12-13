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
| mattcl | input-mattcl | 1.1 ± 2.1 | 0.3 | 30.4 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.07 ± 2.04 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 2.2 | 1.08 ± 2.06 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.09 ± 2.07 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.9 | 2.79 ± 5.31 |
| lanjian | input-pting | 3.3 ± 0.5 | 2.4 | 5.6 | 3.00 ± 5.72 |
| lanjian | input-lanjian | 3.7 ± 0.5 | 3.0 | 7.0 | 3.35 ± 6.38 |
| lanjian | input-kcen | 3.7 ± 0.4 | 2.9 | 5.9 | 3.36 ± 6.39 |
| mattcl-py | input-kcen | 55.8 ± 1.1 | 53.9 | 58.2 | 50.35 ± 95.71 |
| mattcl-py | input-lanjian | 55.8 ± 2.2 | 53.5 | 68.5 | 50.38 ± 95.77 |
| mattcl-py | input-mattcl | 57.0 ± 1.1 | 54.7 | 61.1 | 51.42 ± 97.74 |
| pting | input-lanjian | 58.2 ± 1.8 | 55.7 | 63.9 | 52.58 ± 99.95 |
| pting | input-mattcl | 58.9 ± 1.8 | 55.3 | 62.4 | 53.20 ± 101.13 |
| mattcl-py | input-pting | 59.2 ± 1.4 | 56.7 | 67.0 | 53.45 ± 101.59 |
| pting | input-kcen | 60.4 ± 7.2 | 56.5 | 95.5 | 54.53 ± 103.84 |
| pting | input-pting | 61.8 ± 1.6 | 58.4 | 65.8 | 55.81 ± 106.08 |
| kcen | input-lanjian | 84.7 ± 1.5 | 82.7 | 88.9 | 76.47 ± 145.35 |
| kcen | input-kcen | 86.0 ± 2.0 | 82.9 | 91.7 | 77.62 ± 147.54 |
| kcen | input-mattcl | 87.6 ± 3.5 | 84.2 | 102.2 | 79.07 ± 150.32 |
| kcen | input-pting | 90.2 ± 2.3 | 87.5 | 99.8 | 81.47 ± 154.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|