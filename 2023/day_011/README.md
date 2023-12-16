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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.1 | 1.00 ± 0.24 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.2 | 1.1 | 1.01 ± 0.25 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.25 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.1 | 5.6 | 3.24 ± 0.70 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.1 | 3.6 | 3.31 ± 0.67 |
| lanjian | input-kcen | 3.4 ± 0.5 | 2.6 | 6.5 | 3.69 ± 0.84 |
| lanjian | input-lanjian | 3.4 ± 0.5 | 2.6 | 6.6 | 3.70 ± 0.84 |
| mattcl-py | input-pting | 15.0 ± 0.5 | 14.0 | 17.7 | 16.35 ± 3.05 |
| mattcl-py | input-mattcl | 15.0 ± 0.5 | 14.2 | 17.7 | 16.37 ± 3.05 |
| mattcl-py | input-kcen | 15.2 ± 0.6 | 14.1 | 18.4 | 16.52 ± 3.10 |
| mattcl-py | input-lanjian | 15.5 ± 3.7 | 14.0 | 59.2 | 16.87 ± 5.07 |
| pting | input-lanjian | 53.8 ± 2.1 | 51.4 | 64.8 | 58.47 ± 10.97 |
| pting | input-mattcl | 53.9 ± 1.4 | 51.7 | 60.7 | 58.63 ± 10.86 |
| pting | input-kcen | 54.9 ± 4.6 | 51.8 | 82.7 | 59.72 ± 12.04 |
| pting | input-pting | 56.0 ± 1.6 | 54.2 | 64.3 | 60.91 ± 11.31 |
| kcen | input-lanjian | 88.3 ± 1.8 | 85.4 | 94.3 | 96.07 ± 17.72 |
| kcen | input-kcen | 88.9 ± 1.5 | 86.0 | 92.8 | 96.67 ± 17.80 |
| kcen | input-mattcl | 89.5 ± 1.2 | 87.7 | 92.1 | 97.29 ± 17.89 |
| kcen | input-pting | 93.9 ± 1.4 | 91.7 | 97.3 | 102.13 ± 18.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|