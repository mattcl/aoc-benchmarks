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
| mattcl | input-pting | 4.3 ± 0.6 | 3.2 | 10.4 | 1.00 |
| mattcl | input-mattcl | 5.3 ± 0.5 | 4.8 | 8.0 | 1.24 ± 0.22 |
| mattcl | input-kcen | 5.4 ± 0.7 | 4.7 | 9.3 | 1.26 ± 0.25 |
| mattcl | input-lanjian | 6.3 ± 0.7 | 5.7 | 10.8 | 1.48 ± 0.27 |
| lanjian | input-pting | 33.0 ± 1.2 | 31.3 | 36.4 | 7.73 ± 1.20 |
| lanjian | input-kcen | 40.6 ± 1.1 | 39.1 | 43.6 | 9.50 ± 1.46 |
| lanjian | input-mattcl | 43.5 ± 0.9 | 42.2 | 46.2 | 10.18 ± 1.55 |
| lanjian | input-lanjian | 52.3 ± 1.1 | 50.8 | 54.7 | 12.24 ± 1.87 |
| pting | input-pting | 200.2 ± 3.7 | 193.3 | 206.0 | 46.84 ± 7.14 |
| mattcl-py | input-pting | 203.2 ± 2.4 | 200.0 | 207.8 | 47.55 ± 7.21 |
| pting | input-kcen | 250.5 ± 6.6 | 245.1 | 262.3 | 58.62 ± 9.00 |
| pting | input-mattcl | 255.9 ± 5.8 | 246.5 | 264.0 | 59.87 ± 9.15 |
| mattcl-py | input-mattcl | 263.3 ± 3.5 | 257.8 | 267.9 | 61.61 ± 9.35 |
| mattcl-py | input-kcen | 263.5 ± 6.2 | 253.9 | 273.6 | 61.65 ± 9.44 |
| pting | input-lanjian | 321.0 ± 3.5 | 315.3 | 325.6 | 75.11 ± 11.39 |
| mattcl-py | input-lanjian | 328.6 ± 6.3 | 319.9 | 339.0 | 76.89 ± 11.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|