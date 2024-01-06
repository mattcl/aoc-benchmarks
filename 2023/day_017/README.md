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
| mattcl | input-lanjian | 0.011 ± 0.000 | 0.010 | 0.012 | 1.00 ± 0.06 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.013 | 1.00 ± 0.06 |
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.010 | 0.013 | 1.01 ± 0.06 |
| mattcl-py | input-mattcl | 0.301 ± 0.003 | 0.295 | 0.305 | 28.25 ± 1.25 |
| mattcl-py | input-lanjian | 0.301 ± 0.003 | 0.295 | 0.306 | 28.27 ± 1.26 |
| mattcl-py | input-kcen | 0.302 ± 0.004 | 0.297 | 0.309 | 28.39 ± 1.27 |
| mattcl-py | input-pting | 0.307 ± 0.006 | 0.299 | 0.322 | 28.86 ± 1.37 |
| pting | input-kcen | 1.888 ± 0.016 | 1.869 | 1.899 | 177.28 ± 7.76 |
| pting | input-lanjian | 1.905 ± 0.011 | 1.892 | 1.911 | 178.87 ± 7.74 |
| pting | input-mattcl | 1.920 ± 0.056 | 1.874 | 1.982 | 180.28 ± 9.34 |
| pting | input-pting | 2.018 ± 0.047 | 1.987 | 2.072 | 189.52 ± 9.24 |
| lanjian | input-lanjian | 2.366 ± 0.005 | 2.361 | 2.370 | 222.23 ± 9.55 |
| lanjian | input-mattcl | 2.385 ± 0.032 | 2.354 | 2.418 | 223.99 ± 10.08 |
| lanjian | input-kcen | 2.422 ± 0.006 | 2.417 | 2.429 | 227.43 ± 9.78 |
| lanjian | input-pting | 2.521 ± 0.060 | 2.482 | 2.590 | 236.76 ± 11.60 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|