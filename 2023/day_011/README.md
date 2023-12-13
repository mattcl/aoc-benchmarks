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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.21 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.22 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 2.2 | 1.09 ± 0.24 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.9 | 2.57 ± 0.48 |
| lanjian | input-pting | 3.3 ± 0.4 | 2.4 | 5.4 | 2.76 ± 0.56 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 2.8 | 6.2 | 3.09 ± 0.60 |
| lanjian | input-kcen | 3.7 ± 0.4 | 2.9 | 5.7 | 3.10 ± 0.59 |
| mattcl-py | input-lanjian | 55.2 ± 1.0 | 53.6 | 57.7 | 45.92 ± 7.44 |
| mattcl-py | input-kcen | 55.9 ± 2.3 | 54.1 | 69.4 | 46.50 ± 7.71 |
| mattcl-py | input-mattcl | 56.9 ± 1.1 | 54.8 | 59.9 | 47.37 ± 7.68 |
| pting | input-lanjian | 57.9 ± 1.5 | 54.4 | 61.0 | 48.19 ± 7.85 |
| pting | input-kcen | 58.2 ± 1.7 | 55.5 | 63.7 | 48.40 ± 7.91 |
| pting | input-mattcl | 59.5 ± 3.3 | 56.6 | 79.9 | 49.49 ± 8.42 |
| mattcl-py | input-pting | 60.6 ± 8.6 | 57.5 | 119.0 | 50.43 ± 10.83 |
| pting | input-pting | 62.2 ± 2.5 | 58.1 | 71.5 | 51.77 ± 8.59 |
| kcen | input-lanjian | 84.7 ± 2.0 | 81.9 | 91.0 | 70.49 ± 11.46 |
| kcen | input-kcen | 85.3 ± 1.4 | 82.9 | 89.7 | 70.93 ± 11.48 |
| kcen | input-mattcl | 87.9 ± 5.2 | 84.5 | 116.0 | 73.14 ± 12.54 |
| kcen | input-pting | 89.9 ± 1.6 | 87.2 | 93.1 | 74.79 ± 12.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|