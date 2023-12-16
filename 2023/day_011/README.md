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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.30 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.1 | 1.0 | 1.04 ± 0.29 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.2 | 1.5 | 1.05 ± 0.29 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 2.1 | 5.3 | 3.75 ± 0.90 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.0 | 5.4 | 3.84 ± 0.93 |
| lanjian | input-lanjian | 3.2 ± 0.4 | 2.5 | 6.4 | 4.20 ± 1.02 |
| lanjian | input-kcen | 3.3 ± 0.4 | 2.5 | 4.8 | 4.31 ± 1.07 |
| mattcl-py | input-lanjian | 15.0 ± 0.6 | 13.8 | 17.6 | 19.40 ± 4.21 |
| mattcl-py | input-mattcl | 15.0 ± 0.7 | 13.9 | 17.8 | 19.41 ± 4.22 |
| mattcl-py | input-pting | 15.0 ± 0.7 | 14.0 | 17.6 | 19.44 ± 4.24 |
| mattcl-py | input-kcen | 15.3 ± 3.0 | 14.0 | 46.4 | 19.83 ± 5.77 |
| pting | input-lanjian | 53.6 ± 2.2 | 51.3 | 63.4 | 69.51 ± 15.09 |
| pting | input-kcen | 53.9 ± 1.6 | 51.8 | 59.6 | 69.93 ± 15.05 |
| pting | input-mattcl | 54.1 ± 2.8 | 51.6 | 68.6 | 70.15 ± 15.40 |
| pting | input-pting | 56.3 ± 1.7 | 54.1 | 63.1 | 73.06 ± 15.73 |
| kcen | input-lanjian | 88.6 ± 2.5 | 85.4 | 100.8 | 114.94 ± 24.70 |
| kcen | input-mattcl | 89.3 ± 1.7 | 86.6 | 94.0 | 115.75 ± 24.76 |
| kcen | input-kcen | 89.9 ± 1.7 | 86.9 | 93.8 | 116.56 ± 24.93 |
| kcen | input-pting | 94.5 ± 1.7 | 92.1 | 99.8 | 122.48 ± 26.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|