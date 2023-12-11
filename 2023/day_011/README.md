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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.25 |
| mattcl | input-mattcl | 1.1 ± 0.1 | 0.6 | 1.3 | 1.03 ± 0.22 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.6 | 1.05 ± 0.26 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 2.0 | 4.0 | 2.74 ± 0.54 |
| lanjian | input-pting | 3.0 ± 0.3 | 1.9 | 5.6 | 2.82 ± 0.59 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.6 | 5.0 | 2.96 ± 0.56 |
| lanjian | input-kcen | 3.2 ± 0.3 | 2.6 | 4.8 | 3.01 ± 0.61 |
| pting | input-lanjian | 51.9 ± 1.2 | 50.2 | 54.6 | 49.46 ± 8.56 |
| pting | input-kcen | 52.0 ± 1.4 | 50.4 | 57.4 | 49.55 ± 8.61 |
| pting | input-mattcl | 52.8 ± 1.3 | 50.9 | 57.6 | 50.25 ± 8.71 |
| mattcl-py | input-lanjian | 54.1 ± 1.5 | 52.7 | 62.1 | 51.55 ± 8.95 |
| mattcl-py | input-kcen | 54.2 ± 1.6 | 52.2 | 62.7 | 51.59 ± 8.99 |
| pting | input-pting | 55.3 ± 1.4 | 53.2 | 61.1 | 52.65 ± 9.13 |
| mattcl-py | input-mattcl | 55.6 ± 1.3 | 54.0 | 61.8 | 52.97 ± 9.17 |
| mattcl-py | input-pting | 57.8 ± 1.1 | 56.3 | 61.5 | 55.03 ± 9.50 |
| kcen | input-lanjian | 88.2 ± 1.2 | 85.9 | 91.1 | 83.96 ± 14.45 |
| kcen | input-kcen | 88.2 ± 2.0 | 85.6 | 95.5 | 84.02 ± 14.54 |
| kcen | input-mattcl | 90.4 ± 1.4 | 87.9 | 93.2 | 86.12 ± 14.84 |
| kcen | input-pting | 94.8 ± 1.2 | 92.4 | 97.0 | 90.28 ± 15.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|