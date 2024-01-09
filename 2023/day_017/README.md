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
| mattcl | input-pting | 0.011 ± 0.000 | 0.010 | 0.012 | 1.00 |
| mattcl | input-lanjian | 0.011 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.010 | 0.013 | 1.01 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.013 | 1.01 ± 0.05 |
| mattcl-py | input-pting | 0.296 ± 0.002 | 0.292 | 0.300 | 27.88 ± 0.94 |
| mattcl-py | input-mattcl | 0.302 ± 0.002 | 0.300 | 0.307 | 28.52 ± 0.96 |
| mattcl-py | input-kcen | 0.306 ± 0.003 | 0.302 | 0.311 | 28.81 ± 0.98 |
| mattcl-py | input-lanjian | 0.309 ± 0.013 | 0.302 | 0.342 | 29.10 ± 1.53 |
| pting | input-kcen | 1.893 ± 0.012 | 1.882 | 1.906 | 178.52 ± 5.98 |
| pting | input-mattcl | 1.897 ± 0.044 | 1.853 | 1.942 | 178.82 ± 7.20 |
| pting | input-lanjian | 1.897 ± 0.008 | 1.888 | 1.902 | 178.87 ± 5.93 |
| pting | input-pting | 1.942 ± 0.032 | 1.917 | 1.977 | 183.10 ± 6.72 |
| lanjian | input-pting | 2.376 ± 0.031 | 2.357 | 2.412 | 223.98 ± 7.94 |
| lanjian | input-mattcl | 2.382 ± 0.024 | 2.356 | 2.404 | 224.58 ± 7.73 |
| lanjian | input-lanjian | 2.417 ± 0.006 | 2.411 | 2.423 | 227.89 ± 7.52 |
| lanjian | input-kcen | 2.418 ± 0.029 | 2.385 | 2.440 | 227.94 ± 7.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|