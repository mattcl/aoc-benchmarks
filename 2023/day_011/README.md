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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.6 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.8 | 1.01 ± 0.20 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.6 | 1.02 ± 0.20 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.22 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 4.7 | 2.73 ± 0.46 |
| lanjian | input-mattcl | 3.2 ± 0.3 | 2.3 | 5.6 | 2.82 ± 0.48 |
| lanjian | input-kcen | 3.7 ± 0.4 | 2.9 | 5.9 | 3.27 ± 0.54 |
| lanjian | input-lanjian | 3.7 ± 0.5 | 3.2 | 7.3 | 3.32 ± 0.60 |
| mattcl-py | input-lanjian | 55.3 ± 1.2 | 53.6 | 60.9 | 49.03 ± 6.67 |
| mattcl-py | input-kcen | 55.7 ± 1.2 | 54.0 | 59.5 | 49.43 ± 6.72 |
| mattcl-py | input-mattcl | 56.8 ± 1.0 | 55.2 | 59.8 | 50.34 ± 6.81 |
| pting | input-mattcl | 58.4 ± 1.6 | 55.4 | 62.2 | 51.74 ± 7.09 |
| pting | input-lanjian | 58.4 ± 1.9 | 54.7 | 63.7 | 51.75 ± 7.14 |
| pting | input-kcen | 58.7 ± 1.5 | 56.2 | 63.4 | 52.06 ± 7.12 |
| mattcl-py | input-pting | 59.0 ± 1.5 | 56.3 | 64.0 | 52.28 ± 7.14 |
| pting | input-pting | 61.8 ± 1.5 | 58.1 | 64.8 | 54.77 ± 7.46 |
| kcen | input-lanjian | 84.9 ± 1.9 | 81.6 | 90.7 | 75.28 ± 10.24 |
| kcen | input-kcen | 86.0 ± 2.9 | 83.2 | 97.3 | 76.28 ± 10.55 |
| kcen | input-mattcl | 87.1 ± 2.6 | 84.1 | 94.9 | 77.27 ± 10.62 |
| kcen | input-pting | 90.6 ± 2.5 | 88.0 | 101.5 | 80.32 ± 11.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|