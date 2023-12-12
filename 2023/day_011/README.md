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
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.7 | 1.9 | 1.01 ± 0.22 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.7 | 1.8 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.9 | 1.04 ± 0.22 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.1 | 2.43 ± 0.43 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.1 | 3.5 | 2.49 ± 0.42 |
| lanjian | input-kcen | 3.4 ± 0.5 | 2.6 | 5.9 | 2.74 ± 0.59 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.5 | 4.9 | 2.79 ± 0.55 |
| pting | input-lanjian | 52.2 ± 1.4 | 50.5 | 57.4 | 42.40 ± 6.71 |
| pting | input-kcen | 52.9 ± 2.6 | 49.9 | 67.8 | 42.96 ± 7.01 |
| pting | input-mattcl | 53.1 ± 1.0 | 50.8 | 56.2 | 43.16 ± 6.78 |
| mattcl-py | input-kcen | 54.1 ± 1.2 | 51.4 | 57.5 | 43.96 ± 6.92 |
| mattcl-py | input-lanjian | 54.4 ± 1.3 | 52.6 | 57.8 | 44.22 ± 6.98 |
| pting | input-pting | 55.5 ± 1.4 | 53.6 | 60.2 | 45.10 ± 7.11 |
| mattcl-py | input-mattcl | 55.8 ± 1.2 | 53.7 | 59.5 | 45.32 ± 7.13 |
| mattcl-py | input-pting | 58.0 ± 1.6 | 55.7 | 64.9 | 47.10 ± 7.45 |
| kcen | input-lanjian | 84.4 ± 1.7 | 81.8 | 89.1 | 68.56 ± 10.77 |
| kcen | input-kcen | 85.7 ± 6.3 | 82.1 | 120.9 | 69.64 ± 12.01 |
| kcen | input-mattcl | 86.3 ± 2.4 | 83.9 | 95.7 | 70.16 ± 11.10 |
| kcen | input-pting | 91.1 ± 1.4 | 88.3 | 94.1 | 74.04 ± 11.60 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|