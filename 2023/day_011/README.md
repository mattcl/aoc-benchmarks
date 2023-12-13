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
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.8 | 1.01 ± 0.21 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.9 | 1.02 ± 0.21 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 2.2 | 1.03 ± 0.23 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.4 | 4.0 | 2.54 ± 0.43 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.5 | 6.0 | 2.56 ± 0.48 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 3.2 | 6.7 | 3.02 ± 0.58 |
| lanjian | input-kcen | 3.8 ± 0.4 | 2.9 | 6.1 | 3.06 ± 0.58 |
| mattcl-py | input-lanjian | 55.3 ± 1.1 | 53.7 | 58.8 | 44.57 ± 6.86 |
| mattcl-py | input-kcen | 55.8 ± 1.1 | 54.1 | 59.3 | 44.95 ± 6.92 |
| mattcl-py | input-mattcl | 56.9 ± 1.2 | 55.4 | 59.2 | 45.85 ± 7.06 |
| pting | input-mattcl | 58.1 ± 1.7 | 55.2 | 63.2 | 46.88 ± 7.29 |
| pting | input-kcen | 58.3 ± 1.5 | 55.7 | 62.4 | 47.01 ± 7.28 |
| pting | input-lanjian | 58.6 ± 1.8 | 56.2 | 64.6 | 47.21 ± 7.36 |
| mattcl-py | input-pting | 58.8 ± 1.1 | 57.0 | 61.9 | 47.44 ± 7.30 |
| pting | input-pting | 61.6 ± 1.5 | 58.4 | 64.5 | 49.64 ± 7.67 |
| kcen | input-lanjian | 85.2 ± 2.3 | 82.9 | 92.7 | 68.65 ± 10.65 |
| kcen | input-kcen | 85.7 ± 2.2 | 82.8 | 91.9 | 69.08 ± 10.69 |
| kcen | input-mattcl | 86.8 ± 1.7 | 84.4 | 92.5 | 69.99 ± 10.77 |
| kcen | input-pting | 90.0 ± 1.9 | 86.7 | 96.6 | 72.54 ± 11.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|