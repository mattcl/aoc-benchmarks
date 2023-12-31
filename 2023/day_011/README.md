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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.5 | 1.00 ± 0.25 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.2 | 1.2 | 1.01 ± 0.23 |
| mattcl | input-pting | 1.0 ± 0.1 | 0.4 | 1.1 | 1.03 ± 0.22 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 4.8 | 3.17 ± 0.62 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.2 | 5.5 | 3.19 ± 0.65 |
| lanjian | input-lanjian | 3.6 ± 0.3 | 2.9 | 5.2 | 3.64 ± 0.72 |
| lanjian | input-kcen | 3.6 ± 0.4 | 2.8 | 5.2 | 3.72 ± 0.75 |
| mattcl-py | input-pting | 15.2 ± 0.6 | 14.2 | 18.1 | 15.54 ± 2.77 |
| mattcl-py | input-lanjian | 15.2 ± 0.5 | 14.4 | 18.5 | 15.55 ± 2.76 |
| mattcl-py | input-mattcl | 15.3 ± 0.6 | 14.2 | 18.4 | 15.61 ± 2.80 |
| mattcl-py | input-kcen | 15.5 ± 0.6 | 14.4 | 18.4 | 15.79 ± 2.83 |
| pting | input-mattcl | 54.6 ± 1.3 | 52.3 | 60.8 | 55.73 ± 9.82 |
| pting | input-kcen | 54.6 ± 1.5 | 52.6 | 60.7 | 55.75 ± 9.85 |
| pting | input-lanjian | 54.7 ± 3.2 | 52.0 | 76.4 | 55.80 ± 10.27 |
| pting | input-pting | 57.4 ± 1.3 | 55.0 | 60.8 | 58.54 ± 10.30 |
| kcen | input-lanjian | 85.5 ± 2.3 | 83.5 | 96.7 | 87.28 ± 15.41 |
| kcen | input-kcen | 86.7 ± 1.9 | 84.2 | 93.9 | 88.53 ± 15.57 |
| kcen | input-mattcl | 86.9 ± 1.1 | 85.2 | 89.7 | 88.66 ± 15.51 |
| kcen | input-pting | 91.1 ± 1.9 | 88.9 | 98.0 | 93.01 ± 16.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|