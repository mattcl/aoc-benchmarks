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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.30 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.2 | 1.6 | 1.05 ± 0.28 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.7 | 1.06 ± 0.28 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.2 | 5.6 | 3.02 ± 0.68 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.2 | 4.7 | 3.05 ± 0.68 |
| lanjian | input-kcen | 3.5 ± 0.3 | 2.7 | 5.1 | 3.42 ± 0.77 |
| lanjian | input-lanjian | 3.5 ± 0.5 | 2.8 | 6.1 | 3.46 ± 0.84 |
| pting | input-lanjian | 52.2 ± 2.3 | 50.2 | 63.8 | 51.67 ± 10.77 |
| pting | input-kcen | 52.6 ± 3.2 | 50.1 | 69.0 | 52.02 ± 11.07 |
| pting | input-mattcl | 52.8 ± 1.7 | 50.9 | 59.1 | 52.29 ± 10.78 |
| mattcl-py | input-kcen | 53.7 ± 1.0 | 52.2 | 56.4 | 53.16 ± 10.88 |
| mattcl-py | input-lanjian | 54.5 ± 2.5 | 51.9 | 70.7 | 53.93 ± 11.26 |
| pting | input-pting | 55.4 ± 1.6 | 53.7 | 60.2 | 54.83 ± 11.28 |
| mattcl-py | input-mattcl | 55.8 ± 1.4 | 53.5 | 59.6 | 55.18 ± 11.33 |
| mattcl-py | input-pting | 57.7 ± 1.4 | 55.7 | 61.6 | 57.13 ± 11.72 |
| kcen | input-kcen | 83.4 ± 1.3 | 80.8 | 86.4 | 82.53 ± 16.86 |
| kcen | input-lanjian | 83.9 ± 1.9 | 80.6 | 90.3 | 82.98 ± 17.00 |
| kcen | input-mattcl | 84.6 ± 1.6 | 82.4 | 90.0 | 83.73 ± 17.13 |
| kcen | input-pting | 88.7 ± 1.5 | 86.3 | 92.0 | 87.79 ± 17.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|