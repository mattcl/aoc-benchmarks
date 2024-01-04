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
| mattcl | input-pting | 4.3 ± 0.6 | 3.6 | 8.8 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.5 | 4.6 | 7.9 | 1.20 ± 0.21 |
| mattcl | input-mattcl | 5.3 ± 0.5 | 4.8 | 8.7 | 1.24 ± 0.22 |
| mattcl | input-lanjian | 6.3 ± 0.5 | 5.8 | 8.9 | 1.46 ± 0.24 |
| lanjian | input-pting | 33.6 ± 1.0 | 32.1 | 36.3 | 7.79 ± 1.18 |
| lanjian | input-kcen | 41.5 ± 1.1 | 39.5 | 44.6 | 9.62 ± 1.45 |
| lanjian | input-mattcl | 44.4 ± 1.0 | 42.8 | 46.7 | 10.29 ± 1.55 |
| lanjian | input-lanjian | 53.3 ± 1.1 | 51.5 | 55.9 | 12.36 ± 1.85 |
| pting | input-pting | 201.2 ± 2.6 | 197.6 | 205.8 | 46.67 ± 6.96 |
| mattcl-py | input-pting | 204.5 ± 2.5 | 201.6 | 208.7 | 47.44 ± 7.07 |
| pting | input-kcen | 253.4 ± 4.7 | 248.1 | 262.3 | 58.80 ± 8.81 |
| pting | input-mattcl | 258.5 ± 4.9 | 249.7 | 264.5 | 59.98 ± 8.99 |
| mattcl-py | input-kcen | 263.2 ± 6.1 | 254.6 | 271.8 | 61.07 ± 9.18 |
| mattcl-py | input-mattcl | 265.2 ± 3.6 | 256.5 | 269.8 | 61.54 ± 9.18 |
| pting | input-lanjian | 326.5 ± 9.9 | 313.3 | 350.1 | 75.76 ± 11.49 |
| mattcl-py | input-lanjian | 328.8 ± 3.5 | 323.0 | 332.6 | 76.28 ± 11.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|