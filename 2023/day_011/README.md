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
| mattcl | input-pting | 1.1 ± 0.3 | 0.3 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.08 ± 0.30 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.09 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 2.2 | 1.12 ± 0.32 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.4 | 5.5 | 2.86 ± 0.79 |
| lanjian | input-pting | 3.2 ± 1.8 | 2.3 | 27.8 | 2.93 ± 1.77 |
| lanjian | input-lanjian | 3.8 ± 0.5 | 2.9 | 6.3 | 3.43 ± 0.93 |
| lanjian | input-kcen | 3.8 ± 0.4 | 3.0 | 6.1 | 3.49 ± 0.93 |
| mattcl-py | input-lanjian | 55.2 ± 1.0 | 53.5 | 58.1 | 50.19 ± 12.24 |
| mattcl-py | input-kcen | 56.0 ± 1.2 | 54.4 | 61.6 | 50.93 ± 12.44 |
| mattcl-py | input-mattcl | 57.8 ± 6.2 | 54.9 | 100.5 | 52.62 ± 14.00 |
| pting | input-lanjian | 57.8 ± 1.1 | 55.2 | 60.6 | 52.63 ± 12.84 |
| pting | input-kcen | 58.4 ± 2.2 | 55.2 | 69.1 | 53.20 ± 13.10 |
| pting | input-mattcl | 58.6 ± 1.9 | 55.4 | 63.0 | 53.32 ± 13.09 |
| mattcl-py | input-pting | 59.0 ± 0.9 | 57.5 | 61.6 | 53.65 ± 13.08 |
| pting | input-pting | 62.1 ± 2.1 | 58.3 | 68.5 | 56.49 ± 13.88 |
| kcen | input-lanjian | 85.0 ± 1.4 | 82.8 | 88.4 | 77.36 ± 18.86 |
| kcen | input-kcen | 86.0 ± 2.0 | 83.4 | 92.3 | 78.29 ± 19.13 |
| kcen | input-mattcl | 87.6 ± 2.6 | 84.4 | 95.0 | 79.76 ± 19.54 |
| kcen | input-pting | 90.3 ± 2.0 | 87.6 | 98.1 | 82.15 ± 20.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|