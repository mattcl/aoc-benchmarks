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
| mattcl | input-pting | 4.3 ± 0.6 | 3.6 | 9.3 | 1.00 |
| mattcl | input-kcen | 5.1 ± 0.5 | 4.6 | 9.9 | 1.19 ± 0.21 |
| mattcl | input-mattcl | 5.3 ± 0.6 | 4.8 | 9.0 | 1.24 ± 0.22 |
| mattcl | input-lanjian | 6.6 ± 3.2 | 5.7 | 50.5 | 1.54 ± 0.78 |
| lanjian | input-pting | 33.0 ± 1.2 | 31.5 | 36.3 | 7.76 ± 1.14 |
| lanjian | input-kcen | 40.5 ± 1.1 | 38.6 | 43.8 | 9.52 ± 1.39 |
| lanjian | input-mattcl | 44.0 ± 0.9 | 42.4 | 46.8 | 10.32 ± 1.49 |
| lanjian | input-lanjian | 52.9 ± 1.2 | 50.7 | 55.3 | 12.43 ± 1.80 |
| pting | input-pting | 202.1 ± 2.1 | 199.2 | 208.0 | 47.47 ± 6.81 |
| mattcl-py | input-pting | 207.2 ± 3.2 | 203.3 | 212.2 | 48.65 ± 7.00 |
| pting | input-kcen | 254.5 ± 6.7 | 247.8 | 268.0 | 59.76 ± 8.69 |
| pting | input-mattcl | 261.7 ± 3.9 | 253.4 | 267.1 | 61.46 ± 8.84 |
| mattcl-py | input-kcen | 266.7 ± 5.1 | 259.8 | 276.1 | 62.64 ± 9.04 |
| mattcl-py | input-mattcl | 268.9 ± 3.2 | 262.6 | 273.3 | 63.15 ± 9.06 |
| pting | input-lanjian | 333.1 ± 15.0 | 321.2 | 371.5 | 78.22 ± 11.73 |
| mattcl-py | input-lanjian | 334.2 ± 4.8 | 328.4 | 345.2 | 78.49 ± 11.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|