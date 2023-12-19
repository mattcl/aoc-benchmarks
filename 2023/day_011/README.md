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
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.6 | 1.00 ± 0.25 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.5 | 1.02 ± 0.24 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.6 | 1.2 | 1.03 ± 0.23 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.2 | 5.1 | 3.21 ± 0.64 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.1 | 5.3 | 3.26 ± 0.69 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.8 | 5.1 | 3.69 ± 0.75 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.8 | 5.8 | 3.72 ± 0.78 |
| mattcl-py | input-pting | 15.3 ± 0.7 | 13.9 | 18.4 | 16.07 ± 2.86 |
| mattcl-py | input-mattcl | 15.3 ± 0.7 | 14.1 | 18.2 | 16.08 ± 2.84 |
| mattcl-py | input-lanjian | 15.3 ± 0.7 | 13.9 | 18.5 | 16.11 ± 2.84 |
| mattcl-py | input-kcen | 15.4 ± 0.5 | 14.4 | 17.9 | 16.17 ± 2.82 |
| pting | input-lanjian | 55.8 ± 1.2 | 54.1 | 59.0 | 58.81 ± 10.13 |
| pting | input-mattcl | 56.0 ± 1.3 | 53.9 | 59.1 | 58.98 ± 10.18 |
| pting | input-kcen | 56.5 ± 2.1 | 54.3 | 68.5 | 59.54 ± 10.43 |
| pting | input-pting | 59.0 ± 1.5 | 56.9 | 63.5 | 62.13 ± 10.74 |
| kcen | input-lanjian | 85.5 ± 1.8 | 82.9 | 89.8 | 90.01 ± 15.51 |
| kcen | input-mattcl | 86.6 ± 1.3 | 84.5 | 89.3 | 91.25 ± 15.67 |
| kcen | input-kcen | 87.3 ± 1.5 | 84.8 | 93.3 | 91.91 ± 15.80 |
| kcen | input-pting | 90.5 ± 1.7 | 87.6 | 94.8 | 95.26 ± 16.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|