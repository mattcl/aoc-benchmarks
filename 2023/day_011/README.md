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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.26 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 2.3 | 1.05 ± 0.28 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.3 | 1.5 | 1.08 ± 0.26 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.4 | 5.8 | 3.45 ± 0.75 |
| lanjian | input-pting | 3.3 ± 0.4 | 2.5 | 6.0 | 3.58 ± 0.81 |
| lanjian | input-lanjian | 3.8 ± 0.5 | 3.2 | 6.9 | 4.16 ± 0.98 |
| lanjian | input-kcen | 3.8 ± 0.5 | 2.9 | 6.8 | 4.22 ± 0.98 |
| mattcl-py | input-pting | 15.1 ± 0.7 | 13.8 | 18.1 | 16.64 ± 3.22 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 13.8 | 18.6 | 16.72 ± 3.22 |
| mattcl-py | input-lanjian | 15.2 ± 0.7 | 13.9 | 18.4 | 16.74 ± 3.24 |
| mattcl-py | input-kcen | 15.2 ± 0.6 | 14.0 | 18.4 | 16.81 ± 3.25 |
| pting | input-lanjian | 53.9 ± 1.3 | 51.7 | 58.5 | 59.42 ± 11.31 |
| pting | input-kcen | 54.0 ± 1.4 | 51.7 | 59.1 | 59.49 ± 11.33 |
| pting | input-mattcl | 54.1 ± 2.2 | 52.0 | 68.1 | 59.69 ± 11.53 |
| pting | input-pting | 56.7 ± 1.4 | 54.7 | 61.4 | 62.52 ± 11.91 |
| kcen | input-lanjian | 84.8 ± 1.6 | 82.2 | 88.8 | 93.47 ± 17.73 |
| kcen | input-mattcl | 86.7 ± 1.3 | 84.1 | 89.3 | 95.55 ± 18.10 |
| kcen | input-kcen | 87.4 ± 1.8 | 84.9 | 91.9 | 96.38 ± 18.31 |
| kcen | input-pting | 90.8 ± 4.3 | 87.7 | 113.2 | 100.14 ± 19.50 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|