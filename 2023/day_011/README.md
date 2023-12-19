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
| mattcl | input-kcen | 0.8 ± 0.3 | 0.2 | 1.1 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.19 ± 0.48 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.5 | 1.1 | 1.22 ± 0.45 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.5 | 1.23 ± 0.45 |
| lanjian | input-mattcl | 3.0 ± 0.4 | 2.2 | 5.4 | 3.92 ± 1.41 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.1 | 4.5 | 4.02 ± 1.37 |
| lanjian | input-kcen | 3.4 ± 0.4 | 2.6 | 6.0 | 4.48 ± 1.59 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.6 | 6.5 | 4.54 ± 1.61 |
| mattcl-py | input-mattcl | 15.0 ± 0.6 | 13.9 | 18.3 | 19.69 ± 6.59 |
| mattcl-py | input-pting | 15.1 ± 0.6 | 14.0 | 18.3 | 19.70 ± 6.60 |
| mattcl-py | input-kcen | 15.1 ± 0.6 | 13.9 | 18.9 | 19.81 ± 6.63 |
| mattcl-py | input-lanjian | 15.2 ± 0.7 | 14.1 | 18.1 | 19.88 ± 6.67 |
| pting | input-kcen | 53.6 ± 1.2 | 51.6 | 56.9 | 70.07 ± 23.36 |
| pting | input-lanjian | 53.9 ± 3.2 | 51.6 | 75.4 | 70.55 ± 23.84 |
| pting | input-mattcl | 54.3 ± 1.9 | 52.0 | 62.2 | 71.01 ± 23.74 |
| pting | input-pting | 57.0 ± 4.9 | 54.3 | 86.7 | 74.64 ± 25.63 |
| kcen | input-lanjian | 88.6 ± 1.9 | 86.5 | 97.5 | 115.98 ± 38.65 |
| kcen | input-kcen | 90.0 ± 1.4 | 87.9 | 92.9 | 117.83 ± 39.23 |
| kcen | input-mattcl | 90.1 ± 1.1 | 88.0 | 92.9 | 117.94 ± 39.25 |
| kcen | input-pting | 94.9 ± 2.9 | 92.6 | 108.5 | 124.13 ± 41.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|