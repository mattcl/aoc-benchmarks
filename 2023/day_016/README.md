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
| mattcl | input-pting | 4.2 ± 0.4 | 3.6 | 6.4 | 1.00 |
| mattcl | input-kcen | 5.1 ± 0.6 | 4.6 | 9.9 | 1.22 ± 0.19 |
| mattcl | input-mattcl | 5.2 ± 0.4 | 4.7 | 7.3 | 1.24 ± 0.15 |
| mattcl | input-lanjian | 6.3 ± 0.7 | 5.7 | 11.7 | 1.49 ± 0.22 |
| lanjian | input-pting | 33.4 ± 1.1 | 32.2 | 36.5 | 7.95 ± 0.78 |
| lanjian | input-kcen | 41.2 ± 1.0 | 39.6 | 44.2 | 9.81 ± 0.93 |
| lanjian | input-mattcl | 44.5 ± 1.1 | 42.9 | 47.6 | 10.59 ± 1.01 |
| lanjian | input-lanjian | 53.5 ± 1.0 | 51.8 | 56.4 | 12.73 ± 1.20 |
| pting | input-pting | 200.3 ± 2.2 | 197.4 | 203.5 | 47.64 ± 4.43 |
| mattcl-py | input-pting | 204.0 ± 2.0 | 201.0 | 207.5 | 48.52 ± 4.51 |
| pting | input-kcen | 251.4 ± 4.0 | 247.1 | 261.5 | 59.79 ± 5.60 |
| pting | input-mattcl | 258.1 ± 3.4 | 251.7 | 262.4 | 61.39 ± 5.73 |
| mattcl-py | input-kcen | 263.2 ± 4.9 | 257.8 | 274.5 | 62.60 ± 5.90 |
| mattcl-py | input-mattcl | 266.2 ± 2.3 | 263.4 | 270.0 | 63.32 ± 5.87 |
| pting | input-lanjian | 324.2 ± 3.8 | 315.6 | 327.1 | 77.09 ± 7.17 |
| mattcl-py | input-lanjian | 330.2 ± 4.1 | 324.5 | 335.7 | 78.54 ± 7.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|