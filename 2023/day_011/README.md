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
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.31 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 1.9 | 4.0 | 3.46 ± 0.88 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 5.4 | 3.60 ± 0.92 |
| lanjian | input-kcen | 3.2 ± 0.4 | 2.5 | 6.6 | 3.81 ± 1.01 |
| lanjian | input-lanjian | 3.4 ± 0.5 | 2.6 | 6.1 | 4.00 ± 1.10 |
| mattcl-py | input-mattcl | 14.9 ± 0.5 | 13.9 | 17.8 | 17.57 ± 4.19 |
| mattcl-py | input-pting | 14.9 ± 0.6 | 13.8 | 18.2 | 17.60 ± 4.21 |
| mattcl-py | input-lanjian | 14.9 ± 0.5 | 13.9 | 17.6 | 17.63 ± 4.20 |
| mattcl-py | input-kcen | 15.1 ± 0.6 | 14.0 | 18.3 | 17.83 ± 4.26 |
| pting | input-lanjian | 53.0 ± 1.7 | 50.6 | 58.7 | 62.67 ± 14.91 |
| pting | input-kcen | 53.0 ± 1.3 | 51.2 | 57.2 | 62.70 ± 14.87 |
| pting | input-mattcl | 53.0 ± 1.5 | 51.4 | 58.5 | 62.71 ± 14.90 |
| pting | input-pting | 56.2 ± 1.4 | 54.2 | 60.7 | 66.49 ± 15.76 |
| kcen | input-lanjian | 87.8 ± 1.4 | 84.5 | 91.1 | 103.91 ± 24.55 |
| kcen | input-mattcl | 89.0 ± 1.4 | 86.3 | 92.4 | 105.31 ± 24.88 |
| kcen | input-kcen | 89.6 ± 2.6 | 86.8 | 96.2 | 105.96 ± 25.17 |
| kcen | input-pting | 93.3 ± 1.8 | 90.1 | 97.8 | 110.39 ± 26.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|