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
| mattcl | input-pting | 4.2 ± 0.4 | 3.2 | 6.1 | 1.00 |
| mattcl | input-kcen | 5.1 ± 0.5 | 4.7 | 8.0 | 1.21 ± 0.16 |
| mattcl | input-mattcl | 5.3 ± 0.5 | 4.7 | 7.4 | 1.26 ± 0.16 |
| mattcl | input-lanjian | 6.3 ± 0.5 | 5.8 | 8.8 | 1.49 ± 0.19 |
| lanjian | input-pting | 32.8 ± 0.8 | 31.6 | 36.0 | 7.75 ± 0.76 |
| lanjian | input-kcen | 40.2 ± 1.1 | 38.9 | 43.6 | 9.51 ± 0.94 |
| lanjian | input-mattcl | 44.9 ± 6.7 | 42.4 | 96.3 | 10.61 ± 1.87 |
| lanjian | input-lanjian | 52.6 ± 1.1 | 50.9 | 56.6 | 12.43 ± 1.21 |
| pting | input-pting | 202.7 ± 2.9 | 198.1 | 206.9 | 47.88 ± 4.61 |
| mattcl-py | input-pting | 205.8 ± 3.2 | 201.9 | 212.2 | 48.62 ± 4.69 |
| pting | input-kcen | 252.0 ± 4.7 | 245.8 | 260.7 | 59.54 ± 5.77 |
| pting | input-mattcl | 261.3 ± 4.2 | 255.1 | 268.3 | 61.75 ± 5.96 |
| mattcl-py | input-kcen | 263.7 ± 4.9 | 258.4 | 273.2 | 62.30 ± 6.04 |
| mattcl-py | input-mattcl | 273.5 ± 10.4 | 259.5 | 300.7 | 64.62 ± 6.62 |
| pting | input-lanjian | 326.0 ± 5.9 | 317.8 | 335.4 | 77.03 ± 7.46 |
| mattcl-py | input-lanjian | 330.8 ± 2.0 | 327.1 | 332.9 | 78.16 ± 7.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|