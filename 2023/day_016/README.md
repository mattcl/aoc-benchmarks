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
| mattcl | input-pting | 4.3 ± 0.4 | 3.7 | 7.2 | 1.00 |
| mattcl | input-mattcl | 5.3 ± 0.5 | 4.9 | 8.7 | 1.24 ± 0.17 |
| mattcl | input-kcen | 5.5 ± 3.0 | 4.7 | 46.7 | 1.29 ± 0.71 |
| mattcl | input-lanjian | 6.3 ± 0.4 | 5.8 | 8.9 | 1.47 ± 0.18 |
| lanjian | input-pting | 32.8 ± 1.1 | 31.3 | 35.8 | 7.63 ± 0.80 |
| lanjian | input-kcen | 40.5 ± 1.1 | 38.9 | 43.1 | 9.41 ± 0.97 |
| lanjian | input-mattcl | 43.6 ± 1.1 | 41.6 | 46.6 | 10.13 ± 1.03 |
| lanjian | input-lanjian | 52.4 ± 1.1 | 50.6 | 55.5 | 12.17 ± 1.23 |
| pting | input-pting | 204.7 ± 7.6 | 198.5 | 225.6 | 47.58 ± 5.02 |
| mattcl-py | input-pting | 207.7 ± 6.5 | 200.0 | 225.7 | 48.28 ± 5.01 |
| pting | input-kcen | 253.8 ± 3.1 | 249.7 | 258.4 | 59.00 ± 5.88 |
| pting | input-mattcl | 258.0 ± 4.2 | 252.0 | 264.3 | 59.98 ± 6.02 |
| mattcl-py | input-kcen | 262.2 ± 4.6 | 257.5 | 272.3 | 60.96 ± 6.13 |
| mattcl-py | input-mattcl | 271.5 ± 8.1 | 262.4 | 286.0 | 63.12 ± 6.52 |
| pting | input-lanjian | 325.0 ± 4.9 | 315.7 | 330.3 | 75.55 ± 7.56 |
| mattcl-py | input-lanjian | 332.9 ± 5.6 | 327.7 | 347.0 | 77.38 ± 7.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|