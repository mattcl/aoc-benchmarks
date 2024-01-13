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
| mattcl | input-pting | 4.3 ± 0.4 | 3.8 | 6.7 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.7 | 4.7 | 9.7 | 1.21 ± 0.19 |
| mattcl | input-mattcl | 5.4 ± 0.6 | 4.9 | 8.9 | 1.25 ± 0.18 |
| mattcl | input-lanjian | 6.4 ± 0.5 | 5.8 | 8.6 | 1.47 ± 0.19 |
| lanjian | input-pting | 32.8 ± 0.9 | 31.6 | 35.9 | 7.58 ± 0.76 |
| lanjian | input-kcen | 41.0 ± 0.9 | 39.8 | 43.7 | 9.48 ± 0.94 |
| lanjian | input-mattcl | 43.7 ± 1.0 | 42.3 | 47.2 | 10.09 ± 1.00 |
| lanjian | input-lanjian | 53.1 ± 1.0 | 51.2 | 55.7 | 12.27 ± 1.21 |
| pting | input-pting | 203.8 ± 3.7 | 199.4 | 209.8 | 47.07 ± 4.63 |
| mattcl-py | input-pting | 204.8 ± 1.8 | 202.1 | 208.1 | 47.30 ± 4.59 |
| pting | input-kcen | 254.2 ± 6.3 | 246.4 | 264.2 | 58.71 ± 5.86 |
| pting | input-mattcl | 259.3 ± 5.1 | 249.1 | 267.9 | 59.91 ± 5.91 |
| mattcl-py | input-kcen | 264.0 ± 5.6 | 255.7 | 274.7 | 60.99 ± 6.04 |
| mattcl-py | input-mattcl | 270.2 ± 3.7 | 265.4 | 275.9 | 62.41 ± 6.09 |
| pting | input-lanjian | 326.7 ± 4.4 | 321.0 | 334.3 | 75.46 ± 7.36 |
| mattcl-py | input-lanjian | 334.3 ± 4.9 | 327.4 | 343.9 | 77.22 ± 7.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|