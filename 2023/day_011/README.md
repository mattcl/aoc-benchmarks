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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.29 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 2.0 | 1.09 ± 0.28 |
| mattcl | input-kcen | 1.2 ± 3.5 | 0.2 | 50.4 | 1.14 ± 3.25 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.2 | 3.8 | 2.84 ± 0.60 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.3 | 5.5 | 2.88 ± 0.66 |
| lanjian | input-lanjian | 3.6 ± 0.4 | 2.9 | 5.4 | 3.35 ± 0.74 |
| lanjian | input-kcen | 3.7 ± 0.4 | 2.9 | 5.9 | 3.39 ± 0.77 |
| pting | input-kcen | 52.3 ± 1.4 | 50.7 | 57.6 | 48.36 ± 9.57 |
| pting | input-lanjian | 52.5 ± 1.6 | 50.3 | 58.3 | 48.49 ± 9.62 |
| pting | input-mattcl | 53.1 ± 1.5 | 50.7 | 57.0 | 49.10 ± 9.72 |
| mattcl-py | input-lanjian | 53.9 ± 1.1 | 51.7 | 56.3 | 49.80 ± 9.82 |
| mattcl-py | input-kcen | 55.2 ± 4.5 | 52.1 | 82.6 | 51.03 ± 10.82 |
| mattcl-py | input-mattcl | 55.9 ± 1.3 | 53.8 | 61.3 | 51.64 ± 10.19 |
| pting | input-pting | 56.1 ± 1.3 | 53.8 | 60.6 | 51.84 ± 10.24 |
| mattcl-py | input-pting | 58.1 ± 1.2 | 56.1 | 60.9 | 53.68 ± 10.58 |
| kcen | input-lanjian | 84.4 ± 2.0 | 80.7 | 90.1 | 77.98 ± 15.40 |
| kcen | input-kcen | 84.6 ± 2.0 | 81.9 | 92.1 | 78.18 ± 15.44 |
| kcen | input-mattcl | 86.8 ± 2.4 | 83.7 | 94.7 | 80.18 ± 15.88 |
| kcen | input-pting | 90.9 ± 3.2 | 87.0 | 102.6 | 83.93 ± 16.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|