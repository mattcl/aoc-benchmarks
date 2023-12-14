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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.24 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.8 | 1.04 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.23 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.3 | 4.9 | 2.73 ± 0.55 |
| lanjian | input-mattcl | 3.2 ± 0.4 | 2.3 | 5.9 | 2.73 ± 0.57 |
| lanjian | input-lanjian | 3.6 ± 0.4 | 2.9 | 6.0 | 3.10 ± 0.65 |
| lanjian | input-kcen | 3.6 ± 0.5 | 2.9 | 6.9 | 3.12 ± 0.68 |
| pting | input-lanjian | 53.2 ± 1.4 | 51.4 | 58.3 | 45.89 ± 8.02 |
| pting | input-kcen | 53.5 ± 1.2 | 51.7 | 56.7 | 46.18 ± 8.05 |
| pting | input-mattcl | 53.9 ± 2.4 | 51.4 | 68.5 | 46.51 ± 8.30 |
| mattcl-py | input-lanjian | 55.2 ± 1.0 | 53.4 | 58.4 | 47.58 ± 8.27 |
| mattcl-py | input-kcen | 55.2 ± 0.9 | 53.7 | 57.9 | 47.63 ± 8.27 |
| pting | input-pting | 56.9 ± 1.6 | 54.1 | 61.7 | 49.11 ± 8.59 |
| mattcl-py | input-mattcl | 57.0 ± 6.7 | 54.6 | 104.0 | 49.16 ± 10.28 |
| mattcl-py | input-pting | 58.4 ± 1.1 | 56.8 | 62.6 | 50.33 ± 8.74 |
| kcen | input-lanjian | 86.4 ± 5.1 | 83.2 | 114.2 | 74.47 ± 13.59 |
| kcen | input-kcen | 86.8 ± 2.8 | 83.6 | 95.3 | 74.90 ± 13.16 |
| kcen | input-mattcl | 87.2 ± 2.3 | 84.5 | 93.9 | 75.16 ± 13.14 |
| kcen | input-pting | 91.2 ± 2.1 | 87.9 | 96.4 | 78.66 ± 13.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|