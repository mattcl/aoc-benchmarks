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
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.2 | 1.0 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 ± 0.27 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.2 | 1.04 ± 0.23 |
| mattcl | input-pting | 0.9 ± 3.6 | 0.1 | 50.9 | 1.08 ± 4.31 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 5.5 | 3.57 ± 0.73 |
| lanjian | input-mattcl | 3.0 ± 0.4 | 2.3 | 5.7 | 3.65 ± 0.79 |
| lanjian | input-lanjian | 3.5 ± 0.3 | 2.7 | 5.1 | 4.20 ± 0.85 |
| lanjian | input-kcen | 3.5 ± 0.4 | 3.0 | 5.4 | 4.28 ± 0.88 |
| mattcl-py | input-mattcl | 14.8 ± 0.5 | 13.7 | 17.2 | 17.85 ± 3.21 |
| mattcl-py | input-lanjian | 14.9 ± 0.6 | 13.8 | 18.0 | 18.00 ± 3.28 |
| mattcl-py | input-kcen | 14.9 ± 0.7 | 13.9 | 18.0 | 18.03 ± 3.30 |
| mattcl-py | input-pting | 15.0 ± 2.3 | 13.8 | 45.8 | 18.19 ± 4.25 |
| pting | input-lanjian | 54.4 ± 1.8 | 51.9 | 61.2 | 65.81 ± 11.88 |
| pting | input-kcen | 54.8 ± 1.6 | 51.9 | 60.9 | 66.28 ± 11.92 |
| pting | input-mattcl | 55.0 ± 1.6 | 52.5 | 60.2 | 66.52 ± 11.95 |
| pting | input-pting | 58.1 ± 2.0 | 55.9 | 70.2 | 70.29 ± 12.71 |
| kcen | input-lanjian | 83.4 ± 1.4 | 81.0 | 87.1 | 100.85 ± 17.97 |
| kcen | input-kcen | 85.3 ± 1.5 | 82.9 | 89.1 | 103.17 ± 18.39 |
| kcen | input-mattcl | 85.7 ± 3.1 | 82.9 | 101.2 | 103.70 ± 18.76 |
| kcen | input-pting | 90.1 ± 3.8 | 86.8 | 108.8 | 108.99 ± 19.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|