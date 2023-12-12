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
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.8 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.4 | 1.7 | 1.01 ± 0.20 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 2.8 | 1.02 ± 0.22 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.3 | 5.8 | 2.64 ± 0.53 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.7 | 4.7 | 2.72 ± 0.52 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 2.9 | 5.1 | 3.09 ± 0.58 |
| lanjian | input-kcen | 3.7 ± 0.4 | 3.1 | 5.9 | 3.14 ± 0.60 |
| pting | input-kcen | 52.9 ± 1.3 | 51.3 | 59.3 | 44.70 ± 7.23 |
| pting | input-lanjian | 53.1 ± 2.3 | 51.0 | 62.6 | 44.89 ± 7.42 |
| pting | input-mattcl | 53.1 ± 1.1 | 51.2 | 56.7 | 44.92 ± 7.23 |
| mattcl-py | input-kcen | 55.2 ± 2.6 | 53.2 | 71.6 | 46.71 ± 7.78 |
| mattcl-py | input-lanjian | 55.3 ± 2.3 | 53.0 | 69.8 | 46.77 ± 7.72 |
| pting | input-pting | 55.7 ± 1.2 | 53.3 | 59.6 | 47.07 ± 7.58 |
| mattcl-py | input-mattcl | 56.2 ± 2.6 | 54.4 | 70.3 | 47.51 ± 7.90 |
| mattcl-py | input-pting | 58.4 ± 1.4 | 56.0 | 62.7 | 49.37 ± 7.97 |
| kcen | input-lanjian | 85.3 ± 1.5 | 83.0 | 90.5 | 72.09 ± 11.58 |
| kcen | input-kcen | 85.4 ± 1.6 | 82.7 | 90.0 | 72.16 ± 11.60 |
| kcen | input-mattcl | 87.1 ± 2.1 | 84.1 | 96.7 | 73.60 ± 11.89 |
| kcen | input-pting | 90.3 ± 1.9 | 87.5 | 98.6 | 76.35 ± 12.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|