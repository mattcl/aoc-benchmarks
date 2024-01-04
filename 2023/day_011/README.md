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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.1 | 1.01 ± 0.26 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.1 | 1.01 ± 0.24 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.2 | 1.1 | 1.03 ± 0.25 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.3 | 5.5 | 3.35 ± 0.73 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.6 | 3.35 ± 0.70 |
| lanjian | input-lanjian | 3.5 ± 0.3 | 2.7 | 5.0 | 3.82 ± 0.77 |
| lanjian | input-kcen | 3.6 ± 0.4 | 2.8 | 5.1 | 3.95 ± 0.84 |
| mattcl-py | input-pting | 15.1 ± 0.5 | 14.1 | 17.4 | 16.64 ± 3.18 |
| mattcl-py | input-kcen | 15.3 ± 0.7 | 14.0 | 18.2 | 16.81 ± 3.25 |
| mattcl-py | input-mattcl | 15.3 ± 1.6 | 14.0 | 35.8 | 16.82 ± 3.63 |
| mattcl-py | input-lanjian | 15.7 ± 3.4 | 13.9 | 49.7 | 17.31 ± 4.96 |
| pting | input-lanjian | 52.8 ± 1.2 | 51.2 | 56.3 | 58.10 ± 11.01 |
| pting | input-kcen | 54.0 ± 1.8 | 51.4 | 60.7 | 59.35 ± 11.35 |
| pting | input-mattcl | 54.3 ± 4.4 | 51.8 | 84.9 | 59.66 ± 12.23 |
| pting | input-pting | 56.2 ± 1.5 | 53.9 | 62.1 | 61.82 ± 11.75 |
| kcen | input-lanjian | 88.5 ± 1.6 | 85.4 | 92.6 | 97.28 ± 18.40 |
| kcen | input-mattcl | 89.8 ± 1.3 | 87.7 | 93.1 | 98.71 ± 18.64 |
| kcen | input-kcen | 90.0 ± 1.4 | 87.9 | 92.5 | 99.01 ± 18.70 |
| kcen | input-pting | 93.9 ± 1.7 | 91.7 | 97.9 | 103.30 ± 19.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|