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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.1 | 1.00 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.05 ± 0.31 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.1 | 3.6 | 3.47 ± 0.82 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.1 | 4.3 | 3.57 ± 0.87 |
| lanjian | input-lanjian | 3.4 ± 0.3 | 2.5 | 4.8 | 3.96 ± 0.93 |
| lanjian | input-kcen | 3.4 ± 0.4 | 2.5 | 5.9 | 4.00 ± 0.97 |
| mattcl-py | input-pting | 15.0 ± 0.6 | 14.1 | 17.6 | 17.57 ± 3.89 |
| mattcl-py | input-mattcl | 15.0 ± 0.6 | 14.0 | 18.1 | 17.58 ± 3.91 |
| mattcl-py | input-kcen | 15.1 ± 0.6 | 14.0 | 18.2 | 17.72 ± 3.93 |
| mattcl-py | input-lanjian | 15.2 ± 2.2 | 13.9 | 45.3 | 17.82 ± 4.69 |
| pting | input-lanjian | 52.8 ± 1.2 | 50.9 | 55.7 | 62.07 ± 13.63 |
| pting | input-kcen | 53.0 ± 1.3 | 51.4 | 57.3 | 62.31 ± 13.69 |
| pting | input-mattcl | 53.6 ± 1.5 | 51.6 | 58.8 | 62.98 ± 13.87 |
| pting | input-pting | 56.2 ± 1.5 | 54.0 | 59.4 | 65.97 ± 14.51 |
| kcen | input-lanjian | 88.1 ± 1.8 | 85.2 | 93.4 | 103.47 ± 22.70 |
| kcen | input-mattcl | 88.8 ± 1.3 | 86.8 | 92.1 | 104.36 ± 22.85 |
| kcen | input-kcen | 89.6 ± 2.0 | 87.0 | 96.1 | 105.30 ± 23.12 |
| kcen | input-pting | 93.4 ± 2.0 | 90.7 | 99.8 | 109.70 ± 24.07 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|