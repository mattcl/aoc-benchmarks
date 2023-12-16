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
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.35 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.4 | 1.06 ± 0.35 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 2.6 | 1.10 ± 0.41 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 2.1 | 5.1 | 3.93 ± 1.08 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.1 | 5.1 | 3.98 ± 1.07 |
| lanjian | input-lanjian | 3.2 ± 0.5 | 2.5 | 6.6 | 4.28 ± 1.26 |
| lanjian | input-kcen | 3.3 ± 0.4 | 2.5 | 5.6 | 4.49 ± 1.27 |
| mattcl-py | input-pting | 14.7 ± 0.4 | 13.8 | 17.3 | 19.85 ± 4.98 |
| mattcl-py | input-mattcl | 14.9 ± 0.6 | 13.9 | 17.9 | 20.06 ± 5.05 |
| mattcl-py | input-lanjian | 14.9 ± 0.6 | 14.0 | 17.7 | 20.09 ± 5.06 |
| mattcl-py | input-kcen | 15.0 ± 0.6 | 13.9 | 18.5 | 20.20 ± 5.10 |
| pting | input-lanjian | 52.7 ± 1.4 | 51.1 | 58.5 | 71.03 ± 17.78 |
| pting | input-mattcl | 53.3 ± 1.4 | 51.2 | 59.6 | 71.88 ± 18.00 |
| pting | input-kcen | 53.4 ± 4.6 | 51.0 | 85.8 | 71.96 ± 18.96 |
| pting | input-pting | 55.7 ± 1.5 | 53.7 | 59.3 | 75.11 ± 18.81 |
| kcen | input-lanjian | 87.9 ± 2.5 | 84.4 | 98.5 | 118.40 ± 29.67 |
| kcen | input-mattcl | 89.3 ± 1.5 | 86.7 | 93.1 | 120.32 ± 30.03 |
| kcen | input-kcen | 89.9 ± 2.8 | 87.2 | 100.0 | 121.16 ± 30.41 |
| kcen | input-pting | 92.2 ± 1.2 | 90.2 | 95.8 | 124.25 ± 30.98 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|