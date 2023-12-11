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
| mattcl | input-lanjian | 1.0 ± 0.3 | 0.4 | 1.5 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.4 | 1.8 | 1.16 ± 0.41 |
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.4 | 1.9 | 1.20 ± 0.41 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.9 | 1.31 ± 0.41 |
| lanjian | input-mattcl | 3.0 ± 0.4 | 2.0 | 5.4 | 2.91 ± 0.87 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 4.8 | 3.06 ± 0.87 |
| lanjian | input-lanjian | 3.2 ± 0.2 | 2.6 | 3.9 | 3.17 ± 0.89 |
| lanjian | input-kcen | 3.5 ± 0.7 | 2.7 | 7.4 | 3.48 ± 1.17 |
| pting | input-lanjian | 53.6 ± 1.2 | 51.7 | 58.3 | 52.68 ± 14.46 |
| pting | input-mattcl | 54.4 ± 2.3 | 51.7 | 67.5 | 53.47 ± 14.81 |
| pting | input-kcen | 54.8 ± 4.0 | 51.6 | 81.8 | 53.91 ± 15.28 |
| mattcl-py | input-kcen | 55.5 ± 1.0 | 53.9 | 58.1 | 54.62 ± 14.98 |
| mattcl-py | input-mattcl | 56.7 ± 1.1 | 54.8 | 59.7 | 55.78 ± 15.30 |
| mattcl-py | input-lanjian | 57.0 ± 1.5 | 54.7 | 63.4 | 56.05 ± 15.41 |
| pting | input-pting | 57.1 ± 2.0 | 54.7 | 64.4 | 56.19 ± 15.50 |
| mattcl-py | input-pting | 59.6 ± 3.0 | 57.2 | 78.5 | 58.67 ± 16.33 |
| kcen | input-lanjian | 92.9 ± 3.0 | 89.2 | 104.0 | 91.41 ± 25.19 |
| kcen | input-mattcl | 93.0 ± 2.0 | 89.2 | 98.7 | 91.43 ± 25.10 |
| kcen | input-kcen | 93.1 ± 1.8 | 90.9 | 97.9 | 91.61 ± 25.13 |
| kcen | input-pting | 97.4 ± 2.3 | 93.2 | 104.1 | 95.82 ± 26.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|