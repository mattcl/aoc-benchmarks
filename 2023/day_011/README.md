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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.5 | 1.3 | 1.04 ± 0.25 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.07 ± 0.26 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 2.6 | 1.08 ± 0.27 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.7 | 2.75 ± 0.63 |
| lanjian | input-mattcl | 3.2 ± 0.4 | 2.3 | 5.8 | 2.83 ± 0.67 |
| lanjian | input-lanjian | 3.7 ± 0.5 | 2.9 | 7.4 | 3.30 ± 0.81 |
| lanjian | input-kcen | 3.7 ± 0.4 | 3.2 | 6.8 | 3.32 ± 0.78 |
| mattcl-py | input-lanjian | 55.5 ± 1.1 | 54.0 | 57.8 | 49.73 ± 10.29 |
| mattcl-py | input-kcen | 55.9 ± 1.3 | 54.2 | 58.8 | 50.15 ± 10.39 |
| mattcl-py | input-mattcl | 56.3 ± 0.9 | 54.6 | 58.9 | 50.52 ± 10.43 |
| pting | input-kcen | 58.4 ± 1.3 | 55.4 | 61.4 | 52.37 ± 10.85 |
| pting | input-lanjian | 58.4 ± 1.7 | 55.6 | 64.3 | 52.39 ± 10.90 |
| pting | input-mattcl | 58.8 ± 2.1 | 55.9 | 65.2 | 52.75 ± 11.02 |
| mattcl-py | input-pting | 59.2 ± 1.2 | 56.9 | 62.5 | 53.07 ± 10.98 |
| pting | input-pting | 61.6 ± 1.6 | 58.8 | 65.6 | 55.27 ± 11.47 |
| kcen | input-lanjian | 85.3 ± 2.5 | 83.0 | 95.0 | 76.45 ± 15.90 |
| kcen | input-kcen | 85.7 ± 2.1 | 83.3 | 94.2 | 76.82 ± 15.92 |
| kcen | input-mattcl | 86.5 ± 2.1 | 84.1 | 95.2 | 77.54 ± 16.07 |
| kcen | input-pting | 90.5 ± 1.7 | 87.5 | 96.1 | 81.18 ± 16.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|