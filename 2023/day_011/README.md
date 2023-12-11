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

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.1 | 0.5 | 1.6 | 1.04 ± 0.23 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.6 | 2.0 | 1.05 ± 0.25 |
| mattcl | input-pting | 1.1 ± 0.1 | 0.6 | 1.7 | 1.05 ± 0.23 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 2.0 | 5.0 | 2.70 ± 0.56 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.0 | 5.6 | 2.75 ± 0.56 |
| lanjian | input-kcen | 3.3 ± 0.5 | 2.6 | 5.9 | 3.02 ± 0.73 |
| lanjian | input-lanjian | 3.3 ± 0.4 | 2.5 | 5.9 | 3.08 ± 0.66 |
| pting | input-kcen | 52.2 ± 1.7 | 49.9 | 59.2 | 48.39 ± 8.54 |
| pting | input-lanjian | 52.3 ± 1.2 | 50.2 | 55.7 | 48.46 ± 8.47 |
| pting | input-mattcl | 53.6 ± 1.3 | 51.3 | 57.0 | 49.69 ± 8.70 |
| mattcl-py | input-lanjian | 54.2 ± 1.4 | 52.0 | 60.2 | 50.29 ± 8.82 |
| mattcl-py | input-kcen | 54.6 ± 2.1 | 52.6 | 65.2 | 50.68 ± 9.01 |
| mattcl-py | input-mattcl | 55.6 ± 1.2 | 53.8 | 58.5 | 51.59 ± 9.01 |
| pting | input-pting | 55.9 ± 1.4 | 53.5 | 59.3 | 51.84 ± 9.08 |
| mattcl-py | input-pting | 57.7 ± 1.3 | 55.7 | 61.9 | 53.51 ± 9.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|