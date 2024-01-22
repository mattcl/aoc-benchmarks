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
| mattcl | input-pting | 4.3 ± 0.5 | 3.8 | 7.0 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.7 | 4.3 | 10.3 | 1.21 ± 0.23 |
| mattcl | input-mattcl | 5.3 ± 0.5 | 4.8 | 8.8 | 1.23 ± 0.19 |
| mattcl | input-lanjian | 6.2 ± 0.5 | 5.8 | 9.0 | 1.46 ± 0.21 |
| lanjian | input-pting | 34.2 ± 2.3 | 31.8 | 40.8 | 7.99 ± 1.12 |
| lanjian | input-kcen | 41.2 ± 1.5 | 39.2 | 47.2 | 9.63 ± 1.23 |
| lanjian | input-mattcl | 45.4 ± 2.3 | 43.0 | 51.5 | 10.60 ± 1.40 |
| lanjian | input-lanjian | 53.9 ± 2.1 | 51.2 | 59.8 | 12.60 ± 1.62 |
| pting | input-pting | 203.0 ± 2.6 | 199.4 | 207.9 | 47.41 ± 5.85 |
| mattcl-py | input-pting | 205.9 ± 1.4 | 203.4 | 208.0 | 48.08 ± 5.91 |
| pting | input-kcen | 254.8 ± 5.9 | 250.1 | 268.9 | 59.50 ± 7.44 |
| mattcl-py | input-kcen | 262.4 ± 5.5 | 256.6 | 276.1 | 61.27 ± 7.63 |
| pting | input-mattcl | 263.2 ± 4.2 | 255.1 | 269.9 | 61.45 ± 7.61 |
| mattcl-py | input-mattcl | 270.3 ± 3.0 | 266.0 | 275.6 | 63.11 ± 7.78 |
| pting | input-lanjian | 326.5 ± 4.9 | 315.9 | 333.5 | 76.25 ± 9.44 |
| mattcl-py | input-lanjian | 334.1 ± 3.1 | 328.5 | 338.1 | 78.02 ± 9.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|