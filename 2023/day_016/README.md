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
| mattcl | input-pting | 4.4 ± 0.5 | 3.9 | 7.1 | 1.00 |
| mattcl | input-kcen | 5.3 ± 0.5 | 4.7 | 7.6 | 1.20 ± 0.19 |
| mattcl | input-mattcl | 5.4 ± 0.7 | 4.7 | 11.6 | 1.24 ± 0.21 |
| mattcl | input-lanjian | 6.4 ± 0.5 | 5.8 | 8.7 | 1.46 ± 0.21 |
| lanjian | input-pting | 33.4 ± 1.0 | 32.1 | 37.3 | 7.61 ± 0.95 |
| lanjian | input-kcen | 41.1 ± 1.1 | 39.3 | 43.8 | 9.39 ± 1.16 |
| lanjian | input-mattcl | 44.6 ± 1.1 | 43.4 | 47.2 | 10.18 ± 1.26 |
| lanjian | input-lanjian | 53.1 ± 1.1 | 51.4 | 55.4 | 12.12 ± 1.49 |
| pting | input-pting | 203.4 ± 3.2 | 198.8 | 208.8 | 46.43 ± 5.67 |
| mattcl-py | input-pting | 210.0 ± 5.9 | 203.0 | 219.6 | 47.94 ± 5.96 |
| pting | input-kcen | 254.6 ± 6.0 | 247.2 | 264.7 | 58.11 ± 7.16 |
| pting | input-mattcl | 263.3 ± 2.9 | 257.7 | 267.1 | 60.09 ± 7.30 |
| mattcl-py | input-kcen | 266.4 ± 6.2 | 260.8 | 279.0 | 60.80 ± 7.49 |
| mattcl-py | input-mattcl | 269.4 ± 3.4 | 263.7 | 274.0 | 61.48 ± 7.48 |
| pting | input-lanjian | 332.0 ± 5.0 | 327.0 | 343.6 | 75.77 ± 9.24 |
| mattcl-py | input-lanjian | 332.0 ± 3.9 | 327.8 | 338.9 | 75.78 ± 9.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|