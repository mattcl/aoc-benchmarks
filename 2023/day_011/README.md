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
| mattcl | input-pting | 0.9 ± 0.1 | 0.2 | 1.0 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.25 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.1 | 1.05 ± 0.22 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.05 ± 0.26 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.1 | 5.5 | 3.54 ± 0.68 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 5.8 | 3.54 ± 0.67 |
| lanjian | input-kcen | 3.4 ± 0.4 | 2.7 | 5.0 | 3.95 ± 0.78 |
| lanjian | input-lanjian | 3.4 ± 0.3 | 2.7 | 5.5 | 3.99 ± 0.76 |
| mattcl-py | input-pting | 14.9 ± 0.6 | 13.8 | 18.0 | 17.30 ± 2.93 |
| mattcl-py | input-kcen | 14.9 ± 0.5 | 13.9 | 18.3 | 17.36 ± 2.90 |
| mattcl-py | input-lanjian | 14.9 ± 0.5 | 13.9 | 18.2 | 17.37 ± 2.89 |
| mattcl-py | input-mattcl | 14.9 ± 0.6 | 13.9 | 17.5 | 17.38 ± 2.92 |
| pting | input-lanjian | 53.3 ± 1.1 | 51.4 | 57.5 | 62.08 ± 10.24 |
| pting | input-kcen | 53.6 ± 1.1 | 51.6 | 56.6 | 62.35 ± 10.28 |
| pting | input-mattcl | 54.1 ± 2.2 | 51.9 | 65.4 | 62.93 ± 10.62 |
| pting | input-pting | 56.4 ± 1.5 | 54.2 | 61.1 | 65.71 ± 10.90 |
| kcen | input-lanjian | 84.8 ± 1.6 | 82.6 | 89.4 | 98.76 ± 16.27 |
| kcen | input-mattcl | 85.7 ± 1.5 | 83.8 | 89.9 | 99.74 ± 16.42 |
| kcen | input-kcen | 86.2 ± 2.2 | 83.3 | 94.0 | 100.35 ± 16.62 |
| kcen | input-pting | 90.1 ± 1.4 | 88.0 | 93.5 | 104.88 ± 17.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|