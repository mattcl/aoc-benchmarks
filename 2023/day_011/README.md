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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.31 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.4 | 1.2 | 1.05 ± 0.28 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.3 | 1.08 ± 0.29 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 4.9 | 3.44 ± 0.85 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.2 | 4.6 | 3.48 ± 0.86 |
| lanjian | input-kcen | 3.5 ± 0.5 | 2.7 | 6.6 | 3.97 ± 1.06 |
| lanjian | input-lanjian | 3.5 ± 0.5 | 2.7 | 5.9 | 4.01 ± 1.07 |
| mattcl-py | input-mattcl | 14.9 ± 0.5 | 14.0 | 17.7 | 16.94 ± 3.97 |
| mattcl-py | input-pting | 15.0 ± 0.6 | 14.1 | 17.9 | 16.96 ± 3.99 |
| mattcl-py | input-kcen | 15.1 ± 0.5 | 14.2 | 17.6 | 17.09 ± 3.99 |
| mattcl-py | input-lanjian | 15.2 ± 2.5 | 13.8 | 48.5 | 17.20 ± 4.87 |
| pting | input-kcen | 54.1 ± 1.6 | 51.7 | 59.0 | 61.37 ± 14.34 |
| pting | input-mattcl | 54.1 ± 1.7 | 52.0 | 61.7 | 61.38 ± 14.34 |
| pting | input-lanjian | 55.0 ± 6.9 | 51.6 | 89.8 | 62.34 ± 16.40 |
| pting | input-pting | 56.7 ± 1.4 | 54.4 | 60.9 | 64.27 ± 14.97 |
| kcen | input-lanjian | 85.3 ± 2.0 | 83.0 | 94.9 | 96.76 ± 22.53 |
| kcen | input-kcen | 87.6 ± 1.4 | 85.4 | 91.1 | 99.33 ± 23.07 |
| kcen | input-mattcl | 87.6 ± 1.6 | 85.1 | 92.0 | 99.38 ± 23.09 |
| kcen | input-pting | 93.0 ± 8.8 | 88.9 | 140.3 | 105.46 ± 26.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|