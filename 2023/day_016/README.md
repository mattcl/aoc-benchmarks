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
| mattcl | input-pting | 4.3 ± 0.5 | 3.7 | 6.9 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.6 | 4.7 | 9.5 | 1.20 ± 0.20 |
| mattcl | input-mattcl | 5.3 ± 0.5 | 4.8 | 8.5 | 1.23 ± 0.19 |
| mattcl | input-lanjian | 6.2 ± 0.5 | 5.8 | 10.6 | 1.44 ± 0.20 |
| lanjian | input-pting | 33.8 ± 0.9 | 32.7 | 36.5 | 7.84 ± 0.95 |
| lanjian | input-kcen | 41.9 ± 1.1 | 40.4 | 45.9 | 9.72 ± 1.18 |
| lanjian | input-mattcl | 45.4 ± 1.1 | 43.7 | 47.7 | 10.52 ± 1.27 |
| lanjian | input-lanjian | 54.3 ± 1.1 | 52.4 | 57.2 | 12.59 ± 1.51 |
| pting | input-pting | 203.7 ± 2.4 | 200.4 | 209.9 | 47.20 ± 5.62 |
| mattcl-py | input-pting | 206.4 ± 2.2 | 202.9 | 211.4 | 47.84 ± 5.69 |
| pting | input-kcen | 254.1 ± 4.8 | 248.4 | 263.2 | 58.88 ± 7.06 |
| pting | input-mattcl | 263.0 ± 7.1 | 248.7 | 275.3 | 60.96 ± 7.41 |
| mattcl-py | input-kcen | 267.1 ± 6.3 | 259.5 | 276.9 | 61.90 ± 7.47 |
| mattcl-py | input-mattcl | 268.6 ± 5.5 | 259.7 | 277.3 | 62.24 ± 7.48 |
| pting | input-lanjian | 328.0 ± 5.1 | 319.9 | 334.1 | 76.01 ± 9.08 |
| mattcl-py | input-lanjian | 333.8 ± 3.5 | 329.5 | 340.8 | 77.35 ± 9.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|