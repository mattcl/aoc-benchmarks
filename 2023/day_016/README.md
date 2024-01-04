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
| mattcl | input-pting | 4.2 ± 0.4 | 3.8 | 6.6 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.5 | 4.7 | 7.9 | 1.22 ± 0.17 |
| mattcl | input-lanjian | 6.3 ± 0.5 | 5.8 | 9.8 | 1.49 ± 0.19 |
| mattcl | input-mattcl | 6.4 ± 5.4 | 4.9 | 57.4 | 1.51 ± 1.29 |
| lanjian | input-pting | 33.8 ± 1.7 | 32.4 | 47.8 | 7.96 ± 0.84 |
| lanjian | input-kcen | 41.9 ± 0.9 | 40.4 | 44.8 | 9.87 ± 0.93 |
| lanjian | input-mattcl | 45.0 ± 1.4 | 42.9 | 53.0 | 10.60 ± 1.03 |
| lanjian | input-lanjian | 54.3 ± 0.9 | 52.5 | 56.7 | 12.78 ± 1.19 |
| pting | input-pting | 202.6 ± 2.8 | 199.5 | 208.1 | 47.68 ± 4.43 |
| mattcl-py | input-pting | 206.6 ± 3.3 | 200.6 | 211.1 | 48.64 ± 4.53 |
| pting | input-kcen | 254.3 ± 6.0 | 247.4 | 265.7 | 59.85 ± 5.68 |
| pting | input-mattcl | 264.5 ± 4.9 | 255.6 | 270.5 | 62.25 ± 5.83 |
| mattcl-py | input-kcen | 266.3 ± 4.5 | 260.5 | 273.1 | 62.67 ± 5.85 |
| mattcl-py | input-mattcl | 268.9 ± 4.2 | 260.6 | 274.0 | 63.30 ± 5.90 |
| pting | input-lanjian | 327.5 ± 4.3 | 321.8 | 336.6 | 77.08 ± 7.15 |
| mattcl-py | input-lanjian | 336.1 ± 5.9 | 328.9 | 345.5 | 79.10 ± 7.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|