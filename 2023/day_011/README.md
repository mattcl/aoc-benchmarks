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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.28 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.7 | 1.04 ± 0.28 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.05 ± 0.29 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.1 | 4.3 | 3.39 ± 0.76 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 5.2 | 3.45 ± 0.75 |
| lanjian | input-kcen | 3.4 ± 0.4 | 2.7 | 5.9 | 3.91 ± 0.90 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.7 | 5.1 | 3.95 ± 0.90 |
| mattcl-py | input-lanjian | 15.3 ± 0.6 | 14.5 | 18.5 | 17.39 ± 3.52 |
| mattcl-py | input-kcen | 15.3 ± 0.5 | 14.4 | 18.2 | 17.41 ± 3.51 |
| mattcl-py | input-pting | 15.4 ± 3.8 | 13.9 | 68.0 | 17.57 ± 5.57 |
| mattcl-py | input-mattcl | 15.6 ± 3.7 | 14.1 | 55.1 | 17.71 ± 5.50 |
| pting | input-lanjian | 53.5 ± 1.2 | 51.6 | 56.7 | 60.92 ± 12.16 |
| pting | input-mattcl | 54.3 ± 1.2 | 52.3 | 57.9 | 61.75 ± 12.33 |
| pting | input-kcen | 54.3 ± 1.6 | 51.9 | 60.9 | 61.76 ± 12.38 |
| pting | input-pting | 56.7 ± 1.4 | 54.1 | 59.6 | 64.50 ± 12.89 |
| kcen | input-lanjian | 85.0 ± 1.5 | 82.7 | 88.2 | 96.67 ± 19.25 |
| kcen | input-kcen | 86.9 ± 1.9 | 83.4 | 94.0 | 98.83 ± 19.72 |
| kcen | input-mattcl | 87.0 ± 1.5 | 84.0 | 90.8 | 98.97 ± 19.70 |
| kcen | input-pting | 91.0 ± 2.6 | 88.6 | 103.7 | 103.52 ± 20.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|