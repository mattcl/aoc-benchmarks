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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.6 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.33 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.5 | 1.04 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.33 |
| lanjian | input-mattcl | 2.9 ± 0.4 | 2.0 | 5.2 | 3.57 ± 0.99 |
| lanjian | input-pting | 3.0 ± 2.1 | 1.9 | 32.7 | 3.71 ± 2.77 |
| lanjian | input-lanjian | 3.3 ± 0.4 | 2.7 | 5.5 | 4.07 ± 1.13 |
| lanjian | input-kcen | 3.3 ± 0.4 | 2.6 | 5.4 | 4.10 ± 1.12 |
| mattcl-py | input-pting | 15.1 ± 0.5 | 14.0 | 18.2 | 18.50 ± 4.66 |
| mattcl-py | input-lanjian | 15.2 ± 0.5 | 13.9 | 18.4 | 18.58 ± 4.68 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.2 | 17.9 | 18.64 ± 4.72 |
| mattcl-py | input-kcen | 15.3 ± 0.7 | 14.0 | 18.4 | 18.79 ± 4.77 |
| pting | input-mattcl | 53.7 ± 1.4 | 52.0 | 58.4 | 65.87 ± 16.52 |
| pting | input-kcen | 53.9 ± 3.3 | 51.6 | 76.9 | 66.02 ± 16.98 |
| pting | input-lanjian | 53.9 ± 3.9 | 51.0 | 80.2 | 66.09 ± 17.18 |
| pting | input-pting | 56.3 ± 1.3 | 54.5 | 60.3 | 68.98 ± 17.29 |
| kcen | input-lanjian | 88.7 ± 1.7 | 86.1 | 94.0 | 108.72 ± 27.21 |
| kcen | input-kcen | 90.2 ± 1.5 | 87.8 | 93.6 | 110.59 ± 27.66 |
| kcen | input-mattcl | 90.5 ± 1.1 | 88.5 | 92.6 | 110.92 ± 27.71 |
| kcen | input-pting | 95.5 ± 3.3 | 92.0 | 109.9 | 117.11 ± 29.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|