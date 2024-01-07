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
| mattcl | input-pting | 4.6 ± 0.7 | 3.7 | 11.7 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.3 | 4.8 | 7.5 | 1.15 ± 0.20 |
| mattcl | input-mattcl | 5.4 ± 0.4 | 5.0 | 8.4 | 1.19 ± 0.22 |
| mattcl | input-lanjian | 6.5 ± 0.6 | 5.9 | 10.7 | 1.42 ± 0.27 |
| lanjian | input-pting | 32.7 ± 0.9 | 31.6 | 35.9 | 7.18 ± 1.19 |
| lanjian | input-kcen | 40.6 ± 0.9 | 39.1 | 43.4 | 8.92 ± 1.47 |
| lanjian | input-mattcl | 45.0 ± 6.0 | 42.4 | 81.6 | 9.88 ± 2.09 |
| lanjian | input-lanjian | 52.6 ± 1.0 | 51.2 | 54.8 | 11.56 ± 1.90 |
| pting | input-pting | 201.3 ± 2.6 | 198.6 | 208.1 | 44.23 ± 7.25 |
| mattcl-py | input-pting | 204.6 ± 2.2 | 201.2 | 208.9 | 44.94 ± 7.36 |
| pting | input-kcen | 253.8 ± 5.9 | 245.1 | 263.8 | 55.75 ± 9.20 |
| pting | input-mattcl | 259.6 ± 5.9 | 249.8 | 268.5 | 57.03 ± 9.41 |
| mattcl-py | input-kcen | 264.6 ± 7.2 | 255.3 | 279.6 | 58.13 ± 9.63 |
| mattcl-py | input-mattcl | 268.1 ± 3.2 | 260.6 | 272.4 | 58.90 ± 9.65 |
| pting | input-lanjian | 324.7 ± 4.0 | 315.6 | 328.6 | 71.32 ± 11.68 |
| mattcl-py | input-lanjian | 331.6 ± 3.6 | 325.6 | 336.5 | 72.84 ± 11.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|