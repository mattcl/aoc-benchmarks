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
| mattcl | input-pting | 4.2 ± 0.4 | 3.5 | 6.8 | 1.00 |
| mattcl | input-mattcl | 5.3 ± 0.6 | 4.8 | 8.9 | 1.26 ± 0.18 |
| mattcl | input-lanjian | 6.2 ± 0.6 | 5.7 | 10.8 | 1.49 ± 0.20 |
| lanjian | input-pting | 32.2 ± 0.9 | 31.2 | 35.3 | 7.69 ± 0.79 |
| lanjian | input-mattcl | 42.8 ± 1.0 | 41.1 | 45.1 | 10.22 ± 1.03 |
| lanjian | input-lanjian | 51.5 ± 1.1 | 49.9 | 54.7 | 12.29 ± 1.24 |
| pting | input-pting | 203.1 ± 2.7 | 200.0 | 208.3 | 48.47 ± 4.81 |
| mattcl-py | input-pting | 206.4 ± 2.7 | 203.2 | 212.8 | 49.25 ± 4.89 |
| pting | input-mattcl | 264.0 ± 5.3 | 255.1 | 275.2 | 62.99 ± 6.33 |
| mattcl-py | input-mattcl | 268.0 ± 2.4 | 265.4 | 273.9 | 63.95 ± 6.32 |
| pting | input-lanjian | 320.5 ± 4.5 | 316.1 | 328.9 | 76.48 ± 7.60 |
| mattcl-py | input-lanjian | 333.4 ± 5.2 | 324.1 | 341.0 | 79.55 ± 7.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|