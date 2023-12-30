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
| mattcl | input-pting | 4.3 ± 0.4 | 3.8 | 6.5 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.5 | 4.7 | 9.2 | 1.20 ± 0.17 |
| mattcl | input-mattcl | 5.4 ± 0.4 | 4.9 | 7.8 | 1.24 ± 0.16 |
| mattcl | input-lanjian | 6.4 ± 0.6 | 5.9 | 10.1 | 1.47 ± 0.19 |
| lanjian | input-pting | 33.2 ± 2.3 | 31.9 | 53.2 | 7.65 ± 0.92 |
| lanjian | input-kcen | 41.2 ± 1.2 | 39.2 | 44.0 | 9.49 ± 0.98 |
| lanjian | input-mattcl | 44.4 ± 1.1 | 43.0 | 47.5 | 10.24 ± 1.04 |
| lanjian | input-lanjian | 52.7 ± 0.9 | 51.4 | 55.2 | 12.16 ± 1.22 |
| pting | input-pting | 201.7 ± 1.8 | 198.4 | 205.2 | 46.52 ± 4.61 |
| mattcl-py | input-pting | 206.2 ± 3.5 | 202.4 | 214.5 | 47.56 ± 4.76 |
| pting | input-kcen | 254.7 ± 5.8 | 248.6 | 266.9 | 58.75 ± 5.95 |
| pting | input-mattcl | 261.5 ± 5.7 | 254.9 | 271.6 | 60.32 ± 6.10 |
| mattcl-py | input-kcen | 263.2 ± 2.8 | 260.1 | 268.0 | 60.71 ± 6.02 |
| mattcl-py | input-mattcl | 270.3 ± 2.1 | 265.9 | 273.3 | 62.34 ± 6.17 |
| pting | input-lanjian | 329.1 ± 3.4 | 321.5 | 332.5 | 75.91 ± 7.53 |
| mattcl-py | input-lanjian | 335.4 ± 4.8 | 329.2 | 345.1 | 77.36 ± 7.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|