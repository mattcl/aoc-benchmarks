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
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.32 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.30 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.6 | 1.6 | 1.07 ± 0.29 |
| lanjian | input-mattcl | 3.0 ± 0.5 | 1.9 | 5.9 | 3.39 ± 0.95 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.1 | 4.0 | 3.48 ± 0.86 |
| lanjian | input-kcen | 3.4 ± 0.3 | 2.6 | 5.1 | 3.82 ± 0.96 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.7 | 6.2 | 3.84 ± 1.00 |
| mattcl-py | input-mattcl | 14.9 ± 0.5 | 13.9 | 17.9 | 17.01 ± 3.97 |
| mattcl-py | input-lanjian | 14.9 ± 0.5 | 13.9 | 18.5 | 17.01 ± 3.98 |
| mattcl-py | input-pting | 15.0 ± 0.7 | 13.9 | 18.3 | 17.10 ± 4.04 |
| mattcl-py | input-kcen | 15.2 ± 0.6 | 14.1 | 17.7 | 17.28 ± 4.06 |
| pting | input-lanjian | 52.6 ± 1.8 | 50.8 | 60.1 | 59.91 ± 14.01 |
| pting | input-kcen | 53.5 ± 1.3 | 51.2 | 56.7 | 60.91 ± 14.18 |
| pting | input-mattcl | 53.7 ± 1.5 | 51.7 | 59.3 | 61.18 ± 14.27 |
| pting | input-pting | 55.9 ± 1.2 | 53.9 | 59.4 | 63.65 ± 14.80 |
| kcen | input-lanjian | 88.0 ± 1.3 | 85.0 | 91.1 | 100.23 ± 23.25 |
| kcen | input-kcen | 89.6 ± 1.7 | 87.2 | 94.5 | 102.04 ± 23.70 |
| kcen | input-mattcl | 89.9 ± 1.9 | 86.9 | 96.6 | 102.36 ± 23.80 |
| kcen | input-pting | 93.6 ± 2.0 | 90.8 | 102.1 | 106.66 ± 24.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|