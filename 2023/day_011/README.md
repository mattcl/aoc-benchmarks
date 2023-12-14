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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.26 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.05 ± 0.26 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.9 | 1.05 ± 0.26 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 4.5 | 2.79 ± 0.60 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.3 | 6.2 | 2.81 ± 0.64 |
| lanjian | input-kcen | 3.7 ± 0.4 | 2.9 | 6.9 | 3.33 ± 0.74 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 2.9 | 6.5 | 3.34 ± 0.75 |
| pting | input-lanjian | 53.1 ± 1.2 | 51.1 | 56.8 | 48.36 ± 9.35 |
| pting | input-kcen | 53.5 ± 1.4 | 51.2 | 57.7 | 48.72 ± 9.44 |
| pting | input-mattcl | 53.9 ± 1.3 | 52.0 | 57.1 | 49.10 ± 9.50 |
| mattcl-py | input-lanjian | 54.9 ± 1.1 | 53.2 | 58.4 | 49.96 ± 9.64 |
| mattcl-py | input-kcen | 55.0 ± 1.0 | 53.4 | 57.6 | 50.11 ± 9.66 |
| mattcl-py | input-mattcl | 56.6 ± 2.1 | 54.3 | 69.0 | 51.53 ± 10.08 |
| pting | input-pting | 56.6 ± 4.5 | 54.1 | 87.7 | 51.57 ± 10.72 |
| mattcl-py | input-pting | 58.0 ± 1.1 | 56.3 | 60.6 | 52.82 ± 10.19 |
| kcen | input-lanjian | 84.6 ± 1.7 | 81.4 | 90.8 | 77.07 ± 14.88 |
| kcen | input-kcen | 85.4 ± 1.7 | 83.1 | 91.8 | 77.79 ± 15.02 |
| kcen | input-mattcl | 86.8 ± 2.2 | 84.5 | 95.0 | 79.08 ± 15.32 |
| kcen | input-pting | 90.5 ± 2.2 | 87.7 | 99.3 | 82.44 ± 15.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|