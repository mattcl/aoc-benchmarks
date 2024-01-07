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
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 ± 0.32 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.31 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.2 | 1.03 ± 0.31 |
| lanjian | input-mattcl | 2.9 ± 0.5 | 1.9 | 5.4 | 3.64 ± 0.99 |
| lanjian | input-pting | 3.0 ± 0.4 | 2.2 | 6.0 | 3.76 ± 0.94 |
| lanjian | input-lanjian | 3.5 ± 2.6 | 2.5 | 39.4 | 4.36 ± 3.37 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.8 | 5.5 | 4.36 ± 1.09 |
| mattcl-py | input-pting | 14.9 ± 0.7 | 13.9 | 18.2 | 18.57 ± 4.20 |
| mattcl-py | input-lanjian | 14.9 ± 0.5 | 13.9 | 18.2 | 18.57 ± 4.16 |
| mattcl-py | input-kcen | 15.1 ± 0.6 | 14.1 | 18.3 | 18.77 ± 4.24 |
| mattcl-py | input-mattcl | 15.2 ± 3.4 | 13.8 | 53.0 | 18.91 ± 5.95 |
| pting | input-mattcl | 55.0 ± 1.5 | 52.4 | 62.5 | 68.41 ± 15.28 |
| pting | input-lanjian | 55.2 ± 2.9 | 52.6 | 73.0 | 68.76 ± 15.67 |
| pting | input-kcen | 55.5 ± 1.8 | 53.0 | 64.5 | 69.14 ± 15.48 |
| pting | input-pting | 57.9 ± 1.8 | 55.6 | 64.6 | 72.02 ± 16.12 |
| kcen | input-lanjian | 85.0 ± 5.5 | 82.0 | 115.9 | 105.86 ± 24.44 |
| kcen | input-kcen | 86.0 ± 1.7 | 83.0 | 90.5 | 107.01 ± 23.82 |
| kcen | input-mattcl | 86.2 ± 1.8 | 83.3 | 90.7 | 107.30 ± 23.89 |
| kcen | input-pting | 89.7 ± 2.3 | 86.7 | 99.5 | 111.64 ± 24.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|