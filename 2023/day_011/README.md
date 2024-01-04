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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.01 ± 0.36 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.5 | 1.03 ± 0.39 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.04 ± 0.35 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.1 | 5.5 | 3.76 ± 1.07 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.1 | 5.1 | 3.76 ± 1.10 |
| lanjian | input-kcen | 3.4 ± 0.5 | 2.6 | 6.0 | 4.30 ± 1.31 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.7 | 5.8 | 4.31 ± 1.26 |
| mattcl-py | input-mattcl | 14.8 ± 0.5 | 13.8 | 18.1 | 18.64 ± 5.09 |
| mattcl-py | input-pting | 14.8 ± 0.6 | 13.7 | 17.6 | 18.68 ± 5.11 |
| mattcl-py | input-lanjian | 14.9 ± 0.6 | 13.8 | 17.6 | 18.80 ± 5.14 |
| mattcl-py | input-kcen | 15.0 ± 0.5 | 13.9 | 18.4 | 18.85 ± 5.15 |
| pting | input-lanjian | 52.8 ± 1.8 | 50.8 | 62.6 | 66.59 ± 18.17 |
| pting | input-mattcl | 53.3 ± 1.2 | 50.7 | 55.8 | 67.15 ± 18.25 |
| pting | input-kcen | 53.7 ± 1.6 | 51.5 | 60.0 | 67.68 ± 18.44 |
| pting | input-pting | 55.9 ± 1.6 | 53.9 | 63.5 | 70.52 ± 19.20 |
| kcen | input-lanjian | 85.7 ± 3.2 | 81.6 | 96.9 | 108.04 ± 29.53 |
| kcen | input-mattcl | 85.9 ± 1.6 | 83.4 | 89.7 | 108.29 ± 29.39 |
| kcen | input-kcen | 86.5 ± 1.9 | 83.0 | 90.7 | 109.10 ± 29.64 |
| kcen | input-pting | 89.5 ± 1.5 | 87.0 | 92.6 | 112.79 ± 30.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|