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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.7 | 1.7 | 1.00 ± 0.21 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.7 | 1.9 | 1.06 ± 0.22 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.2 | 5.8 | 2.63 ± 0.50 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.4 | 4.6 | 2.71 ± 0.51 |
| lanjian | input-lanjian | 3.6 ± 0.4 | 2.8 | 6.5 | 3.13 ± 0.62 |
| lanjian | input-kcen | 3.7 ± 0.5 | 2.8 | 6.8 | 3.16 ± 0.66 |
| pting | input-lanjian | 52.4 ± 1.8 | 50.3 | 59.5 | 45.12 ± 7.37 |
| pting | input-kcen | 53.0 ± 1.6 | 51.1 | 60.6 | 45.60 ± 7.41 |
| pting | input-mattcl | 53.7 ± 1.4 | 51.0 | 57.0 | 46.25 ± 7.49 |
| mattcl-py | input-lanjian | 54.2 ± 1.4 | 52.5 | 58.8 | 46.65 ± 7.55 |
| mattcl-py | input-kcen | 55.3 ± 2.6 | 52.8 | 72.4 | 47.55 ± 7.91 |
| mattcl-py | input-mattcl | 55.9 ± 0.9 | 54.8 | 58.5 | 48.12 ± 7.72 |
| pting | input-pting | 56.2 ± 1.4 | 54.0 | 59.4 | 48.34 ± 7.81 |
| mattcl-py | input-pting | 58.5 ± 1.6 | 56.5 | 63.0 | 50.38 ± 8.17 |
| kcen | input-lanjian | 84.8 ± 1.5 | 81.7 | 90.6 | 72.97 ± 11.73 |
| kcen | input-kcen | 86.0 ± 2.8 | 82.4 | 95.7 | 73.97 ± 12.06 |
| kcen | input-mattcl | 86.7 ± 2.2 | 83.5 | 93.9 | 74.62 ± 12.06 |
| kcen | input-pting | 90.8 ± 2.3 | 88.0 | 98.4 | 78.17 ± 12.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|