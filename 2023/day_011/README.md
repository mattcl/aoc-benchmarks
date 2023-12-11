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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.24 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.4 | 1.6 | 1.04 ± 0.24 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.6 | 1.7 | 1.06 ± 0.24 |
| lanjian | input-mattcl | 2.9 ± 0.4 | 2.0 | 5.1 | 2.80 ± 0.59 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.1 | 4.3 | 2.82 ± 0.53 |
| lanjian | input-kcen | 3.4 ± 0.4 | 2.9 | 4.6 | 3.20 ± 0.66 |
| lanjian | input-lanjian | 3.4 ± 2.0 | 2.1 | 30.5 | 3.22 ± 1.99 |
| pting | input-kcen | 52.2 ± 1.6 | 50.4 | 57.7 | 49.74 ± 8.60 |
| pting | input-lanjian | 52.2 ± 1.7 | 50.2 | 61.2 | 49.75 ± 8.62 |
| pting | input-mattcl | 52.4 ± 1.0 | 50.7 | 55.0 | 49.88 ± 8.55 |
| mattcl-py | input-kcen | 54.2 ± 1.5 | 52.2 | 58.7 | 51.60 ± 8.91 |
| mattcl-py | input-lanjian | 54.3 ± 1.3 | 52.7 | 59.6 | 51.68 ± 8.88 |
| pting | input-pting | 55.1 ± 1.2 | 53.0 | 59.4 | 52.48 ± 9.01 |
| mattcl-py | input-mattcl | 55.3 ± 0.9 | 53.8 | 57.5 | 52.66 ± 9.00 |
| mattcl-py | input-pting | 57.8 ± 1.1 | 56.1 | 60.4 | 55.01 ± 9.43 |
| kcen | input-kcen | 88.0 ± 1.5 | 86.0 | 92.9 | 83.85 ± 14.34 |
| kcen | input-lanjian | 89.1 ± 2.2 | 86.3 | 98.5 | 84.83 ± 14.58 |
| kcen | input-mattcl | 90.9 ± 2.9 | 88.0 | 105.8 | 86.61 ± 15.01 |
| kcen | input-pting | 95.5 ± 4.0 | 92.0 | 111.3 | 90.92 ± 15.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|