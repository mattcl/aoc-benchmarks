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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.02 ± 0.30 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.4 | 1.3 | 1.02 ± 0.28 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.0 | 5.4 | 3.41 ± 0.85 |
| lanjian | input-pting | 3.0 ± 0.4 | 2.3 | 5.7 | 3.42 ± 0.86 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.5 | 6.1 | 3.86 ± 0.98 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.7 | 5.0 | 3.90 ± 0.97 |
| mattcl-py | input-pting | 15.1 ± 0.7 | 13.8 | 18.3 | 17.07 ± 3.88 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.1 | 18.1 | 17.14 ± 3.89 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 13.8 | 18.5 | 17.15 ± 3.89 |
| mattcl-py | input-kcen | 15.3 ± 0.7 | 13.9 | 18.9 | 17.24 ± 3.92 |
| pting | input-lanjian | 56.6 ± 1.2 | 54.7 | 60.3 | 63.82 ± 14.30 |
| pting | input-kcen | 57.3 ± 1.2 | 55.3 | 60.3 | 64.70 ± 14.50 |
| pting | input-mattcl | 57.9 ± 2.2 | 55.0 | 69.7 | 65.32 ± 14.79 |
| pting | input-pting | 60.4 ± 2.0 | 58.0 | 66.7 | 68.16 ± 15.37 |
| kcen | input-lanjian | 89.3 ± 1.7 | 87.2 | 93.9 | 100.76 ± 22.57 |
| kcen | input-kcen | 90.1 ± 1.1 | 88.2 | 92.4 | 101.67 ± 22.73 |
| kcen | input-mattcl | 91.1 ± 1.2 | 88.8 | 94.6 | 102.80 ± 22.98 |
| kcen | input-pting | 95.8 ± 2.9 | 92.1 | 108.9 | 108.13 ± 24.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|