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
| mattcl | input-lanjian | 0.011 ± 0.000 | 0.010 | 0.013 | 1.00 ± 0.05 |
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.010 | 0.013 | 1.01 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl-py | input-pting | 0.297 ± 0.005 | 0.292 | 0.309 | 27.91 ± 1.10 |
| mattcl-py | input-mattcl | 0.300 ± 0.003 | 0.295 | 0.305 | 28.22 ± 1.05 |
| mattcl-py | input-lanjian | 0.301 ± 0.005 | 0.298 | 0.315 | 28.33 ± 1.13 |
| mattcl-py | input-kcen | 0.304 ± 0.005 | 0.298 | 0.314 | 28.60 ± 1.11 |
| pting | input-kcen | 1.867 ± 0.003 | 1.864 | 1.869 | 175.58 ± 6.28 |
| pting | input-lanjian | 1.874 ± 0.029 | 1.856 | 1.908 | 176.24 ± 6.87 |
| pting | input-mattcl | 1.888 ± 0.004 | 1.885 | 1.893 | 177.56 ± 6.36 |
| pting | input-pting | 1.902 ± 0.029 | 1.883 | 1.936 | 178.88 ± 6.96 |
| lanjian | input-pting | 2.369 ± 0.022 | 2.352 | 2.394 | 222.80 ± 8.21 |
| lanjian | input-mattcl | 2.381 ± 0.027 | 2.351 | 2.404 | 223.88 ± 8.40 |
| lanjian | input-lanjian | 2.386 ± 0.025 | 2.367 | 2.413 | 224.33 ± 8.34 |
| lanjian | input-kcen | 2.408 ± 0.028 | 2.378 | 2.433 | 226.47 ± 8.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|