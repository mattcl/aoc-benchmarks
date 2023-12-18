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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.28 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.28 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.4 | 1.0 | 1.05 ± 0.24 |
| lanjian | input-mattcl | 2.8 ± 0.3 | 2.1 | 4.8 | 3.54 ± 0.78 |
| lanjian | input-pting | 2.9 ± 0.3 | 2.0 | 5.3 | 3.66 ± 0.81 |
| lanjian | input-lanjian | 3.2 ± 0.3 | 2.5 | 5.8 | 3.98 ± 0.88 |
| lanjian | input-kcen | 3.3 ± 0.3 | 2.6 | 5.3 | 4.10 ± 0.90 |
| mattcl-py | input-mattcl | 14.9 ± 0.6 | 13.8 | 17.9 | 18.59 ± 3.70 |
| mattcl-py | input-pting | 14.9 ± 0.6 | 14.1 | 18.2 | 18.66 ± 3.72 |
| mattcl-py | input-lanjian | 15.0 ± 0.6 | 13.9 | 18.1 | 18.69 ± 3.72 |
| mattcl-py | input-kcen | 15.1 ± 0.7 | 14.0 | 18.6 | 18.86 ± 3.76 |
| pting | input-lanjian | 52.4 ± 1.4 | 50.3 | 58.5 | 65.47 ± 12.86 |
| pting | input-mattcl | 52.8 ± 1.1 | 51.5 | 56.3 | 66.00 ± 12.93 |
| pting | input-kcen | 53.3 ± 1.5 | 51.0 | 59.2 | 66.60 ± 13.10 |
| pting | input-pting | 55.8 ± 2.0 | 53.5 | 64.6 | 69.64 ± 13.78 |
| kcen | input-lanjian | 85.2 ± 1.2 | 83.2 | 87.8 | 106.45 ± 20.78 |
| kcen | input-kcen | 86.2 ± 1.5 | 84.0 | 90.0 | 107.71 ± 21.06 |
| kcen | input-mattcl | 86.9 ± 1.4 | 84.6 | 89.4 | 108.59 ± 21.21 |
| kcen | input-pting | 91.2 ± 2.0 | 88.5 | 97.8 | 113.85 ± 22.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|