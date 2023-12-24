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
| mattcl | input-pting | 0.5 ± 0.1 | 0.3 | 0.9 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.85 ± 0.57 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.86 ± 0.51 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.88 ± 0.53 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 4.9 | 6.30 ± 1.41 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.4 | 4.3 | 6.32 ± 1.37 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.7 | 5.9 | 7.00 ± 1.61 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.8 | 5.8 | 7.14 ± 1.64 |
| mattcl-py | input-kcen | 15.2 ± 0.4 | 14.4 | 17.3 | 31.36 ± 6.48 |
| mattcl-py | input-mattcl | 15.8 ± 0.5 | 14.9 | 18.5 | 32.46 ± 6.75 |
| mattcl-py | input-lanjian | 15.9 ± 1.3 | 14.8 | 23.8 | 32.66 ± 7.20 |
| mattcl-py | input-pting | 20.1 ± 1.5 | 18.2 | 24.4 | 41.26 ± 9.01 |
| pting | input-lanjian | 56.8 ± 10.1 | 52.9 | 96.0 | 116.81 ± 31.70 |
| pting | input-pting | 57.7 ± 1.2 | 55.3 | 61.3 | 118.60 ± 24.47 |
| pting | input-kcen | 59.4 ± 12.3 | 52.4 | 95.8 | 122.21 ± 35.58 |
| pting | input-mattcl | 72.5 ± 11.8 | 53.6 | 98.4 | 149.17 ± 39.08 |
| kcen | input-lanjian | 89.6 ± 1.8 | 87.0 | 94.5 | 184.34 ± 38.01 |
| kcen | input-kcen | 89.7 ± 1.1 | 87.8 | 92.8 | 184.58 ± 37.94 |
| kcen | input-mattcl | 91.8 ± 1.5 | 89.7 | 95.4 | 188.78 ± 38.85 |
| kcen | input-pting | 132.8 ± 1.8 | 131.0 | 139.5 | 273.06 ± 56.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|