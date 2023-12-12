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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.5 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.25 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 2.7 | 1.03 ± 0.27 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.05 ± 0.24 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.8 | 2.86 ± 0.57 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.4 | 5.9 | 2.88 ± 0.62 |
| lanjian | input-lanjian | 3.5 ± 0.3 | 2.8 | 5.1 | 3.23 ± 0.65 |
| lanjian | input-kcen | 3.6 ± 0.3 | 2.8 | 6.3 | 3.27 ± 0.65 |
| pting | input-kcen | 52.1 ± 1.3 | 50.3 | 56.9 | 47.67 ± 8.51 |
| pting | input-lanjian | 52.1 ± 1.3 | 50.0 | 58.0 | 47.68 ± 8.51 |
| pting | input-mattcl | 52.9 ± 1.7 | 51.1 | 60.2 | 48.41 ± 8.69 |
| mattcl-py | input-kcen | 54.3 ± 1.1 | 52.8 | 58.6 | 49.73 ± 8.85 |
| mattcl-py | input-lanjian | 54.4 ± 1.0 | 52.8 | 57.0 | 49.80 ± 8.85 |
| mattcl-py | input-mattcl | 55.5 ± 1.2 | 53.5 | 59.6 | 50.81 ± 9.05 |
| pting | input-pting | 55.6 ± 1.6 | 53.4 | 61.8 | 50.91 ± 9.11 |
| mattcl-py | input-pting | 57.6 ± 1.3 | 55.6 | 61.0 | 52.76 ± 9.41 |
| kcen | input-lanjian | 83.3 ± 1.3 | 80.7 | 86.6 | 76.25 ± 13.53 |
| kcen | input-kcen | 83.6 ± 1.2 | 81.7 | 86.5 | 76.57 ± 13.58 |
| kcen | input-mattcl | 84.8 ± 1.6 | 82.4 | 88.5 | 77.62 ± 13.79 |
| kcen | input-pting | 88.9 ± 1.5 | 86.1 | 91.5 | 81.39 ± 14.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|