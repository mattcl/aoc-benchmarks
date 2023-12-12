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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.22 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.8 | 1.02 ± 0.23 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 2.0 | 1.03 ± 0.22 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.5 | 4.8 | 2.75 ± 0.46 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.2 | 4.7 | 2.76 ± 0.49 |
| lanjian | input-kcen | 3.6 ± 0.4 | 2.8 | 5.1 | 3.21 ± 0.57 |
| lanjian | input-lanjian | 3.6 ± 0.4 | 3.0 | 6.6 | 3.24 ± 0.61 |
| pting | input-lanjian | 52.7 ± 1.5 | 50.5 | 58.0 | 47.05 ± 7.16 |
| pting | input-kcen | 52.7 ± 1.0 | 50.7 | 55.3 | 47.10 ± 7.10 |
| pting | input-mattcl | 53.0 ± 1.0 | 50.8 | 55.4 | 47.32 ± 7.14 |
| mattcl-py | input-kcen | 54.6 ± 1.1 | 52.8 | 57.8 | 48.76 ± 7.36 |
| mattcl-py | input-lanjian | 54.7 ± 1.3 | 52.2 | 58.4 | 48.84 ± 7.39 |
| pting | input-pting | 56.1 ± 1.6 | 53.6 | 62.5 | 50.13 ± 7.63 |
| mattcl-py | input-mattcl | 56.3 ± 1.4 | 54.2 | 59.7 | 50.30 ± 7.62 |
| mattcl-py | input-pting | 58.9 ± 2.9 | 55.5 | 73.6 | 52.61 ± 8.28 |
| kcen | input-kcen | 85.5 ± 2.1 | 82.8 | 92.7 | 76.38 ± 11.57 |
| kcen | input-lanjian | 86.5 ± 5.4 | 82.0 | 106.3 | 77.21 ± 12.51 |
| kcen | input-mattcl | 87.7 ± 2.4 | 83.5 | 96.2 | 78.27 ± 11.90 |
| kcen | input-pting | 90.4 ± 2.3 | 87.0 | 98.6 | 80.72 ± 12.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|