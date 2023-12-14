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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 2.0 | 1.01 ± 0.22 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.6 | 1.7 | 1.02 ± 0.20 |
| mattcl | input-kcen | 1.3 ± 4.1 | 0.3 | 58.7 | 1.12 ± 3.52 |
| lanjian | input-mattcl | 3.2 ± 0.4 | 2.4 | 4.8 | 2.73 ± 0.56 |
| lanjian | input-pting | 3.2 ± 0.4 | 2.4 | 5.6 | 2.79 ± 0.54 |
| lanjian | input-kcen | 3.8 ± 0.4 | 3.2 | 5.6 | 3.26 ± 0.59 |
| lanjian | input-lanjian | 3.8 ± 0.5 | 3.0 | 6.2 | 3.28 ± 0.65 |
| mattcl-py | input-lanjian | 55.4 ± 1.0 | 54.0 | 58.4 | 47.61 ± 7.44 |
| mattcl-py | input-kcen | 55.8 ± 1.3 | 54.4 | 62.6 | 47.94 ± 7.53 |
| mattcl-py | input-mattcl | 56.9 ± 1.0 | 55.4 | 59.6 | 48.88 ± 7.65 |
| pting | input-lanjian | 58.1 ± 1.9 | 54.6 | 62.8 | 49.89 ± 7.92 |
| pting | input-kcen | 58.5 ± 1.8 | 55.0 | 63.8 | 50.26 ± 7.96 |
| pting | input-mattcl | 58.7 ± 1.7 | 54.9 | 62.9 | 50.44 ± 7.98 |
| mattcl-py | input-pting | 58.9 ± 1.0 | 57.0 | 61.6 | 50.57 ± 7.91 |
| pting | input-pting | 61.3 ± 1.6 | 57.9 | 64.9 | 52.65 ± 8.30 |
| kcen | input-lanjian | 84.9 ± 1.7 | 82.7 | 91.1 | 72.89 ± 11.42 |
| kcen | input-kcen | 86.1 ± 6.2 | 82.8 | 120.1 | 73.95 ± 12.67 |
| kcen | input-mattcl | 86.8 ± 2.1 | 84.0 | 94.5 | 74.55 ± 11.73 |
| kcen | input-pting | 90.1 ± 1.2 | 87.7 | 92.1 | 77.42 ± 12.07 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|