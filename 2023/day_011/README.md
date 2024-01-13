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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.2 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.23 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.3 | 1.4 | 1.01 ± 0.24 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.4 | 1.2 | 1.03 ± 0.22 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.1 | 3.5 | 3.03 ± 0.57 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.2 | 5.1 | 3.16 ± 0.60 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.7 | 6.5 | 3.53 ± 0.74 |
| lanjian | input-kcen | 3.5 ± 0.5 | 2.6 | 7.0 | 3.53 ± 0.80 |
| mattcl-py | input-mattcl | 15.1 ± 0.5 | 14.0 | 18.0 | 15.20 ± 2.66 |
| mattcl-py | input-lanjian | 15.1 ± 0.4 | 13.9 | 17.8 | 15.21 ± 2.64 |
| mattcl-py | input-pting | 15.1 ± 0.6 | 14.2 | 18.4 | 15.25 ± 2.67 |
| mattcl-py | input-kcen | 15.2 ± 0.5 | 14.2 | 17.9 | 15.32 ± 2.67 |
| pting | input-lanjian | 53.5 ± 1.3 | 51.7 | 56.9 | 54.04 ± 9.34 |
| pting | input-mattcl | 53.9 ± 1.2 | 52.2 | 58.2 | 54.42 ± 9.39 |
| pting | input-kcen | 54.9 ± 6.2 | 52.2 | 98.6 | 55.42 ± 11.34 |
| pting | input-pting | 56.1 ± 1.3 | 54.6 | 61.6 | 56.60 ± 9.77 |
| kcen | input-lanjian | 85.5 ± 1.6 | 82.9 | 91.2 | 86.29 ± 14.86 |
| kcen | input-kcen | 87.2 ± 2.3 | 84.4 | 93.4 | 87.96 ± 15.22 |
| kcen | input-mattcl | 87.5 ± 1.6 | 85.0 | 93.2 | 88.31 ± 15.20 |
| kcen | input-pting | 91.6 ± 1.5 | 88.6 | 95.2 | 92.47 ± 15.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|