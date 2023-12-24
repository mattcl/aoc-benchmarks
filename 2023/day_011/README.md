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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.1 | 1.00 ± 0.23 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.5 | 1.1 | 1.00 ± 0.22 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.2 | 1.4 | 1.03 ± 0.24 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.7 | 5.0 | 3.28 ± 0.63 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.7 | 3.28 ± 0.67 |
| lanjian | input-lanjian | 3.5 ± 0.3 | 3.1 | 5.2 | 3.74 ± 0.72 |
| lanjian | input-kcen | 3.5 ± 0.3 | 2.6 | 5.2 | 3.79 ± 0.74 |
| mattcl-py | input-lanjian | 15.2 ± 0.5 | 14.1 | 17.7 | 16.20 ± 2.81 |
| mattcl-py | input-kcen | 15.3 ± 0.7 | 14.1 | 18.4 | 16.33 ± 2.88 |
| mattcl-py | input-mattcl | 15.3 ± 0.6 | 14.2 | 18.9 | 16.33 ± 2.88 |
| mattcl-py | input-pting | 15.5 ± 0.8 | 13.9 | 20.3 | 16.57 ± 2.97 |
| pting | input-kcen | 53.1 ± 2.1 | 51.5 | 66.8 | 56.70 ± 9.95 |
| pting | input-lanjian | 53.3 ± 2.7 | 50.8 | 68.1 | 56.92 ± 10.14 |
| pting | input-mattcl | 53.7 ± 1.5 | 51.6 | 60.1 | 57.41 ± 9.94 |
| pting | input-pting | 56.2 ± 1.6 | 53.7 | 63.9 | 60.01 ± 10.40 |
| kcen | input-lanjian | 88.7 ± 1.2 | 86.8 | 92.2 | 94.78 ± 16.25 |
| kcen | input-kcen | 89.6 ± 1.2 | 87.7 | 92.6 | 95.79 ± 16.42 |
| kcen | input-mattcl | 90.4 ± 1.3 | 88.2 | 93.5 | 96.56 ± 16.56 |
| kcen | input-pting | 94.3 ± 1.7 | 90.9 | 98.9 | 100.82 ± 17.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|