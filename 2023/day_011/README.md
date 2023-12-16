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
| mattcl | input-mattcl | 0.8 ± 3.5 | 0.0 | 50.0 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.0 | 1.0 | 1.02 ± 4.72 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.2 | 1.04 ± 4.79 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.1 | 1.0 | 1.09 ± 5.06 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 1.9 | 5.1 | 3.78 ± 17.48 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.0 | 4.0 | 3.89 ± 17.99 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.5 | 5.7 | 4.44 ± 20.50 |
| lanjian | input-kcen | 3.4 ± 0.6 | 2.5 | 6.4 | 4.48 ± 20.69 |
| mattcl-py | input-pting | 14.9 ± 0.6 | 13.8 | 18.1 | 19.63 ± 90.71 |
| mattcl-py | input-kcen | 15.0 ± 0.5 | 13.8 | 17.6 | 19.80 ± 91.51 |
| mattcl-py | input-mattcl | 15.2 ± 3.2 | 13.9 | 58.3 | 19.99 ± 92.45 |
| mattcl-py | input-lanjian | 15.3 ± 3.0 | 13.9 | 55.4 | 20.09 ± 92.89 |
| pting | input-lanjian | 53.1 ± 1.1 | 51.4 | 56.3 | 69.89 ± 322.94 |
| pting | input-mattcl | 53.5 ± 1.2 | 51.4 | 56.9 | 70.42 ± 325.39 |
| pting | input-kcen | 53.6 ± 1.6 | 51.5 | 57.5 | 70.52 ± 325.84 |
| pting | input-pting | 56.3 ± 1.4 | 54.4 | 60.1 | 74.06 ± 342.21 |
| kcen | input-lanjian | 88.2 ± 1.4 | 85.4 | 91.5 | 116.12 ± 536.53 |
| kcen | input-mattcl | 89.3 ± 1.9 | 87.1 | 95.8 | 117.63 ± 543.50 |
| kcen | input-kcen | 90.2 ± 2.4 | 87.3 | 99.4 | 118.77 ± 548.79 |
| kcen | input-pting | 94.2 ± 1.7 | 92.1 | 99.5 | 123.98 ± 572.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|