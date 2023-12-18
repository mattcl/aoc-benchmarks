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
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.5 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.31 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.30 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.2 | 1.3 | 1.03 ± 0.29 |
| lanjian | input-mattcl | 2.9 ± 0.2 | 1.9 | 3.5 | 3.68 ± 0.86 |
| lanjian | input-pting | 2.9 ± 0.3 | 2.0 | 4.5 | 3.69 ± 0.89 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.4 | 4.9 | 4.23 ± 1.06 |
| lanjian | input-kcen | 3.4 ± 0.4 | 2.6 | 6.4 | 4.25 ± 1.09 |
| mattcl-py | input-pting | 15.0 ± 0.5 | 13.8 | 18.1 | 18.83 ± 4.25 |
| mattcl-py | input-mattcl | 15.0 ± 0.6 | 14.0 | 18.4 | 18.83 ± 4.26 |
| mattcl-py | input-lanjian | 15.1 ± 0.6 | 13.9 | 18.4 | 18.88 ± 4.28 |
| mattcl-py | input-kcen | 15.3 ± 0.7 | 14.0 | 18.7 | 19.13 ± 4.37 |
| pting | input-lanjian | 53.1 ± 1.6 | 51.1 | 59.4 | 66.51 ± 15.00 |
| pting | input-mattcl | 53.2 ± 1.4 | 51.2 | 58.2 | 66.71 ± 15.01 |
| pting | input-kcen | 53.4 ± 1.3 | 51.8 | 58.8 | 66.98 ± 15.05 |
| pting | input-pting | 56.5 ± 1.6 | 54.0 | 61.8 | 70.82 ± 15.95 |
| kcen | input-lanjian | 84.9 ± 1.5 | 83.0 | 90.3 | 106.35 ± 23.84 |
| kcen | input-mattcl | 86.4 ± 1.7 | 84.3 | 92.9 | 108.23 ± 24.28 |
| kcen | input-kcen | 87.5 ± 2.8 | 84.6 | 95.7 | 109.58 ± 24.73 |
| kcen | input-pting | 90.2 ± 2.3 | 87.8 | 97.6 | 113.02 ± 25.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|