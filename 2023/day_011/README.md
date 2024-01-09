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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.7 | 1.02 ± 0.30 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.2 | 1.04 ± 0.26 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.4 | 1.7 | 1.06 ± 0.29 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.2 | 3.8 | 3.37 ± 0.77 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.5 | 3.39 ± 0.83 |
| lanjian | input-lanjian | 3.5 ± 0.3 | 3.0 | 5.0 | 3.87 ± 0.89 |
| lanjian | input-kcen | 3.5 ± 0.4 | 3.1 | 5.3 | 3.95 ± 0.96 |
| mattcl-py | input-mattcl | 15.1 ± 0.5 | 13.9 | 17.8 | 16.86 ± 3.72 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 14.2 | 18.3 | 16.94 ± 3.76 |
| mattcl-py | input-pting | 15.2 ± 0.7 | 13.9 | 19.0 | 16.96 ± 3.79 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 14.3 | 18.2 | 17.04 ± 3.78 |
| pting | input-lanjian | 53.6 ± 4.1 | 50.5 | 80.9 | 59.76 ± 13.82 |
| pting | input-mattcl | 53.6 ± 1.2 | 51.8 | 56.2 | 59.78 ± 13.13 |
| pting | input-kcen | 53.8 ± 1.3 | 51.9 | 56.9 | 59.99 ± 13.18 |
| pting | input-pting | 56.5 ± 1.3 | 54.6 | 59.6 | 62.98 ± 13.83 |
| kcen | input-lanjian | 86.0 ± 1.8 | 82.6 | 90.4 | 95.82 ± 21.03 |
| kcen | input-mattcl | 86.9 ± 1.5 | 84.6 | 90.2 | 96.89 ± 21.24 |
| kcen | input-kcen | 87.0 ± 1.6 | 84.3 | 92.6 | 97.01 ± 21.27 |
| kcen | input-pting | 90.2 ± 2.0 | 87.2 | 96.7 | 100.55 ± 22.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|