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
| mattcl | input-pting | 4.2 ± 0.4 | 3.2 | 6.7 | 1.00 |
| mattcl | input-kcen | 5.1 ± 0.5 | 4.6 | 8.4 | 1.22 ± 0.17 |
| mattcl | input-mattcl | 5.3 ± 0.5 | 4.7 | 9.0 | 1.26 ± 0.17 |
| mattcl | input-lanjian | 6.3 ± 0.8 | 5.7 | 12.3 | 1.50 ± 0.24 |
| lanjian | input-pting | 32.8 ± 0.9 | 31.7 | 35.6 | 7.80 ± 0.75 |
| lanjian | input-kcen | 40.9 ± 1.3 | 39.2 | 43.8 | 9.74 ± 0.95 |
| lanjian | input-mattcl | 44.2 ± 1.1 | 42.5 | 47.0 | 10.51 ± 1.00 |
| lanjian | input-lanjian | 53.1 ± 1.1 | 51.1 | 55.5 | 12.63 ± 1.19 |
| pting | input-pting | 202.7 ± 3.1 | 199.8 | 208.1 | 48.23 ± 4.50 |
| mattcl-py | input-pting | 206.9 ± 2.9 | 203.5 | 212.1 | 49.24 ± 4.59 |
| pting | input-kcen | 256.8 ± 6.4 | 248.7 | 265.4 | 61.10 ± 5.83 |
| pting | input-mattcl | 262.4 ± 4.5 | 256.7 | 269.5 | 62.43 ± 5.85 |
| mattcl-py | input-kcen | 264.9 ± 6.8 | 256.5 | 279.5 | 63.04 ± 6.03 |
| mattcl-py | input-mattcl | 270.7 ± 3.4 | 266.2 | 276.2 | 64.41 ± 5.99 |
| pting | input-lanjian | 330.2 ± 4.7 | 325.2 | 341.6 | 78.57 ± 7.32 |
| mattcl-py | input-lanjian | 331.3 ± 3.1 | 325.7 | 335.3 | 78.83 ± 7.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|