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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.3 | 1.03 ± 0.28 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.2 | 1.4 | 1.04 ± 0.29 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.4 | 1.04 ± 0.27 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.1 | 5.6 | 3.30 ± 0.75 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.1 | 5.0 | 3.33 ± 0.73 |
| lanjian | input-lanjian | 3.5 ± 0.3 | 2.7 | 5.1 | 3.72 ± 0.86 |
| lanjian | input-kcen | 3.6 ± 0.5 | 2.7 | 6.6 | 3.81 ± 0.93 |
| mattcl-py | input-pting | 15.3 ± 0.6 | 14.0 | 18.0 | 16.32 ± 3.47 |
| mattcl-py | input-lanjian | 15.3 ± 0.6 | 14.1 | 18.3 | 16.40 ± 3.48 |
| mattcl-py | input-kcen | 15.4 ± 0.5 | 14.4 | 18.5 | 16.43 ± 3.47 |
| mattcl-py | input-mattcl | 15.5 ± 2.9 | 14.3 | 54.5 | 16.58 ± 4.62 |
| pting | input-lanjian | 54.9 ± 1.4 | 52.5 | 58.5 | 58.79 ± 12.34 |
| pting | input-mattcl | 55.6 ± 1.3 | 52.9 | 58.7 | 59.49 ± 12.47 |
| pting | input-kcen | 56.1 ± 2.2 | 53.1 | 65.2 | 60.01 ± 12.72 |
| pting | input-pting | 58.3 ± 1.9 | 55.8 | 66.8 | 62.43 ± 13.16 |
| kcen | input-lanjian | 84.8 ± 1.2 | 82.6 | 87.1 | 90.73 ± 18.95 |
| kcen | input-mattcl | 86.5 ± 1.3 | 84.3 | 89.0 | 92.58 ± 19.34 |
| kcen | input-kcen | 86.7 ± 1.6 | 84.0 | 89.7 | 92.77 ± 19.40 |
| kcen | input-pting | 90.3 ± 1.5 | 88.1 | 95.9 | 96.66 ± 20.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|