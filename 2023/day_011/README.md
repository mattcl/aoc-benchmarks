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
| mattcl | input-pting | 1.1 ± 0.2 | 0.4 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.23 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.02 ± 0.22 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.23 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.6 | 5.9 | 2.73 ± 0.54 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.5 | 5.8 | 2.75 ± 0.57 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 2.9 | 5.4 | 3.20 ± 0.63 |
| lanjian | input-kcen | 3.7 ± 0.6 | 3.0 | 7.6 | 3.26 ± 0.73 |
| pting | input-lanjian | 52.9 ± 1.0 | 51.3 | 55.8 | 46.41 ± 7.79 |
| pting | input-kcen | 53.2 ± 1.1 | 50.7 | 56.2 | 46.60 ± 7.83 |
| pting | input-mattcl | 53.3 ± 1.4 | 51.3 | 57.7 | 46.69 ± 7.87 |
| mattcl-py | input-lanjian | 55.3 ± 1.5 | 53.4 | 60.2 | 48.48 ± 8.18 |
| mattcl-py | input-kcen | 55.9 ± 2.2 | 53.5 | 66.0 | 49.03 ± 8.39 |
| mattcl-py | input-mattcl | 56.3 ± 1.2 | 54.4 | 60.6 | 49.31 ± 8.29 |
| pting | input-pting | 56.5 ± 4.8 | 53.5 | 88.7 | 49.48 ± 9.27 |
| mattcl-py | input-pting | 58.7 ± 1.5 | 56.3 | 65.0 | 51.45 ± 8.68 |
| kcen | input-lanjian | 84.6 ± 1.3 | 82.5 | 88.2 | 74.12 ± 12.41 |
| kcen | input-kcen | 85.5 ± 1.6 | 82.9 | 89.4 | 74.95 ± 12.57 |
| kcen | input-mattcl | 86.3 ± 1.6 | 84.2 | 92.4 | 75.61 ± 12.67 |
| kcen | input-pting | 91.0 ± 3.0 | 87.6 | 101.6 | 79.73 ± 13.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|