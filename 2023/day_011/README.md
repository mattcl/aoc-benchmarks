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
| mattcl | input-pting | 0.7 ± 0.3 | 0.1 | 3.2 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.22 ± 0.60 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.25 ± 0.62 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 2.2 | 1.29 ± 0.64 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.3 | 5.5 | 4.12 ± 1.93 |
| lanjian | input-mattcl | 3.2 ± 2.5 | 1.9 | 38.4 | 4.34 ± 3.99 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.7 | 5.2 | 4.81 ± 2.26 |
| lanjian | input-kcen | 3.6 ± 0.4 | 2.7 | 5.2 | 4.87 ± 2.29 |
| mattcl-py | input-pting | 15.2 ± 0.5 | 14.2 | 18.3 | 20.74 ± 9.51 |
| mattcl-py | input-lanjian | 15.2 ± 0.7 | 14.2 | 18.3 | 20.80 ± 9.55 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 14.1 | 18.7 | 20.83 ± 9.55 |
| mattcl-py | input-mattcl | 15.5 ± 4.2 | 14.1 | 60.2 | 21.21 ± 11.29 |
| pting | input-kcen | 53.6 ± 1.4 | 52.0 | 59.1 | 73.13 ± 33.49 |
| pting | input-mattcl | 54.4 ± 2.8 | 51.9 | 67.2 | 74.26 ± 34.15 |
| pting | input-lanjian | 54.5 ± 2.5 | 51.7 | 64.0 | 74.40 ± 34.18 |
| pting | input-pting | 56.6 ± 1.5 | 54.4 | 60.4 | 77.25 ± 35.37 |
| kcen | input-kcen | 89.2 ± 1.2 | 87.3 | 92.7 | 121.73 ± 55.67 |
| kcen | input-lanjian | 89.2 ± 3.0 | 86.7 | 104.7 | 121.76 ± 55.81 |
| kcen | input-mattcl | 90.3 ± 1.5 | 88.0 | 93.7 | 123.36 ± 56.42 |
| kcen | input-pting | 94.2 ± 1.5 | 91.1 | 98.5 | 128.59 ± 58.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|