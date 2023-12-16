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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.2 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.03 ± 0.30 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.4 | 1.5 | 1.08 ± 0.27 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 4.0 | 3.48 ± 0.84 |
| lanjian | input-mattcl | 3.0 ± 0.4 | 2.1 | 5.2 | 3.50 ± 0.90 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.7 | 5.7 | 3.96 ± 0.99 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.7 | 6.5 | 4.01 ± 0.99 |
| mattcl-py | input-lanjian | 15.2 ± 0.5 | 14.2 | 18.8 | 17.55 ± 3.93 |
| mattcl-py | input-pting | 15.2 ± 0.6 | 14.2 | 17.8 | 17.56 ± 3.95 |
| mattcl-py | input-mattcl | 15.3 ± 0.5 | 14.6 | 17.7 | 17.64 ± 3.95 |
| mattcl-py | input-kcen | 15.4 ± 0.6 | 14.2 | 18.1 | 17.79 ± 4.01 |
| pting | input-lanjian | 53.3 ± 1.2 | 51.2 | 55.8 | 61.53 ± 13.72 |
| pting | input-mattcl | 54.2 ± 2.1 | 52.0 | 65.2 | 62.60 ± 14.08 |
| pting | input-kcen | 54.6 ± 3.9 | 51.1 | 74.5 | 63.00 ± 14.67 |
| pting | input-pting | 56.4 ± 1.2 | 54.9 | 60.6 | 65.12 ± 14.51 |
| kcen | input-lanjian | 92.6 ± 6.6 | 88.5 | 128.1 | 106.90 ± 24.90 |
| kcen | input-kcen | 93.4 ± 2.6 | 90.5 | 104.8 | 107.79 ± 24.09 |
| kcen | input-mattcl | 93.9 ± 2.4 | 90.9 | 103.9 | 108.40 ± 24.19 |
| kcen | input-pting | 97.1 ± 1.8 | 93.2 | 101.4 | 112.03 ± 24.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|