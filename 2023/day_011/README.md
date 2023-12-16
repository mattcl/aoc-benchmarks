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
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.6 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.04 ± 0.33 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.6 | 1.07 ± 0.33 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.1 | 5.3 | 3.55 ± 0.97 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.7 | 4.0 | 3.55 ± 0.95 |
| lanjian | input-kcen | 3.5 ± 0.5 | 2.8 | 6.5 | 4.03 ± 1.20 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.7 | 5.7 | 4.05 ± 1.15 |
| mattcl-py | input-pting | 15.2 ± 0.6 | 13.9 | 18.0 | 17.54 ± 4.62 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 14.2 | 18.6 | 17.55 ± 4.61 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.2 | 18.4 | 17.61 ± 4.64 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 14.2 | 18.2 | 17.68 ± 4.66 |
| pting | input-lanjian | 52.9 ± 1.3 | 50.9 | 57.2 | 61.07 ± 15.95 |
| pting | input-kcen | 53.3 ± 1.3 | 51.8 | 59.8 | 61.62 ± 16.09 |
| pting | input-mattcl | 54.1 ± 2.5 | 51.7 | 68.3 | 62.50 ± 16.50 |
| pting | input-pting | 56.6 ± 2.0 | 54.2 | 64.9 | 65.38 ± 17.16 |
| kcen | input-lanjian | 91.2 ± 1.4 | 88.4 | 94.1 | 105.32 ± 27.43 |
| kcen | input-mattcl | 92.4 ± 1.3 | 90.7 | 95.2 | 106.74 ± 27.80 |
| kcen | input-kcen | 93.0 ± 2.4 | 89.8 | 102.5 | 107.51 ± 28.10 |
| kcen | input-pting | 97.0 ± 1.9 | 93.3 | 102.9 | 112.07 ± 29.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|