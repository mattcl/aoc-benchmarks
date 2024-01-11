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
| mattcl | input-pting | 4.3 ± 0.5 | 3.4 | 9.5 | 1.00 |
| mattcl | input-kcen | 5.1 ± 0.5 | 4.7 | 8.0 | 1.20 ± 0.19 |
| mattcl | input-mattcl | 5.3 ± 0.5 | 4.9 | 8.7 | 1.25 ± 0.19 |
| mattcl | input-lanjian | 6.4 ± 0.6 | 5.7 | 10.3 | 1.49 ± 0.23 |
| lanjian | input-pting | 33.1 ± 0.9 | 31.8 | 35.7 | 7.75 ± 0.99 |
| lanjian | input-kcen | 41.1 ± 1.2 | 39.3 | 43.7 | 9.61 ± 1.24 |
| lanjian | input-mattcl | 43.9 ± 0.7 | 42.9 | 46.3 | 10.28 ± 1.30 |
| lanjian | input-lanjian | 53.2 ± 1.2 | 51.2 | 56.9 | 12.44 ± 1.58 |
| pting | input-pting | 202.1 ± 2.1 | 196.4 | 204.6 | 47.29 ± 5.95 |
| mattcl-py | input-pting | 204.9 ± 2.1 | 202.0 | 208.8 | 47.95 ± 6.03 |
| pting | input-kcen | 255.0 ± 6.1 | 247.7 | 265.9 | 59.67 ± 7.62 |
| pting | input-mattcl | 264.1 ± 4.6 | 256.3 | 270.7 | 61.80 ± 7.82 |
| mattcl-py | input-kcen | 267.0 ± 8.4 | 258.2 | 286.2 | 62.48 ± 8.08 |
| mattcl-py | input-mattcl | 271.5 ± 3.7 | 265.7 | 275.5 | 63.53 ± 8.01 |
| pting | input-lanjian | 329.3 ± 6.3 | 322.5 | 343.2 | 77.05 ± 9.77 |
| mattcl-py | input-lanjian | 334.0 ± 5.7 | 326.7 | 345.3 | 78.15 ± 9.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|