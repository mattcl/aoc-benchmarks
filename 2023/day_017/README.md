# Day 17 benchmarks

[link to problem](https://adventofcode.com/2023/day/17)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 17)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [s] | Min [s] | Max [s] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 0.011 ± 0.000 | 0.010 | 0.013 | 1.00 |
| mattcl | input-lanjian | 0.011 ± 0.000 | 0.010 | 0.012 | 1.00 ± 0.05 |
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.010 | 0.013 | 1.01 ± 0.06 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.06 |
| mattcl-py | input-pting | 0.298 ± 0.003 | 0.295 | 0.302 | 27.97 ± 1.11 |
| mattcl-py | input-lanjian | 0.301 ± 0.002 | 0.296 | 0.303 | 28.21 ± 1.11 |
| mattcl-py | input-mattcl | 0.302 ± 0.004 | 0.296 | 0.309 | 28.33 ± 1.16 |
| mattcl-py | input-kcen | 0.303 ± 0.002 | 0.300 | 0.306 | 28.44 ± 1.12 |
| pting | input-mattcl | 1.879 ± 0.034 | 1.844 | 1.912 | 176.40 ± 7.55 |
| pting | input-lanjian | 1.909 ± 0.028 | 1.876 | 1.929 | 179.19 ± 7.42 |
| pting | input-pting | 1.920 ± 0.018 | 1.899 | 1.934 | 180.25 ± 7.18 |
| pting | input-kcen | 1.931 ± 0.012 | 1.918 | 1.939 | 181.27 ± 7.10 |
| lanjian | input-mattcl | 2.372 ± 0.022 | 2.357 | 2.398 | 222.68 ± 8.87 |
| lanjian | input-pting | 2.374 ± 0.025 | 2.356 | 2.402 | 222.83 ± 8.92 |
| lanjian | input-lanjian | 2.425 ± 0.004 | 2.423 | 2.429 | 227.67 ± 8.81 |
| lanjian | input-kcen | 2.454 ± 0.037 | 2.427 | 2.496 | 230.35 ± 9.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|