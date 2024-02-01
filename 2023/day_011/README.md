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
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.1 | 1.02 ± 0.27 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.28 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.28 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.5 | 5.6 | 3.56 ± 0.83 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.3 | 5.9 | 3.57 ± 0.84 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 2.9 | 5.3 | 4.24 ± 0.96 |
| lanjian | input-kcen | 3.8 ± 0.5 | 2.9 | 6.7 | 4.34 ± 1.02 |
| mattcl-py | input-lanjian | 15.1 ± 0.5 | 14.1 | 17.8 | 17.36 ± 3.55 |
| mattcl-py | input-mattcl | 15.2 ± 0.7 | 14.4 | 18.4 | 17.39 ± 3.59 |
| mattcl-py | input-pting | 15.2 ± 0.7 | 13.8 | 18.3 | 17.42 ± 3.59 |
| mattcl-py | input-kcen | 15.2 ± 0.6 | 14.2 | 18.9 | 17.49 ± 3.60 |
| pting | input-lanjian | 53.8 ± 1.8 | 51.8 | 63.7 | 61.75 ± 12.61 |
| pting | input-mattcl | 54.2 ± 1.4 | 52.2 | 60.2 | 62.17 ± 12.62 |
| pting | input-kcen | 54.5 ± 1.7 | 52.5 | 60.5 | 62.50 ± 12.73 |
| pting | input-pting | 57.1 ± 1.8 | 54.8 | 65.7 | 65.49 ± 13.35 |
| kcen | input-lanjian | 84.5 ± 1.3 | 82.5 | 89.5 | 96.90 ± 19.57 |
| kcen | input-mattcl | 87.0 ± 1.2 | 85.0 | 90.1 | 99.82 ± 20.15 |
| kcen | input-kcen | 87.5 ± 1.5 | 85.4 | 92.1 | 100.35 ± 20.28 |
| kcen | input-pting | 90.3 ± 1.6 | 88.0 | 93.5 | 103.59 ± 20.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|