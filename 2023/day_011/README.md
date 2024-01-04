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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.1 | 1.1 | 1.03 ± 0.30 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.31 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.06 ± 0.34 |
| lanjian | input-mattcl | 2.9 ± 0.2 | 2.0 | 4.6 | 3.81 ± 0.93 |
| lanjian | input-pting | 3.0 ± 0.4 | 2.0 | 5.8 | 3.84 ± 1.01 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.6 | 5.0 | 4.36 ± 1.11 |
| lanjian | input-kcen | 3.4 ± 0.6 | 2.9 | 6.1 | 4.39 ± 1.24 |
| mattcl-py | input-pting | 14.9 ± 0.6 | 14.0 | 18.2 | 19.27 ± 4.50 |
| mattcl-py | input-lanjian | 14.9 ± 0.6 | 13.9 | 18.0 | 19.29 ± 4.50 |
| mattcl-py | input-kcen | 15.0 ± 0.6 | 14.0 | 17.6 | 19.39 ± 4.52 |
| mattcl-py | input-mattcl | 15.0 ± 2.4 | 13.6 | 47.1 | 19.40 ± 5.43 |
| pting | input-lanjian | 52.6 ± 1.6 | 50.3 | 58.8 | 68.21 ± 15.82 |
| pting | input-kcen | 53.1 ± 1.3 | 51.0 | 57.4 | 68.76 ± 15.90 |
| pting | input-mattcl | 53.5 ± 3.8 | 50.9 | 79.1 | 69.27 ± 16.67 |
| pting | input-pting | 55.5 ± 1.4 | 53.6 | 59.8 | 71.94 ± 16.64 |
| kcen | input-lanjian | 84.3 ± 1.4 | 82.0 | 87.7 | 109.19 ± 25.17 |
| kcen | input-mattcl | 85.9 ± 1.2 | 82.8 | 89.1 | 111.35 ± 25.66 |
| kcen | input-kcen | 86.4 ± 3.1 | 82.6 | 101.4 | 111.93 ± 26.05 |
| kcen | input-pting | 89.6 ± 1.6 | 87.4 | 94.5 | 116.13 ± 26.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|