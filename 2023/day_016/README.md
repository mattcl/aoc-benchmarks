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
| mattcl | input-pting | 4.3 ± 0.5 | 3.8 | 7.1 | 1.00 |
| mattcl | input-kcen | 5.1 ± 0.4 | 4.6 | 7.3 | 1.19 ± 0.16 |
| mattcl | input-mattcl | 5.3 ± 0.5 | 4.7 | 7.8 | 1.25 ± 0.18 |
| mattcl | input-lanjian | 6.3 ± 0.5 | 5.7 | 8.4 | 1.48 ± 0.20 |
| lanjian | input-pting | 33.8 ± 0.9 | 32.3 | 36.9 | 7.94 ± 0.90 |
| lanjian | input-kcen | 41.5 ± 1.0 | 39.7 | 44.3 | 9.76 ± 1.09 |
| lanjian | input-mattcl | 45.0 ± 1.2 | 43.5 | 47.9 | 10.57 ± 1.19 |
| lanjian | input-lanjian | 54.0 ± 1.3 | 51.7 | 59.0 | 12.68 ± 1.42 |
| pting | input-pting | 201.7 ± 2.6 | 195.3 | 205.4 | 47.41 ± 5.23 |
| mattcl-py | input-pting | 206.7 ± 3.1 | 202.2 | 212.5 | 48.60 ± 5.37 |
| pting | input-kcen | 256.1 ± 5.0 | 249.9 | 265.1 | 60.21 ± 6.69 |
| mattcl-py | input-kcen | 263.9 ± 6.5 | 258.1 | 281.2 | 62.04 ± 6.96 |
| pting | input-mattcl | 264.1 ± 3.2 | 259.3 | 267.4 | 62.07 ± 6.84 |
| mattcl-py | input-mattcl | 266.8 ± 3.7 | 261.2 | 272.6 | 62.72 ± 6.92 |
| pting | input-lanjian | 330.0 ± 2.5 | 326.0 | 334.1 | 77.58 ± 8.51 |
| mattcl-py | input-lanjian | 334.3 ± 5.9 | 326.4 | 347.6 | 78.59 ± 8.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|