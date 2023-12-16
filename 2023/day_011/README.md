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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.2 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.2 | 1.4 | 1.03 ± 0.29 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.2 | 1.4 | 1.04 ± 0.29 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.2 | 1.1 | 1.07 ± 0.28 |
| lanjian | input-mattcl | 2.9 ± 0.4 | 2.3 | 5.0 | 3.57 ± 0.91 |
| lanjian | input-pting | 3.0 ± 0.4 | 2.1 | 5.9 | 3.65 ± 0.94 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.6 | 5.8 | 4.12 ± 1.06 |
| lanjian | input-kcen | 3.4 ± 0.4 | 2.6 | 5.5 | 4.19 ± 1.05 |
| mattcl-py | input-mattcl | 14.9 ± 0.6 | 13.9 | 17.8 | 18.28 ± 4.15 |
| mattcl-py | input-lanjian | 15.0 ± 0.7 | 14.0 | 18.2 | 18.35 ± 4.18 |
| mattcl-py | input-pting | 15.0 ± 0.7 | 14.0 | 17.7 | 18.36 ± 4.19 |
| mattcl-py | input-kcen | 15.2 ± 0.8 | 14.3 | 18.5 | 18.57 ± 4.25 |
| pting | input-lanjian | 52.7 ± 1.7 | 50.6 | 59.1 | 64.50 ± 14.55 |
| pting | input-kcen | 53.4 ± 2.1 | 50.8 | 63.9 | 65.34 ± 14.81 |
| pting | input-mattcl | 53.6 ± 4.3 | 51.5 | 83.7 | 65.57 ± 15.55 |
| pting | input-pting | 56.8 ± 4.8 | 53.8 | 83.8 | 69.46 ± 16.56 |
| kcen | input-mattcl | 88.9 ± 1.3 | 86.8 | 92.0 | 108.75 ± 24.32 |
| kcen | input-lanjian | 89.1 ± 7.8 | 84.7 | 131.7 | 109.01 ± 26.15 |
| kcen | input-kcen | 89.9 ± 2.2 | 86.4 | 94.5 | 109.99 ± 24.70 |
| kcen | input-pting | 93.7 ± 3.2 | 89.4 | 107.3 | 114.71 ± 25.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|