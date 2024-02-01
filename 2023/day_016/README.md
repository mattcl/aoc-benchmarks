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
| mattcl | input-pting | 4.2 ± 0.4 | 3.6 | 7.0 | 1.00 |
| mattcl | input-kcen | 5.1 ± 0.5 | 4.6 | 7.3 | 1.22 ± 0.16 |
| mattcl | input-mattcl | 5.3 ± 0.5 | 4.8 | 7.9 | 1.26 ± 0.18 |
| mattcl | input-lanjian | 6.4 ± 0.8 | 5.7 | 11.4 | 1.51 ± 0.25 |
| lanjian | input-pting | 33.4 ± 1.1 | 32.0 | 36.1 | 7.94 ± 0.81 |
| lanjian | input-kcen | 40.7 ± 1.1 | 39.3 | 43.6 | 9.68 ± 0.98 |
| lanjian | input-mattcl | 44.0 ± 0.9 | 42.8 | 46.7 | 10.46 ± 1.04 |
| lanjian | input-lanjian | 53.2 ± 1.0 | 51.6 | 55.5 | 12.65 ± 1.25 |
| pting | input-pting | 202.3 ± 3.2 | 195.9 | 208.0 | 48.09 ± 4.75 |
| mattcl-py | input-pting | 206.2 ± 3.2 | 201.6 | 212.2 | 49.01 ± 4.84 |
| pting | input-kcen | 252.4 ± 4.7 | 246.8 | 262.9 | 60.02 ± 5.95 |
| pting | input-mattcl | 261.8 ± 3.9 | 255.6 | 267.1 | 62.25 ± 6.14 |
| mattcl-py | input-kcen | 264.2 ± 5.0 | 253.9 | 271.3 | 62.81 ± 6.24 |
| mattcl-py | input-mattcl | 267.5 ± 4.0 | 259.9 | 274.1 | 63.59 ± 6.27 |
| pting | input-lanjian | 328.3 ± 4.0 | 321.9 | 334.8 | 78.05 ± 7.67 |
| mattcl-py | input-lanjian | 332.8 ± 5.6 | 328.4 | 343.8 | 79.13 ± 7.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|