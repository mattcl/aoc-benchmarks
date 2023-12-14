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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.7 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.8 | 1.00 ± 0.20 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.7 | 1.7 | 1.02 ± 0.18 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.2 | 1.06 ± 0.24 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.4 | 6.0 | 2.59 ± 0.45 |
| lanjian | input-mattcl | 3.2 ± 0.4 | 2.4 | 6.3 | 2.61 ± 0.50 |
| lanjian | input-lanjian | 3.8 ± 0.4 | 2.9 | 6.6 | 3.09 ± 0.53 |
| lanjian | input-kcen | 3.9 ± 0.6 | 3.0 | 6.3 | 3.18 ± 0.64 |
| mattcl-py | input-lanjian | 55.6 ± 1.4 | 53.7 | 63.3 | 45.53 ± 6.46 |
| mattcl-py | input-kcen | 55.9 ± 1.4 | 54.0 | 61.5 | 45.80 ± 6.49 |
| mattcl-py | input-mattcl | 57.1 ± 1.3 | 55.1 | 60.8 | 46.74 ± 6.61 |
| pting | input-kcen | 58.3 ± 1.5 | 55.3 | 61.8 | 47.77 ± 6.78 |
| pting | input-lanjian | 58.4 ± 2.3 | 55.4 | 69.0 | 47.86 ± 6.94 |
| pting | input-mattcl | 58.9 ± 1.5 | 55.7 | 61.4 | 48.22 ± 6.84 |
| mattcl-py | input-pting | 58.9 ± 1.4 | 57.1 | 64.8 | 48.27 ± 6.84 |
| pting | input-pting | 62.2 ± 2.9 | 58.9 | 78.3 | 50.95 ± 7.50 |
| kcen | input-lanjian | 84.6 ± 1.7 | 82.5 | 90.8 | 69.31 ± 9.79 |
| kcen | input-kcen | 85.3 ± 2.5 | 82.4 | 97.5 | 69.91 ± 9.97 |
| kcen | input-mattcl | 86.2 ± 1.4 | 84.2 | 89.1 | 70.64 ± 9.93 |
| kcen | input-pting | 91.9 ± 6.9 | 87.4 | 128.4 | 75.29 ± 11.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|