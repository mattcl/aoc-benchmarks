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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.3 | 1.04 ± 0.22 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.8 | 1.04 ± 0.23 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 2.5 | 1.05 ± 0.27 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.0 | 5.0 | 2.60 ± 0.52 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.1 | 3.8 | 2.66 ± 0.50 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.6 | 5.4 | 2.99 ± 0.63 |
| lanjian | input-kcen | 3.4 ± 0.5 | 2.6 | 6.6 | 3.01 ± 0.66 |
| pting | input-lanjian | 53.3 ± 1.5 | 51.3 | 60.2 | 46.86 ± 8.00 |
| pting | input-kcen | 54.1 ± 1.5 | 52.1 | 59.3 | 47.52 ± 8.11 |
| pting | input-mattcl | 54.9 ± 6.0 | 51.9 | 95.5 | 48.25 ± 9.67 |
| mattcl-py | input-lanjian | 55.4 ± 1.2 | 53.6 | 59.1 | 48.69 ± 8.26 |
| mattcl-py | input-mattcl | 56.4 ± 1.1 | 54.5 | 60.1 | 49.59 ± 8.41 |
| mattcl-py | input-kcen | 56.5 ± 1.9 | 54.2 | 64.6 | 49.65 ± 8.52 |
| pting | input-pting | 56.5 ± 1.6 | 54.4 | 61.2 | 49.67 ± 8.47 |
| mattcl-py | input-pting | 58.7 ± 1.3 | 56.8 | 62.4 | 51.59 ± 8.76 |
| kcen | input-lanjian | 85.4 ± 3.2 | 82.6 | 102.5 | 75.10 ± 12.94 |
| kcen | input-kcen | 87.1 ± 1.3 | 84.9 | 90.3 | 76.56 ± 12.94 |
| kcen | input-mattcl | 87.3 ± 1.9 | 84.2 | 93.8 | 76.75 ± 13.03 |
| kcen | input-pting | 90.9 ± 2.3 | 88.0 | 97.2 | 79.94 ± 13.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|