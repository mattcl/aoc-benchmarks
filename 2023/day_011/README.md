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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.2 | 1.00 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.24 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.5 | 1.2 | 1.04 ± 0.22 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.5 | 1.5 | 1.05 ± 0.24 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.2 | 5.6 | 3.20 ± 0.62 |
| lanjian | input-mattcl | 3.2 ± 0.4 | 2.3 | 5.9 | 3.20 ± 0.67 |
| lanjian | input-lanjian | 3.6 ± 0.4 | 2.8 | 6.7 | 3.63 ± 0.74 |
| lanjian | input-kcen | 3.7 ± 0.4 | 3.2 | 6.5 | 3.71 ± 0.76 |
| mattcl-py | input-pting | 15.3 ± 0.7 | 14.0 | 18.4 | 15.50 ± 2.74 |
| mattcl-py | input-mattcl | 15.3 ± 0.7 | 14.0 | 18.6 | 15.54 ± 2.75 |
| mattcl-py | input-lanjian | 15.4 ± 0.7 | 14.1 | 18.5 | 15.61 ± 2.77 |
| mattcl-py | input-kcen | 15.6 ± 2.0 | 14.3 | 41.8 | 15.84 ± 3.36 |
| pting | input-lanjian | 54.1 ± 1.9 | 52.1 | 61.5 | 54.93 ± 9.58 |
| pting | input-mattcl | 54.3 ± 1.6 | 52.0 | 60.4 | 55.07 ± 9.54 |
| pting | input-kcen | 55.4 ± 7.8 | 52.5 | 108.7 | 56.22 ± 12.47 |
| pting | input-pting | 57.2 ± 5.0 | 54.3 | 89.3 | 58.03 ± 11.14 |
| kcen | input-lanjian | 84.7 ± 1.3 | 82.5 | 88.2 | 86.00 ± 14.75 |
| kcen | input-kcen | 86.3 ± 2.9 | 83.7 | 101.6 | 87.56 ± 15.25 |
| kcen | input-mattcl | 86.3 ± 1.6 | 84.0 | 91.1 | 87.58 ± 15.05 |
| kcen | input-pting | 90.5 ± 3.0 | 88.1 | 106.0 | 91.83 ± 15.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|