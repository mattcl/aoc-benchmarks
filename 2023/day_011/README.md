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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.02 ± 0.33 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.3 | 1.03 ± 0.31 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 1.9 | 3.5 | 3.58 ± 0.89 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.1 | 4.3 | 3.74 ± 0.91 |
| lanjian | input-lanjian | 3.3 ± 0.5 | 2.4 | 6.3 | 4.19 ± 1.14 |
| lanjian | input-kcen | 3.3 ± 0.5 | 2.6 | 4.9 | 4.20 ± 1.17 |
| mattcl-py | input-pting | 14.8 ± 0.5 | 13.9 | 17.7 | 18.57 ± 4.32 |
| mattcl-py | input-lanjian | 14.8 ± 0.6 | 13.7 | 17.6 | 18.62 ± 4.34 |
| mattcl-py | input-mattcl | 14.9 ± 0.6 | 13.9 | 18.1 | 18.66 ± 4.36 |
| mattcl-py | input-kcen | 15.0 ± 0.6 | 14.0 | 18.0 | 18.79 ± 4.38 |
| pting | input-lanjian | 52.3 ± 1.0 | 51.0 | 56.1 | 65.73 ± 15.16 |
| pting | input-mattcl | 53.4 ± 1.6 | 51.4 | 60.6 | 67.09 ± 15.55 |
| pting | input-kcen | 53.6 ± 2.1 | 51.3 | 62.5 | 67.31 ± 15.69 |
| pting | input-pting | 56.2 ± 1.7 | 53.9 | 64.3 | 70.54 ± 16.35 |
| kcen | input-lanjian | 84.8 ± 1.3 | 82.6 | 87.5 | 106.46 ± 24.52 |
| kcen | input-mattcl | 85.9 ± 1.7 | 83.2 | 92.8 | 107.81 ± 24.87 |
| kcen | input-kcen | 86.5 ± 1.7 | 83.6 | 90.2 | 108.55 ± 25.04 |
| kcen | input-pting | 90.5 ± 1.9 | 86.9 | 96.4 | 113.61 ± 26.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|