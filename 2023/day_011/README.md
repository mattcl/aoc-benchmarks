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
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.1 | 1.04 ± 0.30 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.31 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.1 | 6.0 | 3.64 ± 0.90 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.2 | 5.8 | 3.65 ± 0.93 |
| lanjian | input-kcen | 3.4 ± 0.5 | 2.9 | 6.4 | 4.08 ± 1.09 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.8 | 6.1 | 4.08 ± 1.01 |
| mattcl-py | input-lanjian | 14.9 ± 0.6 | 13.8 | 17.5 | 17.75 ± 4.04 |
| mattcl-py | input-mattcl | 14.9 ± 0.6 | 14.1 | 18.2 | 17.77 ± 4.06 |
| mattcl-py | input-pting | 15.0 ± 0.6 | 13.7 | 18.6 | 17.79 ± 4.07 |
| mattcl-py | input-kcen | 15.2 ± 1.9 | 14.0 | 34.9 | 18.08 ± 4.63 |
| pting | input-lanjian | 53.5 ± 2.0 | 51.2 | 61.3 | 63.65 ± 14.49 |
| pting | input-kcen | 53.7 ± 1.1 | 52.1 | 56.4 | 63.86 ± 14.40 |
| pting | input-mattcl | 53.8 ± 1.6 | 51.9 | 59.6 | 63.98 ± 14.48 |
| pting | input-pting | 56.4 ± 4.0 | 54.2 | 83.6 | 67.04 ± 15.77 |
| kcen | input-lanjian | 85.2 ± 1.8 | 82.6 | 92.0 | 101.30 ± 22.85 |
| kcen | input-mattcl | 86.9 ± 3.9 | 84.0 | 107.2 | 103.37 ± 23.67 |
| kcen | input-kcen | 87.3 ± 5.0 | 83.9 | 114.4 | 103.84 ± 24.05 |
| kcen | input-pting | 90.0 ± 2.2 | 87.2 | 96.9 | 107.02 ± 24.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|