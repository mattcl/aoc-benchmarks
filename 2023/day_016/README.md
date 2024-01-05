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
| mattcl | input-pting | 4.6 ± 2.1 | 3.9 | 33.4 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.6 | 4.3 | 9.4 | 1.12 ± 0.53 |
| mattcl | input-mattcl | 5.3 ± 0.5 | 4.8 | 8.3 | 1.15 ± 0.54 |
| mattcl | input-lanjian | 6.3 ± 0.5 | 5.8 | 10.7 | 1.36 ± 0.64 |
| lanjian | input-pting | 33.6 ± 0.9 | 32.3 | 36.7 | 7.26 ± 3.34 |
| lanjian | input-kcen | 41.5 ± 1.2 | 40.0 | 46.1 | 8.98 ± 4.14 |
| lanjian | input-mattcl | 44.5 ± 1.0 | 43.0 | 47.6 | 9.63 ± 4.44 |
| lanjian | input-lanjian | 54.0 ± 1.0 | 52.0 | 56.3 | 11.67 ± 5.37 |
| pting | input-pting | 200.5 ± 2.1 | 196.7 | 204.3 | 43.36 ± 19.95 |
| mattcl-py | input-pting | 203.7 ± 3.3 | 200.4 | 210.5 | 44.06 ± 20.28 |
| pting | input-kcen | 255.1 ± 6.1 | 247.0 | 265.1 | 55.15 ± 25.41 |
| pting | input-mattcl | 259.2 ± 4.6 | 253.5 | 267.6 | 56.06 ± 25.81 |
| mattcl-py | input-mattcl | 264.0 ± 4.1 | 258.5 | 269.1 | 57.09 ± 26.29 |
| mattcl-py | input-kcen | 264.9 ± 6.5 | 256.2 | 276.2 | 57.29 ± 26.40 |
| pting | input-lanjian | 322.6 ± 4.0 | 316.1 | 327.4 | 69.75 ± 32.11 |
| mattcl-py | input-lanjian | 329.8 ± 5.4 | 324.2 | 339.3 | 71.31 ± 32.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|