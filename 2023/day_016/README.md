# Day 16 benchmarks

[link to problem](https://adventofcode.com/2023/day/16)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 16)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 4.3 ± 0.4 | 3.9 | 7.1 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.6 | 4.3 | 9.3 | 1.21 ± 0.19 |
| mattcl | input-mattcl | 5.4 ± 0.5 | 4.8 | 8.6 | 1.25 ± 0.16 |
| mattcl | input-lanjian | 6.3 ± 0.4 | 5.9 | 8.6 | 1.48 ± 0.18 |
| lanjian | input-pting | 33.6 ± 0.8 | 32.6 | 36.9 | 7.83 ± 0.78 |
| lanjian | input-kcen | 42.0 ± 1.1 | 40.4 | 45.6 | 9.80 ± 0.99 |
| lanjian | input-mattcl | 45.0 ± 1.0 | 43.4 | 47.9 | 10.50 ± 1.05 |
| lanjian | input-lanjian | 54.0 ± 1.0 | 52.3 | 56.1 | 12.58 ± 1.24 |
| pting | input-pting | 203.5 ± 3.2 | 199.2 | 209.9 | 47.41 ± 4.66 |
| mattcl-py | input-pting | 207.8 ± 2.8 | 204.4 | 212.8 | 48.41 ± 4.74 |
| pting | input-kcen | 258.9 ± 6.5 | 248.4 | 267.2 | 60.32 ± 6.04 |
| pting | input-mattcl | 263.0 ± 4.3 | 254.4 | 268.8 | 61.29 ± 6.03 |
| mattcl-py | input-kcen | 263.6 ± 2.8 | 259.7 | 269.3 | 61.43 ± 6.00 |
| mattcl-py | input-mattcl | 268.1 ± 2.7 | 263.9 | 272.3 | 62.48 ± 6.09 |
| pting | input-lanjian | 330.7 ± 8.2 | 322.3 | 349.0 | 77.07 ± 7.71 |
| mattcl-py | input-lanjian | 333.2 ± 5.5 | 324.0 | 341.3 | 77.64 ± 7.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|