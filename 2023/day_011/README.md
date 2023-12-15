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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.8 | 1.02 ± 0.23 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.9 | 1.02 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.22 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 1.8 | 5.4 | 2.55 ± 0.47 |
| lanjian | input-pting | 3.0 ± 2.7 | 1.7 | 39.8 | 2.57 ± 2.31 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.7 | 6.7 | 2.91 ± 0.58 |
| lanjian | input-kcen | 3.4 ± 0.4 | 2.7 | 6.4 | 2.95 ± 0.59 |
| pting | input-lanjian | 53.6 ± 2.1 | 51.5 | 63.3 | 45.94 ± 7.17 |
| pting | input-kcen | 54.0 ± 1.4 | 51.9 | 61.0 | 46.31 ± 7.09 |
| pting | input-mattcl | 54.1 ± 1.8 | 52.1 | 61.3 | 46.40 ± 7.18 |
| mattcl-py | input-lanjian | 55.3 ± 1.1 | 53.4 | 60.1 | 47.42 ± 7.23 |
| mattcl-py | input-kcen | 55.9 ± 1.1 | 54.5 | 59.4 | 47.91 ± 7.30 |
| pting | input-pting | 56.1 ± 1.0 | 54.4 | 58.4 | 48.12 ± 7.32 |
| mattcl-py | input-mattcl | 56.9 ± 1.2 | 55.0 | 60.8 | 48.78 ± 7.44 |
| mattcl-py | input-pting | 58.7 ± 1.0 | 56.6 | 61.7 | 50.32 ± 7.65 |
| kcen | input-lanjian | 85.5 ± 1.3 | 83.6 | 88.3 | 73.32 ± 11.14 |
| kcen | input-mattcl | 87.3 ± 1.7 | 84.6 | 91.7 | 74.87 ± 11.41 |
| kcen | input-kcen | 88.1 ± 3.5 | 84.4 | 101.2 | 75.54 ± 11.81 |
| kcen | input-pting | 91.2 ± 2.0 | 87.7 | 98.2 | 78.20 ± 11.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|