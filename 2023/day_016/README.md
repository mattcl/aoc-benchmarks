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
| mattcl | input-pting | 4.4 ± 0.6 | 3.7 | 8.7 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.6 | 4.4 | 9.9 | 1.19 ± 0.23 |
| mattcl | input-mattcl | 5.4 ± 0.4 | 4.9 | 7.6 | 1.22 ± 0.20 |
| mattcl | input-lanjian | 6.4 ± 0.7 | 5.8 | 11.7 | 1.46 ± 0.27 |
| lanjian | input-pting | 32.4 ± 1.0 | 31.3 | 35.3 | 7.38 ± 1.10 |
| lanjian | input-kcen | 39.4 ± 0.7 | 38.3 | 42.6 | 8.96 ± 1.31 |
| lanjian | input-mattcl | 42.8 ± 1.0 | 41.3 | 45.0 | 9.72 ± 1.43 |
| lanjian | input-lanjian | 51.3 ± 1.1 | 49.4 | 53.7 | 11.67 ± 1.71 |
| pting | input-pting | 200.5 ± 1.8 | 198.5 | 203.9 | 45.60 ± 6.65 |
| mattcl-py | input-pting | 203.4 ± 3.2 | 200.3 | 209.7 | 46.25 ± 6.77 |
| pting | input-kcen | 251.8 ± 5.0 | 246.2 | 260.2 | 57.26 ± 8.41 |
| pting | input-mattcl | 259.1 ± 3.4 | 253.8 | 263.9 | 58.91 ± 8.61 |
| mattcl-py | input-kcen | 265.0 ± 5.8 | 258.0 | 273.3 | 60.25 ± 8.87 |
| mattcl-py | input-mattcl | 266.3 ± 3.1 | 262.2 | 270.4 | 60.55 ± 8.84 |
| pting | input-lanjian | 322.5 ± 7.0 | 313.7 | 336.4 | 73.35 ± 10.79 |
| mattcl-py | input-lanjian | 331.4 ± 4.8 | 325.9 | 340.3 | 75.36 ± 11.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|