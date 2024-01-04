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
| mattcl | input-pting | 4.4 ± 0.6 | 3.7 | 8.9 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.4 | 4.7 | 7.5 | 1.19 ± 0.20 |
| mattcl | input-mattcl | 5.4 ± 0.6 | 4.8 | 8.9 | 1.24 ± 0.23 |
| mattcl | input-lanjian | 6.4 ± 0.7 | 5.7 | 11.6 | 1.48 ± 0.27 |
| lanjian | input-pting | 33.6 ± 0.9 | 32.3 | 37.1 | 7.71 ± 1.13 |
| lanjian | input-kcen | 41.9 ± 1.0 | 40.3 | 44.8 | 9.63 ± 1.41 |
| lanjian | input-mattcl | 44.9 ± 1.3 | 42.9 | 49.5 | 10.31 ± 1.52 |
| lanjian | input-lanjian | 53.9 ± 1.3 | 51.6 | 56.8 | 12.38 ± 1.82 |
| pting | input-pting | 201.5 ± 2.8 | 197.9 | 206.3 | 46.25 ± 6.72 |
| mattcl-py | input-pting | 205.4 ± 1.9 | 202.2 | 208.6 | 47.14 ± 6.84 |
| pting | input-kcen | 253.1 ± 5.0 | 246.3 | 262.3 | 58.10 ± 8.49 |
| mattcl-py | input-kcen | 261.5 ± 4.1 | 255.6 | 271.2 | 60.02 ± 8.74 |
| pting | input-mattcl | 262.7 ± 3.6 | 255.8 | 267.6 | 60.31 ± 8.77 |
| mattcl-py | input-mattcl | 270.3 ± 3.0 | 266.2 | 277.3 | 62.05 ± 9.01 |
| pting | input-lanjian | 326.3 ± 4.0 | 320.7 | 332.2 | 74.90 ± 10.88 |
| mattcl-py | input-lanjian | 331.9 ± 5.8 | 326.3 | 345.9 | 76.20 ± 11.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|