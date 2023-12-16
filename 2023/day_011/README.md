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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.5 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.07 ± 0.31 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.3 | 1.1 | 1.07 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.4 | 1.6 | 1.08 ± 0.31 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.1 | 5.5 | 3.56 ± 0.95 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.2 | 5.5 | 3.58 ± 0.92 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.7 | 5.9 | 4.03 ± 1.03 |
| lanjian | input-kcen | 3.5 ± 0.3 | 3.0 | 5.4 | 4.07 ± 0.98 |
| mattcl-py | input-pting | 15.2 ± 0.6 | 13.9 | 18.3 | 17.53 ± 4.08 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 13.9 | 18.7 | 17.54 ± 4.07 |
| mattcl-py | input-lanjian | 15.3 ± 0.6 | 14.2 | 18.4 | 17.64 ± 4.11 |
| mattcl-py | input-kcen | 15.3 ± 0.5 | 14.2 | 18.2 | 17.67 ± 4.09 |
| pting | input-lanjian | 53.0 ± 1.6 | 51.3 | 60.4 | 61.06 ± 14.11 |
| pting | input-kcen | 53.7 ± 1.6 | 52.1 | 63.8 | 61.81 ± 14.29 |
| pting | input-mattcl | 54.0 ± 1.6 | 52.2 | 62.9 | 62.18 ± 14.37 |
| pting | input-pting | 56.7 ± 2.5 | 54.4 | 68.3 | 65.34 ± 15.24 |
| kcen | input-lanjian | 91.8 ± 1.5 | 89.3 | 95.2 | 105.75 ± 24.29 |
| kcen | input-kcen | 92.7 ± 1.9 | 89.2 | 97.8 | 106.82 ± 24.58 |
| kcen | input-mattcl | 92.9 ± 1.8 | 89.6 | 96.2 | 107.02 ± 24.60 |
| kcen | input-pting | 97.0 ± 1.5 | 93.3 | 99.2 | 111.77 ± 25.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|