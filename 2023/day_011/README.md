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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.5 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.3 | 1.2 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.31 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.4 | 1.1 | 1.09 ± 0.30 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 4.6 | 3.44 ± 0.87 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.3 | 6.1 | 3.50 ± 0.96 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 2.8 | 6.4 | 4.21 ± 1.13 |
| lanjian | input-kcen | 3.8 ± 0.5 | 2.9 | 7.4 | 4.25 ± 1.16 |
| mattcl-py | input-mattcl | 15.1 ± 0.6 | 13.8 | 18.8 | 17.03 ± 4.14 |
| mattcl-py | input-pting | 15.1 ± 0.6 | 13.9 | 19.0 | 17.03 ± 4.15 |
| mattcl-py | input-kcen | 15.2 ± 0.6 | 14.1 | 18.3 | 17.12 ± 4.16 |
| mattcl-py | input-lanjian | 15.3 ± 0.6 | 14.3 | 18.3 | 17.18 ± 4.19 |
| pting | input-lanjian | 53.2 ± 1.2 | 51.2 | 56.2 | 59.88 ± 14.46 |
| pting | input-mattcl | 54.0 ± 1.6 | 51.7 | 59.2 | 60.71 ± 14.72 |
| pting | input-kcen | 54.0 ± 1.7 | 51.8 | 59.8 | 60.77 ± 14.74 |
| pting | input-pting | 56.7 ± 4.8 | 53.8 | 89.6 | 63.85 ± 16.28 |
| kcen | input-lanjian | 85.1 ± 2.3 | 82.9 | 94.4 | 95.80 ± 23.18 |
| kcen | input-mattcl | 86.5 ± 2.2 | 83.9 | 96.2 | 97.31 ± 23.53 |
| kcen | input-kcen | 87.1 ± 3.0 | 84.9 | 102.5 | 97.99 ± 23.80 |
| kcen | input-pting | 90.8 ± 1.4 | 88.2 | 93.4 | 102.16 ± 24.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|