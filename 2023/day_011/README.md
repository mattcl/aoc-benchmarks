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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 ± 0.29 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.4 | 1.6 | 1.05 ± 0.28 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.1 | 1.08 ± 0.25 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.0 | 5.2 | 3.36 ± 0.75 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.1 | 5.7 | 3.41 ± 0.80 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.9 | 6.9 | 3.84 ± 0.90 |
| lanjian | input-lanjian | 3.5 ± 0.5 | 2.6 | 6.5 | 3.87 ± 0.95 |
| mattcl-py | input-pting | 15.2 ± 0.5 | 13.9 | 18.5 | 16.65 ± 3.42 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.3 | 18.3 | 16.71 ± 3.46 |
| mattcl-py | input-lanjian | 15.3 ± 0.6 | 14.4 | 18.1 | 16.80 ± 3.46 |
| mattcl-py | input-kcen | 15.4 ± 0.7 | 14.4 | 18.0 | 16.90 ± 3.51 |
| pting | input-lanjian | 53.9 ± 1.4 | 51.7 | 59.1 | 59.10 ± 12.07 |
| pting | input-kcen | 54.2 ± 1.0 | 52.3 | 56.6 | 59.45 ± 12.09 |
| pting | input-mattcl | 54.3 ± 1.5 | 52.2 | 57.3 | 59.51 ± 12.16 |
| pting | input-pting | 57.0 ± 2.2 | 54.6 | 64.9 | 62.45 ± 12.88 |
| kcen | input-lanjian | 85.3 ± 1.6 | 83.2 | 89.3 | 93.54 ± 19.02 |
| kcen | input-mattcl | 87.1 ± 1.5 | 84.8 | 91.1 | 95.50 ± 19.41 |
| kcen | input-kcen | 87.3 ± 1.9 | 84.1 | 92.1 | 95.71 ± 19.50 |
| kcen | input-pting | 90.4 ± 1.3 | 87.7 | 92.8 | 99.06 ± 20.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|