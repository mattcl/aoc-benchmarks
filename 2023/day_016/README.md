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
| mattcl | input-pting | 4.4 ± 0.4 | 3.9 | 7.0 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.4 | 4.7 | 8.5 | 1.19 ± 0.16 |
| mattcl | input-mattcl | 5.3 ± 0.4 | 4.9 | 8.4 | 1.23 ± 0.15 |
| mattcl | input-lanjian | 6.4 ± 0.5 | 5.9 | 10.0 | 1.46 ± 0.18 |
| lanjian | input-pting | 33.9 ± 1.0 | 32.8 | 37.1 | 7.79 ± 0.81 |
| lanjian | input-kcen | 41.9 ± 1.2 | 40.2 | 47.8 | 9.62 ± 1.01 |
| lanjian | input-mattcl | 45.1 ± 1.0 | 43.8 | 47.6 | 10.37 ± 1.07 |
| lanjian | input-lanjian | 53.7 ± 1.1 | 51.9 | 56.5 | 12.34 ± 1.27 |
| pting | input-pting | 203.2 ± 2.7 | 200.1 | 209.0 | 46.67 ± 4.73 |
| mattcl-py | input-pting | 207.6 ± 3.5 | 202.9 | 212.9 | 47.68 ± 4.86 |
| pting | input-kcen | 255.2 ± 5.1 | 250.8 | 265.7 | 58.63 ± 6.01 |
| pting | input-mattcl | 263.8 ± 4.5 | 256.1 | 270.6 | 60.61 ± 6.18 |
| mattcl-py | input-kcen | 269.2 ± 5.2 | 262.8 | 275.9 | 61.83 ± 6.33 |
| mattcl-py | input-mattcl | 271.6 ± 3.8 | 265.5 | 277.7 | 62.39 ± 6.33 |
| pting | input-lanjian | 328.1 ± 5.5 | 322.8 | 339.5 | 75.37 ± 7.68 |
| mattcl-py | input-lanjian | 332.4 ± 4.6 | 325.1 | 337.8 | 76.36 ± 7.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|