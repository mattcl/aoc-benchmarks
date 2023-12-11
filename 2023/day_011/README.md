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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.1 | 0.5 | 1.6 | 1.04 ± 0.22 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.7 | 1.05 ± 0.23 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.9 | 1.07 ± 0.27 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.0 | 4.9 | 2.77 ± 0.56 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.1 | 4.9 | 2.78 ± 0.54 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.4 | 6.4 | 3.17 ± 0.68 |
| lanjian | input-kcen | 3.4 ± 0.4 | 2.8 | 6.5 | 3.18 ± 0.66 |
| pting | input-lanjian | 52.6 ± 1.3 | 50.5 | 57.4 | 49.39 ± 8.43 |
| pting | input-kcen | 52.8 ± 1.3 | 50.8 | 57.1 | 49.58 ± 8.46 |
| pting | input-mattcl | 53.3 ± 2.1 | 51.3 | 65.2 | 50.00 ± 8.67 |
| mattcl-py | input-lanjian | 54.4 ± 1.4 | 52.4 | 57.6 | 51.04 ± 8.72 |
| mattcl-py | input-kcen | 54.9 ± 1.8 | 52.6 | 62.9 | 51.49 ± 8.86 |
| mattcl-py | input-mattcl | 55.8 ± 1.1 | 53.7 | 58.6 | 52.34 ± 8.90 |
| pting | input-pting | 55.9 ± 1.4 | 53.6 | 59.8 | 52.47 ± 8.95 |
| mattcl-py | input-pting | 58.3 ± 2.0 | 56.0 | 69.0 | 54.72 ± 9.42 |
| kcen | input-kcen | 84.8 ± 2.9 | 80.7 | 95.3 | 79.57 ± 13.70 |
| kcen | input-lanjian | 84.8 ± 1.4 | 81.4 | 87.6 | 79.59 ± 13.50 |
| kcen | input-mattcl | 86.9 ± 2.5 | 83.2 | 96.5 | 81.55 ± 13.97 |
| kcen | input-pting | 90.9 ± 1.5 | 87.9 | 95.6 | 85.25 ± 14.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|