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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.26 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.4 | 1.1 | 1.02 ± 0.25 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 2.5 | 1.04 ± 0.31 |
| lanjian | input-pting | 3.3 ± 0.5 | 2.3 | 6.4 | 3.74 ± 0.90 |
| lanjian | input-mattcl | 3.3 ± 0.6 | 2.3 | 5.9 | 3.75 ± 0.95 |
| lanjian | input-lanjian | 3.8 ± 0.6 | 2.9 | 7.5 | 4.38 ± 1.05 |
| lanjian | input-kcen | 3.8 ± 0.4 | 3.2 | 5.8 | 4.39 ± 0.93 |
| mattcl-py | input-pting | 15.2 ± 0.7 | 13.9 | 18.1 | 17.42 ± 3.34 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 14.0 | 18.0 | 17.46 ± 3.33 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.2 | 18.3 | 17.48 ± 3.35 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 13.9 | 18.3 | 17.59 ± 3.36 |
| pting | input-lanjian | 53.4 ± 1.1 | 51.5 | 55.9 | 61.38 ± 11.54 |
| pting | input-mattcl | 53.7 ± 1.1 | 52.0 | 56.7 | 61.75 ± 11.62 |
| pting | input-kcen | 53.9 ± 1.4 | 52.0 | 59.2 | 61.89 ± 11.68 |
| pting | input-pting | 56.3 ± 1.0 | 54.2 | 58.7 | 64.68 ± 12.15 |
| kcen | input-lanjian | 85.4 ± 1.5 | 83.2 | 89.3 | 98.13 ± 18.44 |
| kcen | input-mattcl | 86.9 ± 1.5 | 84.3 | 89.3 | 99.90 ± 18.76 |
| kcen | input-kcen | 87.4 ± 1.8 | 84.2 | 93.1 | 100.42 ± 18.90 |
| kcen | input-pting | 90.9 ± 1.4 | 87.8 | 93.5 | 104.50 ± 19.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|