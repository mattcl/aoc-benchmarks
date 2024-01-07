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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.5 | 1.4 | 1.01 ± 0.25 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.27 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.5 | 1.1 | 1.06 ± 0.25 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 5.7 | 3.55 ± 0.79 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.3 | 4.8 | 3.56 ± 0.77 |
| lanjian | input-lanjian | 3.5 ± 0.3 | 2.8 | 5.7 | 4.11 ± 0.91 |
| lanjian | input-kcen | 3.6 ± 0.5 | 2.8 | 6.4 | 4.17 ± 0.99 |
| mattcl-py | input-pting | 15.0 ± 0.7 | 13.9 | 17.9 | 17.54 ± 3.60 |
| mattcl-py | input-mattcl | 15.0 ± 0.6 | 14.4 | 18.2 | 17.56 ± 3.59 |
| mattcl-py | input-kcen | 15.0 ± 0.5 | 13.9 | 18.0 | 17.61 ± 3.58 |
| mattcl-py | input-lanjian | 15.0 ± 0.7 | 14.0 | 18.3 | 17.61 ± 3.63 |
| pting | input-mattcl | 54.7 ± 1.2 | 52.5 | 57.0 | 64.02 ± 12.89 |
| pting | input-lanjian | 54.8 ± 1.7 | 52.4 | 62.3 | 64.13 ± 12.99 |
| pting | input-kcen | 55.5 ± 1.3 | 53.2 | 58.6 | 64.93 ± 13.09 |
| pting | input-pting | 59.3 ± 6.1 | 56.2 | 97.6 | 69.36 ± 15.60 |
| kcen | input-lanjian | 84.7 ± 1.4 | 81.6 | 88.5 | 99.11 ± 19.92 |
| kcen | input-mattcl | 86.1 ± 1.4 | 83.9 | 89.0 | 100.75 ± 20.25 |
| kcen | input-kcen | 86.2 ± 1.9 | 83.5 | 92.0 | 100.83 ± 20.31 |
| kcen | input-pting | 90.1 ± 1.8 | 86.7 | 94.6 | 105.40 ± 21.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|