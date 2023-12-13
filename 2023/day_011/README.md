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
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.5 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.8 | 1.01 ± 0.25 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.8 | 1.01 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 2.2 | 1.03 ± 0.25 |
| lanjian | input-pting | 3.0 ± 0.5 | 2.2 | 5.7 | 2.57 ± 0.64 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.8 | 2.59 ± 0.57 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 2.9 | 5.7 | 3.13 ± 0.70 |
| lanjian | input-kcen | 3.8 ± 0.5 | 3.1 | 6.6 | 3.21 ± 0.74 |
| mattcl-py | input-lanjian | 55.6 ± 1.2 | 53.3 | 58.3 | 46.90 ± 9.28 |
| mattcl-py | input-kcen | 56.2 ± 1.4 | 53.7 | 60.4 | 47.43 ± 9.41 |
| mattcl-py | input-mattcl | 57.1 ± 1.3 | 55.2 | 61.2 | 48.19 ± 9.55 |
| pting | input-lanjian | 58.2 ± 1.8 | 55.7 | 65.8 | 49.09 ± 9.78 |
| pting | input-kcen | 58.2 ± 1.3 | 55.9 | 61.2 | 49.10 ± 9.73 |
| pting | input-mattcl | 58.6 ± 1.8 | 55.0 | 65.2 | 49.39 ± 9.84 |
| mattcl-py | input-pting | 59.5 ± 3.2 | 57.3 | 80.0 | 50.21 ± 10.24 |
| pting | input-pting | 62.3 ± 2.2 | 58.2 | 71.2 | 52.51 ± 10.50 |
| kcen | input-kcen | 85.8 ± 2.2 | 82.8 | 92.6 | 72.34 ± 14.36 |
| kcen | input-lanjian | 85.9 ± 3.0 | 82.4 | 96.2 | 72.46 ± 14.49 |
| kcen | input-mattcl | 86.6 ± 1.7 | 84.3 | 92.4 | 73.05 ± 14.45 |
| kcen | input-pting | 91.1 ± 2.9 | 87.5 | 100.4 | 76.86 ± 15.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|