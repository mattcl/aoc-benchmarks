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
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.6 | 1.00 ± 0.28 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.2 | 1.02 ± 0.26 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.4 | 2.8 | 1.07 ± 0.30 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.0 | 5.3 | 3.36 ± 0.74 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.3 | 3.36 ± 0.75 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.8 | 4.8 | 3.82 ± 0.86 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.6 | 5.3 | 3.85 ± 0.87 |
| mattcl-py | input-pting | 15.1 ± 0.5 | 14.3 | 17.8 | 16.57 ± 3.35 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 13.9 | 18.0 | 16.63 ± 3.37 |
| mattcl-py | input-lanjian | 15.2 ± 0.5 | 14.3 | 18.0 | 16.68 ± 3.38 |
| mattcl-py | input-kcen | 15.4 ± 0.6 | 14.4 | 18.4 | 16.82 ± 3.42 |
| pting | input-lanjian | 53.8 ± 1.6 | 51.4 | 59.0 | 58.87 ± 11.87 |
| pting | input-kcen | 54.0 ± 1.8 | 51.9 | 61.2 | 59.12 ± 11.94 |
| pting | input-mattcl | 54.8 ± 5.2 | 52.2 | 90.2 | 59.98 ± 13.24 |
| pting | input-pting | 57.4 ± 4.2 | 55.1 | 84.7 | 62.83 ± 13.32 |
| kcen | input-lanjian | 85.7 ± 2.0 | 82.6 | 91.6 | 93.75 ± 18.81 |
| kcen | input-kcen | 86.1 ± 1.1 | 83.7 | 88.1 | 94.28 ± 18.84 |
| kcen | input-mattcl | 87.0 ± 2.8 | 84.0 | 99.9 | 95.21 ± 19.23 |
| kcen | input-pting | 91.7 ± 6.0 | 87.8 | 117.7 | 100.39 ± 21.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|