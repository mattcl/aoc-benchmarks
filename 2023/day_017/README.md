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
| mattcl | input-pting | 0.010 ± 0.000 | 0.009 | 0.012 | 1.00 |
| mattcl | input-mattcl | 0.010 ± 0.000 | 0.010 | 0.011 | 1.01 ± 0.05 |
| mattcl | input-lanjian | 0.010 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl-py | input-pting | 0.295 ± 0.003 | 0.292 | 0.302 | 28.37 ± 0.97 |
| mattcl-py | input-mattcl | 0.298 ± 0.003 | 0.295 | 0.304 | 28.61 ± 0.98 |
| mattcl-py | input-lanjian | 0.300 ± 0.002 | 0.297 | 0.303 | 28.78 ± 0.97 |
| mattcl-py | input-kcen | 0.301 ± 0.002 | 0.299 | 0.305 | 28.95 ± 0.97 |
| pting | input-mattcl | 1.859 ± 0.020 | 1.846 | 1.882 | 178.53 ± 6.18 |
| pting | input-kcen | 1.878 ± 0.021 | 1.860 | 1.900 | 180.40 ± 6.25 |
| pting | input-lanjian | 1.892 ± 0.016 | 1.876 | 1.908 | 181.75 ± 6.16 |
| pting | input-pting | 1.902 ± 0.002 | 1.900 | 1.905 | 182.72 ± 6.00 |
| lanjian | input-mattcl | 2.355 ± 0.010 | 2.345 | 2.365 | 226.22 ± 7.49 |
| lanjian | input-pting | 2.364 ± 0.021 | 2.350 | 2.388 | 227.09 ± 7.72 |
| lanjian | input-lanjian | 2.376 ± 0.005 | 2.370 | 2.379 | 228.19 ± 7.51 |
| lanjian | input-kcen | 2.386 ± 0.011 | 2.377 | 2.398 | 229.13 ± 7.60 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|