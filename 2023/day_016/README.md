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
| mattcl | input-pting | 4.2 ± 0.4 | 3.7 | 6.7 | 1.00 |
| mattcl | input-kcen | 5.1 ± 0.4 | 4.7 | 7.2 | 1.20 ± 0.15 |
| mattcl | input-mattcl | 5.3 ± 0.5 | 4.8 | 8.0 | 1.25 ± 0.16 |
| mattcl | input-lanjian | 6.3 ± 0.6 | 5.8 | 9.2 | 1.49 ± 0.19 |
| lanjian | input-pting | 33.2 ± 0.9 | 31.9 | 36.3 | 7.83 ± 0.77 |
| lanjian | input-kcen | 40.9 ± 1.1 | 39.0 | 43.4 | 9.67 ± 0.95 |
| lanjian | input-mattcl | 44.2 ± 1.1 | 42.9 | 47.0 | 10.44 ± 1.02 |
| lanjian | input-lanjian | 53.3 ± 1.4 | 51.0 | 56.0 | 12.58 ± 1.23 |
| pting | input-pting | 202.3 ± 2.9 | 196.5 | 208.7 | 47.77 ± 4.53 |
| mattcl-py | input-pting | 205.8 ± 3.3 | 202.5 | 214.2 | 48.60 ± 4.63 |
| pting | input-kcen | 253.2 ± 4.2 | 247.5 | 261.9 | 59.78 ± 5.70 |
| pting | input-mattcl | 265.6 ± 9.3 | 259.3 | 292.8 | 62.71 ± 6.28 |
| mattcl-py | input-kcen | 266.4 ± 4.8 | 258.4 | 275.1 | 62.90 ± 6.01 |
| mattcl-py | input-mattcl | 269.7 ± 3.7 | 264.4 | 274.6 | 63.68 ± 6.04 |
| pting | input-lanjian | 329.2 ± 5.5 | 320.2 | 338.1 | 77.75 ± 7.41 |
| mattcl-py | input-lanjian | 335.1 ± 3.6 | 328.6 | 340.4 | 79.12 ± 7.47 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|