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
| mattcl | input-pting | 4.2 ± 0.5 | 3.3 | 6.9 | 1.00 |
| mattcl | input-kcen | 5.1 ± 0.5 | 4.6 | 8.4 | 1.21 ± 0.19 |
| mattcl | input-mattcl | 5.3 ± 0.4 | 4.8 | 7.7 | 1.25 ± 0.18 |
| mattcl | input-lanjian | 6.3 ± 0.6 | 5.7 | 9.1 | 1.50 ± 0.23 |
| lanjian | input-pting | 32.9 ± 1.0 | 31.3 | 36.3 | 7.80 ± 0.94 |
| lanjian | input-kcen | 40.1 ± 0.9 | 38.8 | 43.4 | 9.51 ± 1.13 |
| lanjian | input-mattcl | 43.8 ± 1.0 | 42.2 | 47.6 | 10.38 ± 1.23 |
| lanjian | input-lanjian | 52.5 ± 1.0 | 51.0 | 55.3 | 12.45 ± 1.47 |
| pting | input-pting | 201.6 ± 3.0 | 197.1 | 206.1 | 47.80 ± 5.61 |
| mattcl-py | input-pting | 203.3 ± 2.5 | 199.0 | 209.2 | 48.21 ± 5.65 |
| pting | input-kcen | 252.5 ± 6.0 | 244.1 | 262.3 | 59.88 ± 7.12 |
| pting | input-mattcl | 258.7 ± 4.5 | 252.5 | 267.2 | 61.34 ± 7.22 |
| mattcl-py | input-kcen | 263.4 ± 4.9 | 254.0 | 271.3 | 62.47 ± 7.37 |
| mattcl-py | input-mattcl | 268.3 ± 5.1 | 259.0 | 277.1 | 63.61 ± 7.51 |
| pting | input-lanjian | 323.2 ± 4.9 | 318.1 | 332.8 | 76.63 ± 9.00 |
| mattcl-py | input-lanjian | 329.2 ± 1.9 | 326.2 | 332.7 | 78.05 ± 9.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|