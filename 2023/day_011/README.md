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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.1 | 1.00 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.0 | 1.01 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.6 | 1.04 ± 0.28 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.4 | 4.4 | 3.56 ± 0.78 |
| lanjian | input-pting | 3.3 ± 0.5 | 2.4 | 6.7 | 3.90 ± 0.98 |
| lanjian | input-lanjian | 3.8 ± 0.4 | 3.1 | 6.5 | 4.45 ± 1.07 |
| lanjian | input-kcen | 4.1 ± 4.0 | 2.7 | 60.3 | 4.76 ± 4.84 |
| mattcl-py | input-lanjian | 15.1 ± 0.5 | 14.2 | 18.5 | 17.77 ± 3.77 |
| mattcl-py | input-mattcl | 15.2 ± 0.7 | 14.2 | 19.0 | 17.89 ± 3.83 |
| mattcl-py | input-pting | 15.2 ± 0.7 | 14.1 | 18.7 | 17.89 ± 3.84 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 14.1 | 18.1 | 17.95 ± 3.83 |
| pting | input-lanjian | 57.2 ± 1.5 | 54.9 | 62.9 | 67.19 ± 14.18 |
| pting | input-kcen | 57.2 ± 0.9 | 55.3 | 60.0 | 67.26 ± 14.12 |
| pting | input-mattcl | 57.7 ± 1.0 | 56.3 | 60.3 | 67.85 ± 14.26 |
| pting | input-pting | 60.9 ± 1.4 | 58.2 | 64.5 | 71.60 ± 15.08 |
| kcen | input-lanjian | 90.0 ± 1.7 | 87.0 | 95.4 | 105.73 ± 22.22 |
| kcen | input-kcen | 91.3 ± 1.3 | 89.3 | 95.8 | 107.24 ± 22.51 |
| kcen | input-mattcl | 92.2 ± 1.5 | 89.7 | 96.6 | 108.40 ± 22.77 |
| kcen | input-pting | 95.8 ± 1.3 | 94.1 | 99.6 | 112.64 ± 23.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|