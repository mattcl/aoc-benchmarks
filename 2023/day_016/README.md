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
| mattcl | input-pting | 4.3 ± 0.4 | 3.5 | 6.9 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.5 | 4.7 | 7.8 | 1.21 ± 0.17 |
| mattcl | input-mattcl | 5.4 ± 0.5 | 4.8 | 8.2 | 1.25 ± 0.17 |
| mattcl | input-lanjian | 6.4 ± 0.6 | 5.8 | 8.9 | 1.49 ± 0.19 |
| lanjian | input-pting | 32.0 ± 1.0 | 31.0 | 35.2 | 7.49 ± 0.76 |
| lanjian | input-kcen | 39.6 ± 1.0 | 38.2 | 42.8 | 9.25 ± 0.92 |
| lanjian | input-mattcl | 42.6 ± 2.0 | 41.1 | 56.1 | 9.98 ± 1.07 |
| lanjian | input-lanjian | 50.8 ± 0.9 | 49.3 | 53.5 | 11.89 ± 1.17 |
| pting | input-pting | 200.6 ± 2.5 | 197.2 | 206.1 | 46.92 ± 4.56 |
| mattcl-py | input-pting | 203.1 ± 2.5 | 199.0 | 209.0 | 47.51 ± 4.62 |
| pting | input-kcen | 255.9 ± 7.3 | 245.0 | 264.3 | 59.86 ± 6.02 |
| pting | input-mattcl | 257.0 ± 5.1 | 250.2 | 264.7 | 60.13 ± 5.92 |
| mattcl-py | input-kcen | 263.5 ± 7.1 | 257.8 | 279.7 | 61.64 ± 6.17 |
| mattcl-py | input-mattcl | 266.4 ± 3.4 | 261.9 | 273.3 | 62.32 ± 6.07 |
| pting | input-lanjian | 321.5 ± 5.3 | 312.2 | 327.4 | 75.21 ± 7.36 |
| mattcl-py | input-lanjian | 329.7 ± 3.2 | 326.8 | 337.3 | 77.14 ± 7.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|