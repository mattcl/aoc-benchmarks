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
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.6 | 1.05 ± 0.35 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.6 | 1.07 ± 0.36 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.5 | 1.7 | 1.12 ± 0.34 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.0 | 4.2 | 3.69 ± 0.99 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.0 | 4.9 | 3.73 ± 1.00 |
| lanjian | input-kcen | 3.5 ± 0.5 | 2.9 | 5.5 | 4.30 ± 1.24 |
| lanjian | input-lanjian | 3.5 ± 0.5 | 2.7 | 6.1 | 4.30 ± 1.25 |
| mattcl-py | input-pting | 15.1 ± 0.6 | 14.3 | 18.3 | 18.74 ± 4.84 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 14.0 | 18.3 | 18.82 ± 4.86 |
| mattcl-py | input-mattcl | 15.2 ± 0.7 | 14.1 | 18.5 | 18.87 ± 4.91 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 14.2 | 18.3 | 18.96 ± 4.90 |
| pting | input-lanjian | 53.6 ± 1.8 | 51.2 | 59.5 | 66.37 ± 17.12 |
| pting | input-kcen | 53.7 ± 1.3 | 52.0 | 56.6 | 66.47 ± 17.07 |
| pting | input-mattcl | 54.5 ± 4.6 | 51.8 | 79.4 | 67.56 ± 18.21 |
| pting | input-pting | 56.5 ± 2.7 | 54.0 | 72.4 | 69.92 ± 18.19 |
| kcen | input-lanjian | 91.6 ± 1.5 | 89.0 | 95.3 | 113.41 ± 29.06 |
| kcen | input-kcen | 93.3 ± 1.5 | 90.5 | 96.2 | 115.59 ± 29.62 |
| kcen | input-mattcl | 93.4 ± 1.6 | 90.8 | 97.1 | 115.66 ± 29.65 |
| kcen | input-pting | 97.0 ± 1.5 | 93.9 | 99.6 | 120.19 ± 30.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|