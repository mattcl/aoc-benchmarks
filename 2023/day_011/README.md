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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.32 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.6 | 1.03 ± 0.32 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 2.2 | 1.07 ± 0.34 |
| lanjian | input-mattcl | 2.9 ± 0.4 | 2.0 | 5.4 | 3.72 ± 0.99 |
| lanjian | input-pting | 3.0 ± 0.4 | 2.0 | 5.3 | 3.73 ± 1.00 |
| lanjian | input-lanjian | 3.4 ± 0.3 | 2.8 | 4.9 | 4.23 ± 1.10 |
| lanjian | input-kcen | 3.4 ± 0.4 | 2.7 | 5.4 | 4.35 ± 1.16 |
| mattcl-py | input-mattcl | 15.0 ± 0.5 | 13.8 | 17.7 | 18.98 ± 4.60 |
| mattcl-py | input-pting | 15.1 ± 1.6 | 13.8 | 34.3 | 19.00 ± 4.98 |
| mattcl-py | input-lanjian | 15.2 ± 0.7 | 13.9 | 18.1 | 19.14 ± 4.66 |
| mattcl-py | input-kcen | 15.2 ± 0.6 | 14.0 | 18.9 | 19.24 ± 4.68 |
| pting | input-mattcl | 53.8 ± 1.1 | 52.2 | 56.1 | 67.94 ± 16.34 |
| pting | input-lanjian | 54.0 ± 1.9 | 51.4 | 63.7 | 68.22 ± 16.53 |
| pting | input-kcen | 54.1 ± 1.4 | 51.8 | 57.4 | 68.28 ± 16.46 |
| pting | input-pting | 56.3 ± 1.4 | 54.0 | 61.0 | 71.07 ± 17.12 |
| kcen | input-lanjian | 84.8 ± 1.6 | 82.7 | 90.0 | 107.02 ± 25.72 |
| kcen | input-kcen | 86.9 ± 1.4 | 84.5 | 90.3 | 109.65 ± 26.34 |
| kcen | input-mattcl | 87.6 ± 5.9 | 84.3 | 119.2 | 110.64 ± 27.52 |
| kcen | input-pting | 90.6 ± 1.4 | 88.1 | 93.5 | 114.33 ± 27.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|