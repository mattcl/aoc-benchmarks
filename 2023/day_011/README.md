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
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.2 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.6 | 1.02 ± 0.33 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.3 | 1.1 | 1.04 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.5 | 1.6 | 1.08 ± 0.30 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.6 | 4.7 | 3.67 ± 0.89 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.1 | 4.7 | 3.67 ± 0.92 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.7 | 5.6 | 4.26 ± 1.10 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.6 | 5.6 | 4.27 ± 1.10 |
| mattcl-py | input-pting | 15.1 ± 0.7 | 13.9 | 18.2 | 18.60 ± 4.38 |
| mattcl-py | input-lanjian | 15.1 ± 0.5 | 14.2 | 18.3 | 18.62 ± 4.35 |
| mattcl-py | input-mattcl | 15.1 ± 0.7 | 13.8 | 18.2 | 18.64 ± 4.39 |
| mattcl-py | input-kcen | 15.9 ± 4.2 | 13.9 | 49.2 | 19.54 ± 6.88 |
| pting | input-lanjian | 53.3 ± 1.5 | 50.9 | 57.4 | 65.59 ± 15.28 |
| pting | input-mattcl | 53.8 ± 1.5 | 51.5 | 59.4 | 66.24 ± 15.43 |
| pting | input-kcen | 54.2 ± 2.7 | 51.6 | 69.2 | 66.65 ± 15.77 |
| pting | input-pting | 56.8 ± 3.1 | 54.6 | 76.3 | 69.95 ± 16.64 |
| kcen | input-lanjian | 85.5 ± 2.7 | 82.6 | 97.9 | 105.27 ± 24.58 |
| kcen | input-kcen | 86.3 ± 1.5 | 84.0 | 90.2 | 106.16 ± 24.63 |
| kcen | input-mattcl | 87.5 ± 2.2 | 83.8 | 92.5 | 107.68 ± 25.05 |
| kcen | input-pting | 90.8 ± 2.0 | 87.9 | 96.7 | 111.80 ± 25.98 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|