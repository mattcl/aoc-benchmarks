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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.8 | 1.02 ± 0.24 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.8 | 1.05 ± 0.23 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 1.8 | 1.07 ± 0.22 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.4 | 5.9 | 2.58 ± 0.50 |
| lanjian | input-pting | 3.3 ± 0.5 | 2.5 | 5.9 | 2.71 ± 0.59 |
| lanjian | input-lanjian | 3.8 ± 0.5 | 2.9 | 7.1 | 3.11 ± 0.64 |
| lanjian | input-kcen | 3.8 ± 0.4 | 2.9 | 5.3 | 3.11 ± 0.63 |
| mattcl-py | input-lanjian | 55.4 ± 0.8 | 53.9 | 57.5 | 45.52 ± 7.61 |
| mattcl-py | input-kcen | 56.4 ± 2.5 | 54.3 | 72.1 | 46.40 ± 7.99 |
| mattcl-py | input-mattcl | 56.9 ± 1.7 | 54.8 | 64.0 | 46.81 ± 7.92 |
| pting | input-lanjian | 58.0 ± 1.5 | 55.6 | 61.7 | 47.67 ± 8.03 |
| pting | input-kcen | 58.5 ± 1.7 | 55.8 | 65.4 | 48.09 ± 8.13 |
| pting | input-mattcl | 59.0 ± 1.5 | 56.0 | 64.0 | 48.54 ± 8.17 |
| mattcl-py | input-pting | 59.1 ± 1.3 | 56.6 | 63.2 | 48.63 ± 8.17 |
| pting | input-pting | 62.3 ± 3.5 | 58.3 | 82.1 | 51.24 ± 9.00 |
| kcen | input-lanjian | 84.9 ± 1.3 | 82.3 | 88.5 | 69.77 ± 11.66 |
| kcen | input-kcen | 86.1 ± 2.6 | 83.6 | 95.3 | 70.80 ± 11.98 |
| kcen | input-mattcl | 86.5 ± 1.8 | 84.1 | 93.6 | 71.10 ± 11.93 |
| kcen | input-pting | 90.3 ± 1.9 | 87.0 | 96.3 | 74.24 ± 12.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|