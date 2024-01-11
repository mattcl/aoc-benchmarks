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
| mattcl | input-pting | 4.3 ± 0.4 | 3.4 | 7.5 | 1.00 |
| mattcl | input-kcen | 5.1 ± 0.3 | 4.7 | 8.0 | 1.20 ± 0.14 |
| mattcl | input-mattcl | 5.3 ± 0.4 | 4.9 | 10.1 | 1.23 ± 0.16 |
| mattcl | input-lanjian | 6.3 ± 0.6 | 5.8 | 11.0 | 1.48 ± 0.20 |
| lanjian | input-pting | 32.6 ± 0.8 | 31.1 | 35.5 | 7.63 ± 0.77 |
| lanjian | input-kcen | 40.7 ± 1.1 | 38.7 | 43.9 | 9.54 ± 0.97 |
| lanjian | input-mattcl | 43.6 ± 0.9 | 42.3 | 46.9 | 10.22 ± 1.03 |
| lanjian | input-lanjian | 52.7 ± 0.9 | 50.8 | 55.1 | 12.34 ± 1.23 |
| pting | input-pting | 201.6 ± 2.3 | 199.4 | 207.0 | 47.24 ± 4.67 |
| mattcl-py | input-pting | 204.8 ± 3.0 | 199.8 | 210.2 | 47.99 ± 4.76 |
| pting | input-kcen | 251.2 ± 3.1 | 247.1 | 259.2 | 58.86 ± 5.82 |
| pting | input-mattcl | 262.8 ± 4.7 | 254.0 | 269.0 | 61.59 ± 6.14 |
| mattcl-py | input-kcen | 264.0 ± 12.2 | 255.6 | 298.7 | 61.87 ± 6.71 |
| mattcl-py | input-mattcl | 267.0 ± 2.8 | 261.3 | 269.8 | 62.57 ± 6.17 |
| pting | input-lanjian | 326.3 ± 3.0 | 321.9 | 332.1 | 76.45 ± 7.54 |
| mattcl-py | input-lanjian | 331.7 ± 3.3 | 327.2 | 337.8 | 77.71 ± 7.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|