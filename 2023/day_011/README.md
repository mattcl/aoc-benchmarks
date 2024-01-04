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
| mattcl | input-pting | 0.9 ± 0.3 | 0.2 | 1.3 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.6 | 1.07 ± 0.42 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.11 ± 0.42 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.7 | 1.13 ± 0.43 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.3 | 3.5 | 3.62 ± 1.14 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.2 | 5.7 | 3.64 ± 1.17 |
| lanjian | input-kcen | 3.5 ± 0.3 | 2.7 | 4.1 | 4.08 ± 1.30 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.9 | 6.5 | 4.10 ± 1.35 |
| mattcl-py | input-kcen | 15.6 ± 0.4 | 14.7 | 17.9 | 18.20 ± 5.66 |
| mattcl-py | input-pting | 16.0 ± 0.5 | 14.5 | 18.3 | 18.65 ± 5.81 |
| mattcl-py | input-lanjian | 16.0 ± 0.6 | 14.7 | 18.5 | 18.73 ± 5.85 |
| mattcl-py | input-mattcl | 16.2 ± 0.6 | 15.0 | 19.5 | 18.90 ± 5.90 |
| pting | input-kcen | 54.7 ± 1.2 | 52.8 | 59.8 | 63.88 ± 19.84 |
| pting | input-lanjian | 54.7 ± 2.0 | 52.2 | 67.9 | 63.97 ± 19.96 |
| pting | input-mattcl | 55.8 ± 2.6 | 52.5 | 71.7 | 65.18 ± 20.42 |
| pting | input-pting | 57.5 ± 1.8 | 54.7 | 65.4 | 67.19 ± 20.92 |
| kcen | input-lanjian | 89.2 ± 1.6 | 86.9 | 93.7 | 104.29 ± 32.36 |
| kcen | input-kcen | 91.9 ± 3.6 | 88.8 | 109.1 | 107.38 ± 33.53 |
| kcen | input-mattcl | 92.3 ± 1.4 | 88.4 | 95.1 | 107.86 ± 33.45 |
| kcen | input-pting | 96.4 ± 1.7 | 94.1 | 103.1 | 112.67 ± 34.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|