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
| mattcl | input-lanjian | 0.011 ± 0.000 | 0.010 | 0.012 | 1.00 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.009 | 0.013 | 1.01 ± 0.06 |
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl-py | input-pting | 0.296 ± 0.004 | 0.291 | 0.300 | 27.83 ± 1.15 |
| mattcl-py | input-mattcl | 0.298 ± 0.003 | 0.292 | 0.303 | 28.03 ± 1.14 |
| mattcl-py | input-lanjian | 0.300 ± 0.004 | 0.294 | 0.305 | 28.19 ± 1.16 |
| mattcl-py | input-kcen | 0.303 ± 0.002 | 0.301 | 0.307 | 28.48 ± 1.14 |
| pting | input-lanjian | 1.895 ± 0.021 | 1.872 | 1.912 | 177.94 ± 7.28 |
| pting | input-kcen | 1.904 ± 0.004 | 1.901 | 1.908 | 178.74 ± 7.05 |
| pting | input-pting | 1.907 ± 0.012 | 1.895 | 1.919 | 179.10 ± 7.14 |
| pting | input-mattcl | 1.941 ± 0.088 | 1.870 | 2.039 | 182.23 ± 10.96 |
| lanjian | input-mattcl | 2.375 ± 0.023 | 2.359 | 2.401 | 222.96 ± 9.04 |
| lanjian | input-lanjian | 2.407 ± 0.024 | 2.379 | 2.421 | 226.02 ± 9.19 |
| lanjian | input-pting | 2.436 ± 0.023 | 2.417 | 2.461 | 228.69 ± 9.26 |
| lanjian | input-kcen | 2.438 ± 0.020 | 2.424 | 2.461 | 228.95 ± 9.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|