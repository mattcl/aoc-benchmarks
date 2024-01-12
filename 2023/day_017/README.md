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
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.009 | 0.011 | 1.00 |
| mattcl | input-pting | 0.011 ± 0.000 | 0.009 | 0.012 | 1.00 ± 0.05 |
| mattcl | input-lanjian | 0.011 ± 0.000 | 0.010 | 0.013 | 1.00 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl-py | input-mattcl | 0.298 ± 0.002 | 0.294 | 0.301 | 28.17 ± 1.00 |
| mattcl-py | input-pting | 0.300 ± 0.002 | 0.297 | 0.302 | 28.34 ± 1.00 |
| mattcl-py | input-lanjian | 0.302 ± 0.007 | 0.298 | 0.319 | 28.62 ± 1.17 |
| mattcl-py | input-kcen | 0.305 ± 0.005 | 0.297 | 0.315 | 28.86 ± 1.10 |
| pting | input-lanjian | 1.866 ± 0.033 | 1.844 | 1.904 | 176.49 ± 6.91 |
| pting | input-mattcl | 1.885 ± 0.027 | 1.867 | 1.916 | 178.30 ± 6.71 |
| pting | input-kcen | 1.891 ± 0.031 | 1.857 | 1.917 | 178.93 ± 6.87 |
| pting | input-pting | 1.903 ± 0.029 | 1.877 | 1.934 | 180.00 ± 6.83 |
| lanjian | input-pting | 2.411 ± 0.004 | 2.407 | 2.415 | 228.08 ± 7.95 |
| lanjian | input-kcen | 2.414 ± 0.023 | 2.388 | 2.430 | 228.33 ± 8.23 |
| lanjian | input-mattcl | 2.416 ± 0.011 | 2.405 | 2.427 | 228.55 ± 8.03 |
| lanjian | input-lanjian | 2.421 ± 0.005 | 2.417 | 2.426 | 229.01 ± 7.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|