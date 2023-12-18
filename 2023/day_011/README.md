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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.00 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.3 | 1.2 | 1.05 ± 0.29 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.29 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.2 | 1.08 ± 0.30 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.2 | 5.2 | 3.39 ± 0.79 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.2 | 5.1 | 3.45 ± 0.83 |
| lanjian | input-kcen | 3.5 ± 0.3 | 3.0 | 5.1 | 3.88 ± 0.92 |
| lanjian | input-lanjian | 3.5 ± 0.5 | 2.8 | 6.6 | 3.88 ± 0.99 |
| mattcl-py | input-pting | 15.2 ± 0.6 | 13.9 | 18.2 | 16.68 ± 3.72 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.2 | 17.9 | 16.72 ± 3.72 |
| mattcl-py | input-kcen | 15.4 ± 0.6 | 14.3 | 18.9 | 16.84 ± 3.75 |
| mattcl-py | input-lanjian | 15.4 ± 0.7 | 14.5 | 18.9 | 16.87 ± 3.78 |
| pting | input-lanjian | 53.4 ± 1.4 | 51.2 | 59.1 | 58.50 ± 12.95 |
| pting | input-kcen | 53.6 ± 1.4 | 51.9 | 59.0 | 58.79 ± 13.00 |
| pting | input-mattcl | 54.0 ± 1.4 | 51.8 | 58.9 | 59.19 ± 13.09 |
| pting | input-pting | 56.5 ± 2.0 | 53.6 | 66.2 | 61.92 ± 13.77 |
| kcen | input-lanjian | 84.9 ± 1.0 | 83.0 | 87.1 | 93.08 ± 20.48 |
| kcen | input-mattcl | 87.0 ± 1.9 | 85.0 | 94.2 | 95.38 ± 21.06 |
| kcen | input-kcen | 87.2 ± 2.0 | 84.5 | 92.9 | 95.64 ± 21.12 |
| kcen | input-pting | 90.9 ± 1.8 | 88.3 | 95.8 | 99.67 ± 21.98 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|