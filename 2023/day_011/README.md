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
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.2 | 1.06 ± 0.25 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.3 | 1.06 ± 0.26 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.07 ± 0.27 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.1 | 5.4 | 3.44 ± 0.72 |
| lanjian | input-pting | 3.1 ± 0.4 | 1.9 | 5.4 | 3.47 ± 0.79 |
| lanjian | input-lanjian | 3.5 ± 0.3 | 2.7 | 5.1 | 3.91 ± 0.79 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.6 | 6.2 | 4.00 ± 0.89 |
| mattcl-py | input-pting | 15.2 ± 0.6 | 14.2 | 18.9 | 17.24 ± 3.21 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 14.3 | 18.5 | 17.28 ± 3.22 |
| mattcl-py | input-mattcl | 15.3 ± 0.6 | 14.3 | 18.2 | 17.31 ± 3.25 |
| mattcl-py | input-kcen | 15.4 ± 0.7 | 14.4 | 18.8 | 17.51 ± 3.30 |
| pting | input-lanjian | 53.3 ± 2.0 | 51.1 | 63.5 | 60.42 ± 11.27 |
| pting | input-mattcl | 53.7 ± 1.5 | 51.6 | 57.5 | 60.83 ± 11.24 |
| pting | input-kcen | 53.7 ± 2.1 | 51.6 | 67.1 | 60.91 ± 11.38 |
| pting | input-pting | 56.5 ± 2.3 | 54.1 | 68.8 | 64.06 ± 12.00 |
| kcen | input-lanjian | 88.5 ± 1.1 | 86.6 | 90.4 | 100.38 ± 18.38 |
| kcen | input-kcen | 90.4 ± 1.2 | 88.8 | 92.7 | 102.48 ± 18.78 |
| kcen | input-mattcl | 90.6 ± 1.2 | 87.9 | 93.5 | 102.73 ± 18.82 |
| kcen | input-pting | 94.1 ± 1.6 | 91.2 | 98.5 | 106.63 ± 19.57 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|