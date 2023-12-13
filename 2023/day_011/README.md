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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.6 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.5 | 1.7 | 1.02 ± 0.23 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.6 | 1.8 | 1.02 ± 0.24 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.25 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.2 | 5.9 | 2.73 ± 0.55 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.2 | 3.9 | 2.73 ± 0.53 |
| lanjian | input-kcen | 3.5 ± 0.3 | 3.1 | 5.9 | 3.13 ± 0.61 |
| lanjian | input-lanjian | 3.6 ± 0.5 | 2.9 | 6.0 | 3.18 ± 0.69 |
| pting | input-lanjian | 52.2 ± 1.5 | 50.4 | 60.0 | 46.51 ± 8.04 |
| pting | input-kcen | 53.4 ± 1.9 | 50.5 | 61.0 | 47.51 ± 8.26 |
| pting | input-mattcl | 53.7 ± 2.4 | 51.7 | 65.7 | 47.77 ± 8.42 |
| mattcl-py | input-lanjian | 54.3 ± 1.2 | 52.5 | 57.7 | 48.33 ± 8.31 |
| mattcl-py | input-kcen | 55.3 ± 1.5 | 53.5 | 61.8 | 49.23 ± 8.49 |
| mattcl-py | input-mattcl | 56.0 ± 1.2 | 54.1 | 59.4 | 49.84 ± 8.56 |
| pting | input-pting | 56.2 ± 2.9 | 53.5 | 71.8 | 49.99 ± 8.91 |
| mattcl-py | input-pting | 57.9 ± 1.9 | 56.0 | 67.9 | 51.52 ± 8.94 |
| kcen | input-lanjian | 84.8 ± 2.1 | 82.4 | 91.6 | 75.47 ± 12.99 |
| kcen | input-kcen | 85.8 ± 1.9 | 83.1 | 92.4 | 76.41 ± 13.13 |
| kcen | input-mattcl | 86.8 ± 3.3 | 83.3 | 99.4 | 77.26 ± 13.50 |
| kcen | input-pting | 89.9 ± 3.0 | 86.6 | 98.9 | 80.03 ± 13.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|