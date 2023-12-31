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
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.07 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.7 | 1.07 ± 0.29 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.5 | 5.5 | 3.57 ± 0.83 |
| lanjian | input-mattcl | 3.0 ± 0.4 | 2.2 | 5.7 | 3.59 ± 0.88 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.6 | 5.8 | 4.06 ± 0.95 |
| lanjian | input-kcen | 3.5 ± 0.4 | 3.0 | 5.5 | 4.20 ± 1.01 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 13.8 | 18.5 | 17.97 ± 3.83 |
| mattcl-py | input-pting | 15.2 ± 0.8 | 14.1 | 18.5 | 18.05 ± 3.88 |
| mattcl-py | input-lanjian | 15.3 ± 0.6 | 14.3 | 18.1 | 18.06 ± 3.85 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 14.0 | 18.2 | 18.07 ± 3.84 |
| pting | input-lanjian | 54.2 ± 1.3 | 52.2 | 59.0 | 64.13 ± 13.50 |
| pting | input-mattcl | 54.3 ± 1.4 | 52.5 | 60.8 | 64.36 ± 13.56 |
| pting | input-kcen | 54.4 ± 1.7 | 52.4 | 63.4 | 64.45 ± 13.63 |
| pting | input-pting | 57.3 ± 1.2 | 55.6 | 60.8 | 67.90 ± 14.28 |
| kcen | input-lanjian | 85.4 ± 1.5 | 83.2 | 89.3 | 101.13 ± 21.23 |
| kcen | input-mattcl | 87.3 ± 1.6 | 84.8 | 91.3 | 103.40 ± 21.71 |
| kcen | input-kcen | 89.4 ± 9.3 | 84.7 | 129.7 | 105.86 ± 24.74 |
| kcen | input-pting | 91.8 ± 2.2 | 88.1 | 97.0 | 108.70 ± 22.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|