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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 2.0 | 1.02 ± 0.24 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.23 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.7 | 1.7 | 1.06 ± 0.21 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 2.1 | 5.5 | 2.58 ± 0.50 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.1 | 5.0 | 2.64 ± 0.47 |
| lanjian | input-lanjian | 3.3 ± 0.4 | 2.7 | 4.9 | 2.88 ± 0.56 |
| lanjian | input-kcen | 3.3 ± 0.5 | 2.4 | 6.1 | 2.93 ± 0.62 |
| pting | input-lanjian | 52.4 ± 1.3 | 50.6 | 55.4 | 46.11 ± 7.24 |
| pting | input-mattcl | 53.3 ± 1.9 | 50.9 | 60.0 | 46.89 ± 7.45 |
| pting | input-kcen | 53.6 ± 6.7 | 50.8 | 102.8 | 47.18 ± 9.40 |
| mattcl-py | input-kcen | 54.2 ± 1.3 | 51.6 | 57.3 | 47.69 ± 7.48 |
| mattcl-py | input-lanjian | 54.3 ± 1.2 | 52.4 | 57.7 | 47.81 ± 7.48 |
| mattcl-py | input-mattcl | 55.9 ± 1.6 | 53.6 | 61.2 | 49.21 ± 7.75 |
| pting | input-pting | 56.1 ± 1.4 | 53.7 | 59.7 | 49.41 ± 7.75 |
| mattcl-py | input-pting | 58.3 ± 1.4 | 56.1 | 61.5 | 51.36 ± 8.05 |
| kcen | input-kcen | 84.1 ± 1.8 | 81.4 | 90.3 | 74.05 ± 11.58 |
| kcen | input-lanjian | 84.8 ± 2.5 | 81.7 | 93.1 | 74.65 ± 11.78 |
| kcen | input-mattcl | 85.9 ± 1.4 | 83.6 | 90.9 | 75.62 ± 11.79 |
| kcen | input-pting | 90.4 ± 2.4 | 86.9 | 101.0 | 79.59 ± 12.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|