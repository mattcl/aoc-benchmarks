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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.2 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.3 | 1.3 | 1.01 ± 0.25 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.4 | 1.3 | 1.04 ± 0.24 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.4 | 1.2 | 1.06 ± 0.24 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 3.9 | 3.31 ± 0.67 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.1 | 6.2 | 3.35 ± 0.70 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.8 | 5.0 | 3.76 ± 0.78 |
| lanjian | input-kcen | 3.5 ± 0.3 | 2.8 | 5.8 | 3.78 ± 0.75 |
| mattcl-py | input-mattcl | 15.0 ± 0.6 | 14.0 | 18.4 | 16.10 ± 2.99 |
| mattcl-py | input-kcen | 15.1 ± 0.5 | 14.3 | 17.7 | 16.19 ± 3.00 |
| mattcl-py | input-pting | 15.1 ± 0.7 | 14.1 | 17.8 | 16.23 ± 3.04 |
| mattcl-py | input-lanjian | 15.3 ± 3.0 | 14.0 | 55.6 | 16.36 ± 4.35 |
| pting | input-lanjian | 53.6 ± 4.5 | 51.4 | 85.1 | 57.45 ± 11.47 |
| pting | input-mattcl | 53.8 ± 1.5 | 51.8 | 59.4 | 57.68 ± 10.59 |
| pting | input-kcen | 54.1 ± 1.6 | 51.8 | 58.6 | 58.06 ± 10.66 |
| pting | input-pting | 56.7 ± 1.7 | 54.4 | 61.8 | 60.85 ± 11.18 |
| kcen | input-lanjian | 85.8 ± 2.1 | 82.4 | 93.2 | 92.05 ± 16.85 |
| kcen | input-kcen | 86.6 ± 1.7 | 84.3 | 92.4 | 92.83 ± 16.94 |
| kcen | input-mattcl | 86.9 ± 1.2 | 84.0 | 89.4 | 93.17 ± 16.95 |
| kcen | input-pting | 90.6 ± 2.2 | 87.8 | 98.7 | 97.14 ± 17.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|