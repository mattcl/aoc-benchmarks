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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.3 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.2 | 1.8 | 1.03 ± 0.27 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.5 | 1.6 | 1.05 ± 0.22 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.8 | 1.05 ± 0.23 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.3 | 5.7 | 2.83 ± 0.53 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.7 | 5.8 | 2.83 ± 0.50 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.9 | 5.1 | 3.25 ± 0.62 |
| lanjian | input-lanjian | 3.5 ± 0.5 | 3.0 | 6.6 | 3.27 ± 0.66 |
| pting | input-lanjian | 53.2 ± 1.3 | 51.0 | 57.9 | 49.29 ± 7.71 |
| pting | input-kcen | 53.5 ± 1.3 | 51.5 | 56.8 | 49.63 ± 7.76 |
| pting | input-mattcl | 53.7 ± 1.3 | 51.4 | 57.7 | 49.83 ± 7.80 |
| mattcl-py | input-kcen | 54.9 ± 0.8 | 53.5 | 57.1 | 50.92 ± 7.90 |
| mattcl-py | input-lanjian | 55.4 ± 2.0 | 53.3 | 65.4 | 51.33 ± 8.14 |
| pting | input-pting | 56.1 ± 1.6 | 54.2 | 60.6 | 52.03 ± 8.17 |
| mattcl-py | input-mattcl | 56.2 ± 1.0 | 54.7 | 58.5 | 52.12 ± 8.11 |
| mattcl-py | input-pting | 58.7 ± 1.5 | 56.7 | 64.7 | 54.45 ± 8.53 |
| kcen | input-lanjian | 84.9 ± 1.8 | 82.6 | 92.8 | 78.74 ± 12.28 |
| kcen | input-kcen | 86.2 ± 2.1 | 82.9 | 93.8 | 79.89 ± 12.50 |
| kcen | input-mattcl | 87.6 ± 1.9 | 85.2 | 93.1 | 81.22 ± 12.66 |
| kcen | input-pting | 90.4 ± 1.2 | 87.8 | 92.7 | 83.81 ± 12.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|