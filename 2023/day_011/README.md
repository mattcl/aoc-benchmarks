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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.4 | 1.04 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.1 | 1.05 ± 0.31 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.5 | 1.5 | 1.09 ± 0.29 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.1 | 5.4 | 3.57 ± 0.86 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.1 | 5.5 | 3.57 ± 0.90 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.7 | 6.0 | 4.07 ± 1.02 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.6 | 5.9 | 4.12 ± 1.04 |
| mattcl-py | input-pting | 15.2 ± 0.6 | 14.2 | 18.4 | 17.89 ± 4.07 |
| mattcl-py | input-mattcl | 15.2 ± 0.7 | 14.3 | 18.1 | 17.93 ± 4.10 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 14.0 | 18.6 | 17.99 ± 4.10 |
| mattcl-py | input-lanjian | 15.3 ± 0.6 | 14.0 | 18.5 | 18.03 ± 4.11 |
| pting | input-mattcl | 55.9 ± 1.3 | 54.4 | 60.9 | 65.91 ± 14.89 |
| pting | input-lanjian | 56.3 ± 2.7 | 54.2 | 73.4 | 66.30 ± 15.25 |
| pting | input-kcen | 56.7 ± 1.5 | 54.5 | 61.6 | 66.83 ± 15.13 |
| pting | input-pting | 59.7 ± 2.0 | 57.2 | 68.8 | 70.32 ± 15.99 |
| kcen | input-lanjian | 86.0 ± 1.5 | 83.4 | 89.1 | 101.31 ± 22.84 |
| kcen | input-mattcl | 86.6 ± 1.5 | 83.8 | 91.1 | 102.03 ± 23.00 |
| kcen | input-kcen | 86.6 ± 1.3 | 84.7 | 90.2 | 102.08 ± 22.99 |
| kcen | input-pting | 91.3 ± 2.3 | 88.3 | 99.0 | 107.61 ± 24.33 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|