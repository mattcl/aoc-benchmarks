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
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.5 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.30 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.1 | 1.03 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.04 ± 0.30 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.1 | 5.5 | 3.56 ± 0.87 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.1 | 4.3 | 3.58 ± 0.83 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 3.0 | 6.7 | 4.16 ± 1.02 |
| lanjian | input-kcen | 3.5 ± 0.3 | 2.9 | 5.1 | 4.18 ± 0.99 |
| mattcl-py | input-mattcl | 15.0 ± 0.5 | 13.9 | 18.2 | 17.96 ± 3.92 |
| mattcl-py | input-pting | 15.1 ± 0.5 | 14.1 | 18.3 | 17.99 ± 3.93 |
| mattcl-py | input-lanjian | 15.1 ± 0.6 | 13.9 | 18.5 | 18.09 ± 3.97 |
| mattcl-py | input-kcen | 15.5 ± 3.2 | 14.0 | 47.0 | 18.57 ± 5.53 |
| pting | input-lanjian | 53.8 ± 3.6 | 50.7 | 71.3 | 64.26 ± 14.48 |
| pting | input-mattcl | 54.0 ± 1.4 | 51.6 | 58.9 | 64.45 ± 13.98 |
| pting | input-kcen | 54.1 ± 1.6 | 51.7 | 61.0 | 64.63 ± 14.05 |
| pting | input-pting | 56.3 ± 1.5 | 54.0 | 62.4 | 67.25 ± 14.59 |
| kcen | input-lanjian | 85.1 ± 3.4 | 82.2 | 102.8 | 101.69 ± 22.26 |
| kcen | input-mattcl | 86.2 ± 1.3 | 83.8 | 88.6 | 103.00 ± 22.23 |
| kcen | input-kcen | 87.0 ± 1.4 | 84.5 | 91.7 | 103.91 ± 22.44 |
| kcen | input-pting | 91.7 ± 6.0 | 88.5 | 123.2 | 109.48 ± 24.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|