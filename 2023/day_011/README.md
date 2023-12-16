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
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.4 | 1.06 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.2 | 1.08 ± 0.27 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.2 | 1.7 | 1.10 ± 0.28 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.2 | 5.6 | 3.52 ± 0.80 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.2 | 5.3 | 3.57 ± 0.80 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.7 | 5.7 | 4.00 ± 0.92 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.7 | 5.6 | 4.04 ± 0.92 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 14.0 | 18.8 | 17.52 ± 3.59 |
| mattcl-py | input-pting | 15.3 ± 0.7 | 14.0 | 18.8 | 17.57 ± 3.62 |
| mattcl-py | input-mattcl | 15.3 ± 0.6 | 14.0 | 18.5 | 17.57 ± 3.60 |
| mattcl-py | input-kcen | 15.3 ± 0.5 | 14.4 | 18.0 | 17.64 ± 3.60 |
| pting | input-lanjian | 53.3 ± 1.8 | 51.3 | 61.5 | 61.31 ± 12.51 |
| pting | input-kcen | 53.9 ± 1.6 | 51.7 | 60.6 | 61.94 ± 12.58 |
| pting | input-mattcl | 54.0 ± 1.5 | 51.8 | 59.0 | 62.05 ± 12.60 |
| pting | input-pting | 58.1 ± 8.8 | 54.6 | 110.1 | 66.81 ± 16.80 |
| kcen | input-lanjian | 91.1 ± 1.4 | 87.9 | 93.8 | 104.75 ± 21.13 |
| kcen | input-kcen | 93.5 ± 2.5 | 90.3 | 99.6 | 107.47 ± 21.80 |
| kcen | input-mattcl | 93.6 ± 2.4 | 90.8 | 102.7 | 107.55 ± 21.81 |
| kcen | input-pting | 97.6 ± 1.5 | 95.6 | 102.5 | 112.16 ± 22.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|