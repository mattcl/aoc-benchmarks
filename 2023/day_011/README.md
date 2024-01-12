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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 ± 0.25 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.2 | 1.00 ± 0.28 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.26 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.2 | 3.7 | 3.36 ± 0.68 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.2 | 5.4 | 3.40 ± 0.72 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.8 | 6.5 | 3.75 ± 0.85 |
| lanjian | input-kcen | 3.6 ± 2.4 | 2.6 | 36.9 | 3.94 ± 2.73 |
| mattcl-py | input-pting | 14.9 ± 0.6 | 13.9 | 17.7 | 16.37 ± 3.13 |
| mattcl-py | input-mattcl | 15.0 ± 0.6 | 13.9 | 17.8 | 16.41 ± 3.15 |
| mattcl-py | input-lanjian | 15.0 ± 0.5 | 13.8 | 17.9 | 16.41 ± 3.12 |
| mattcl-py | input-kcen | 15.3 ± 3.1 | 14.1 | 57.5 | 16.75 ± 4.61 |
| pting | input-lanjian | 52.6 ± 1.2 | 51.0 | 57.4 | 57.70 ± 10.89 |
| pting | input-mattcl | 53.6 ± 1.5 | 51.5 | 56.6 | 58.73 ± 11.13 |
| pting | input-kcen | 53.6 ± 1.4 | 51.5 | 56.9 | 58.80 ± 11.13 |
| pting | input-pting | 55.9 ± 1.7 | 54.2 | 63.5 | 61.31 ± 11.64 |
| kcen | input-lanjian | 84.8 ± 1.3 | 82.1 | 88.0 | 92.99 ± 17.49 |
| kcen | input-kcen | 86.6 ± 1.8 | 83.7 | 93.0 | 94.98 ± 17.91 |
| kcen | input-mattcl | 87.3 ± 2.0 | 83.4 | 93.5 | 95.70 ± 18.07 |
| kcen | input-pting | 90.3 ± 2.2 | 87.8 | 98.3 | 99.08 ± 18.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|