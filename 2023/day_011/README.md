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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.3 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.29 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.2 | 1.0 | 1.03 ± 0.24 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.6 | 1.05 ± 0.29 |
| lanjian | input-mattcl | 3.2 ± 2.8 | 2.1 | 41.8 | 3.69 ± 3.28 |
| lanjian | input-pting | 3.2 ± 0.4 | 2.4 | 5.8 | 3.70 ± 0.83 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 2.8 | 6.3 | 4.25 ± 0.95 |
| lanjian | input-kcen | 3.7 ± 0.5 | 2.8 | 6.1 | 4.32 ± 0.98 |
| mattcl-py | input-pting | 15.1 ± 0.5 | 14.2 | 17.7 | 17.58 ± 3.37 |
| mattcl-py | input-mattcl | 15.3 ± 2.1 | 14.1 | 42.3 | 17.71 ± 4.10 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 14.4 | 18.5 | 17.76 ± 3.43 |
| mattcl-py | input-lanjian | 15.6 ± 3.5 | 14.4 | 63.0 | 18.06 ± 5.32 |
| pting | input-lanjian | 53.4 ± 1.5 | 51.4 | 58.9 | 62.01 ± 11.82 |
| pting | input-mattcl | 54.0 ± 1.3 | 51.5 | 56.9 | 62.74 ± 11.94 |
| pting | input-kcen | 54.1 ± 1.5 | 51.8 | 58.0 | 62.77 ± 11.98 |
| pting | input-pting | 56.6 ± 1.5 | 54.8 | 61.1 | 65.75 ± 12.52 |
| kcen | input-lanjian | 85.5 ± 4.1 | 82.3 | 105.2 | 99.28 ± 19.33 |
| kcen | input-kcen | 86.1 ± 1.4 | 82.5 | 88.8 | 100.03 ± 18.95 |
| kcen | input-mattcl | 86.4 ± 1.4 | 84.6 | 90.2 | 100.36 ± 19.00 |
| kcen | input-pting | 90.3 ± 1.6 | 87.9 | 95.7 | 104.89 ± 19.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|