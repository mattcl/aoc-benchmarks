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
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.3 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.35 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.2 | 1.09 ± 0.34 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.6 | 1.11 ± 0.33 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.3 | 3.63 ± 0.99 |
| lanjian | input-pting | 3.0 ± 0.4 | 2.1 | 5.3 | 3.66 ± 1.05 |
| lanjian | input-lanjian | 3.3 ± 0.4 | 2.5 | 5.5 | 3.93 ± 1.10 |
| lanjian | input-kcen | 3.5 ± 0.3 | 2.9 | 5.5 | 4.19 ± 1.15 |
| mattcl-py | input-mattcl | 14.9 ± 0.6 | 14.0 | 18.0 | 18.00 ± 4.69 |
| mattcl-py | input-kcen | 14.9 ± 0.5 | 14.0 | 18.1 | 18.04 ± 4.68 |
| mattcl-py | input-pting | 15.0 ± 0.6 | 13.9 | 18.1 | 18.09 ± 4.71 |
| mattcl-py | input-lanjian | 15.0 ± 0.5 | 13.9 | 17.4 | 18.13 ± 4.71 |
| pting | input-lanjian | 53.4 ± 1.3 | 51.4 | 57.3 | 64.54 ± 16.68 |
| pting | input-kcen | 53.6 ± 1.4 | 52.0 | 58.3 | 64.78 ± 16.74 |
| pting | input-mattcl | 54.0 ± 1.7 | 52.0 | 62.3 | 65.28 ± 16.91 |
| pting | input-pting | 56.9 ± 2.1 | 54.7 | 65.8 | 68.78 ± 17.87 |
| kcen | input-lanjian | 84.0 ± 1.2 | 82.0 | 87.8 | 101.56 ± 26.16 |
| kcen | input-kcen | 85.1 ± 1.4 | 82.9 | 89.3 | 102.83 ± 26.49 |
| kcen | input-mattcl | 85.3 ± 1.6 | 82.8 | 88.4 | 103.04 ± 26.57 |
| kcen | input-pting | 89.1 ± 1.8 | 86.7 | 94.3 | 107.63 ± 27.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|