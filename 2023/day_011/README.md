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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.5 | 1.1 | 1.01 ± 0.27 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.29 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.29 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 4.7 | 3.42 ± 0.82 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 4.4 | 3.42 ± 0.83 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 3.0 | 5.7 | 3.98 ± 0.99 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.8 | 5.7 | 4.02 ± 0.99 |
| mattcl-py | input-pting | 15.1 ± 0.6 | 14.3 | 17.7 | 17.22 ± 3.90 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 14.1 | 18.5 | 17.25 ± 3.92 |
| mattcl-py | input-kcen | 15.2 ± 0.5 | 14.0 | 17.8 | 17.32 ± 3.92 |
| mattcl-py | input-mattcl | 15.2 ± 0.7 | 14.0 | 18.1 | 17.34 ± 3.95 |
| pting | input-lanjian | 53.2 ± 2.1 | 51.0 | 61.9 | 60.53 ± 13.75 |
| pting | input-mattcl | 53.5 ± 1.7 | 51.5 | 60.7 | 60.88 ± 13.75 |
| pting | input-kcen | 54.2 ± 2.6 | 51.6 | 64.4 | 61.65 ± 14.11 |
| pting | input-pting | 55.8 ± 2.5 | 53.7 | 71.2 | 63.51 ± 14.48 |
| kcen | input-lanjian | 88.8 ± 1.2 | 86.5 | 91.0 | 100.95 ± 22.62 |
| kcen | input-kcen | 89.7 ± 2.1 | 87.1 | 97.8 | 102.07 ± 22.96 |
| kcen | input-mattcl | 90.2 ± 1.6 | 87.3 | 93.3 | 102.60 ± 23.01 |
| kcen | input-pting | 94.6 ± 1.9 | 91.5 | 101.8 | 107.61 ± 24.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|