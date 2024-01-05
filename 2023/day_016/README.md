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
| mattcl | input-pting | 4.4 ± 0.7 | 3.8 | 11.2 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.6 | 4.7 | 9.6 | 1.19 ± 0.24 |
| mattcl | input-mattcl | 5.4 ± 0.7 | 4.7 | 9.9 | 1.22 ± 0.25 |
| mattcl | input-lanjian | 6.4 ± 0.7 | 5.7 | 10.5 | 1.46 ± 0.29 |
| lanjian | input-pting | 32.9 ± 0.9 | 31.7 | 36.1 | 7.47 ± 1.25 |
| lanjian | input-kcen | 40.9 ± 1.0 | 39.4 | 43.2 | 9.29 ± 1.55 |
| lanjian | input-mattcl | 44.0 ± 1.0 | 42.8 | 46.5 | 10.00 ± 1.66 |
| lanjian | input-lanjian | 53.2 ± 1.1 | 51.5 | 55.4 | 12.07 ± 2.00 |
| pting | input-pting | 202.6 ± 3.2 | 197.9 | 207.8 | 46.00 ± 7.60 |
| mattcl-py | input-pting | 205.4 ± 2.6 | 202.1 | 210.7 | 46.65 ± 7.70 |
| pting | input-kcen | 252.6 ± 3.1 | 248.4 | 258.8 | 57.35 ± 9.47 |
| pting | input-mattcl | 262.0 ± 3.5 | 256.4 | 266.4 | 59.48 ± 9.82 |
| mattcl-py | input-kcen | 264.5 ± 4.9 | 259.0 | 271.2 | 60.06 ± 9.95 |
| mattcl-py | input-mattcl | 267.1 ± 2.9 | 263.2 | 271.7 | 60.65 ± 10.00 |
| pting | input-lanjian | 328.6 ± 5.6 | 319.6 | 336.7 | 74.62 ± 12.35 |
| mattcl-py | input-lanjian | 335.5 ± 6.9 | 329.8 | 349.7 | 76.18 ± 12.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|