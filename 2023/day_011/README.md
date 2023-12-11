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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.9 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.8 | 1.02 ± 0.27 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.05 ± 0.26 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 2.1 | 1.08 ± 0.30 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 2.0 | 4.4 | 2.57 ± 0.61 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.1 | 4.7 | 2.67 ± 0.61 |
| lanjian | input-kcen | 3.1 ± 0.6 | 2.4 | 10.1 | 2.79 ± 0.80 |
| lanjian | input-lanjian | 3.2 ± 0.4 | 2.6 | 6.0 | 2.86 ± 0.68 |
| pting | input-lanjian | 51.8 ± 1.1 | 50.1 | 55.0 | 45.94 ± 9.57 |
| pting | input-kcen | 52.1 ± 1.6 | 50.3 | 60.5 | 46.26 ± 9.69 |
| pting | input-mattcl | 52.7 ± 1.1 | 51.0 | 55.6 | 46.78 ± 9.75 |
| mattcl-py | input-kcen | 54.1 ± 0.9 | 52.4 | 56.9 | 47.96 ± 9.97 |
| mattcl-py | input-lanjian | 54.1 ± 1.2 | 52.5 | 57.7 | 48.02 ± 10.01 |
| pting | input-pting | 55.7 ± 2.3 | 53.7 | 67.4 | 49.40 ± 10.44 |
| mattcl-py | input-mattcl | 56.5 ± 2.9 | 54.1 | 72.7 | 50.09 ± 10.70 |
| mattcl-py | input-pting | 57.8 ± 0.9 | 55.9 | 60.1 | 51.26 ± 10.66 |
| kcen | input-lanjian | 88.3 ± 1.5 | 85.1 | 91.3 | 78.30 ± 16.29 |
| kcen | input-kcen | 89.2 ± 4.5 | 85.9 | 113.4 | 79.09 ± 16.88 |
| kcen | input-mattcl | 90.7 ± 3.3 | 87.7 | 107.7 | 80.49 ± 16.94 |
| kcen | input-pting | 95.0 ± 1.8 | 92.0 | 100.1 | 84.31 ± 17.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|