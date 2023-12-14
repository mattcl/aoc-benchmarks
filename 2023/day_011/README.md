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
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.8 | 1.01 ± 0.25 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.9 | 1.03 ± 0.24 |
| mattcl | input-kcen | 1.3 ± 3.6 | 0.4 | 51.6 | 1.08 ± 2.97 |
| lanjian | input-pting | 3.2 ± 0.2 | 2.4 | 5.1 | 2.62 ± 0.52 |
| lanjian | input-mattcl | 3.2 ± 0.3 | 2.4 | 4.9 | 2.64 ± 0.53 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 3.2 | 6.0 | 3.03 ± 0.65 |
| lanjian | input-kcen | 3.7 ± 0.4 | 3.0 | 6.7 | 3.03 ± 0.66 |
| pting | input-lanjian | 53.2 ± 1.6 | 51.2 | 58.6 | 43.90 ± 8.11 |
| pting | input-kcen | 53.5 ± 1.3 | 51.6 | 56.7 | 44.16 ± 8.13 |
| pting | input-mattcl | 53.8 ± 1.3 | 51.7 | 57.2 | 44.43 ± 8.18 |
| mattcl-py | input-lanjian | 55.3 ± 1.5 | 53.8 | 64.4 | 45.64 ± 8.42 |
| mattcl-py | input-kcen | 56.0 ± 4.4 | 53.7 | 86.1 | 46.19 ± 9.18 |
| pting | input-pting | 56.2 ± 1.2 | 54.2 | 61.1 | 46.39 ± 8.52 |
| mattcl-py | input-mattcl | 56.3 ± 1.1 | 54.8 | 60.1 | 46.49 ± 8.53 |
| mattcl-py | input-pting | 58.8 ± 1.4 | 57.0 | 64.3 | 48.51 ± 8.93 |
| kcen | input-lanjian | 85.9 ± 2.5 | 83.3 | 94.4 | 70.93 ± 13.10 |
| kcen | input-kcen | 87.1 ± 3.9 | 83.7 | 104.2 | 71.89 ± 13.50 |
| kcen | input-mattcl | 87.1 ± 2.3 | 84.5 | 95.4 | 71.91 ± 13.26 |
| kcen | input-pting | 90.3 ± 1.3 | 88.3 | 93.1 | 74.52 ± 13.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|