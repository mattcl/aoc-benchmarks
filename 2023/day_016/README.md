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
| mattcl | input-pting | 4.2 ± 0.4 | 3.4 | 6.8 | 1.00 |
| mattcl | input-kcen | 5.1 ± 0.4 | 4.4 | 9.5 | 1.20 ± 0.15 |
| mattcl | input-mattcl | 5.3 ± 0.5 | 4.7 | 8.9 | 1.24 ± 0.17 |
| mattcl | input-lanjian | 6.2 ± 0.4 | 5.7 | 8.9 | 1.47 ± 0.17 |
| lanjian | input-pting | 33.3 ± 0.7 | 32.2 | 35.6 | 7.85 ± 0.78 |
| lanjian | input-kcen | 41.2 ± 0.8 | 39.9 | 44.2 | 9.73 ± 0.96 |
| lanjian | input-mattcl | 44.5 ± 1.1 | 43.0 | 47.8 | 10.51 ± 1.05 |
| lanjian | input-lanjian | 53.3 ± 1.0 | 51.7 | 56.4 | 12.60 ± 1.24 |
| pting | input-pting | 200.7 ± 2.3 | 198.3 | 205.2 | 47.39 ± 4.63 |
| mattcl-py | input-pting | 205.0 ± 2.9 | 200.8 | 210.5 | 48.42 ± 4.74 |
| pting | input-kcen | 252.6 ± 6.5 | 243.9 | 263.9 | 59.65 ± 5.98 |
| pting | input-mattcl | 257.5 ± 5.5 | 249.6 | 267.6 | 60.81 ± 6.04 |
| mattcl-py | input-kcen | 263.9 ± 6.6 | 255.3 | 274.5 | 62.31 ± 6.24 |
| mattcl-py | input-mattcl | 267.1 ± 4.8 | 260.4 | 275.1 | 63.07 ± 6.22 |
| pting | input-lanjian | 321.5 ± 6.6 | 313.5 | 332.5 | 75.93 ± 7.53 |
| mattcl-py | input-lanjian | 335.1 ± 8.1 | 326.5 | 345.1 | 79.13 ± 7.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|