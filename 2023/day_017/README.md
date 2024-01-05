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
| mattcl | input-pting | 0.010 ± 0.000 | 0.010 | 0.013 | 1.00 |
| mattcl | input-mattcl | 0.010 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl | input-lanjian | 0.011 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.009 | 0.013 | 1.02 ± 0.05 |
| mattcl-py | input-pting | 0.296 ± 0.006 | 0.290 | 0.312 | 28.34 ± 1.06 |
| mattcl-py | input-mattcl | 0.298 ± 0.003 | 0.293 | 0.303 | 28.51 ± 0.94 |
| mattcl-py | input-lanjian | 0.300 ± 0.002 | 0.296 | 0.305 | 28.74 ± 0.94 |
| mattcl-py | input-kcen | 0.304 ± 0.002 | 0.299 | 0.307 | 29.09 ± 0.95 |
| pting | input-kcen | 1.874 ± 0.011 | 1.862 | 1.884 | 179.54 ± 5.78 |
| pting | input-pting | 1.878 ± 0.036 | 1.839 | 1.909 | 179.90 ± 6.64 |
| pting | input-mattcl | 1.878 ± 0.033 | 1.858 | 1.916 | 179.90 ± 6.52 |
| pting | input-lanjian | 1.881 ± 0.020 | 1.861 | 1.901 | 180.27 ± 6.01 |
| lanjian | input-pting | 2.365 ± 0.007 | 2.358 | 2.372 | 226.62 ± 7.20 |
| lanjian | input-mattcl | 2.372 ± 0.007 | 2.365 | 2.380 | 227.27 ± 7.22 |
| lanjian | input-lanjian | 2.397 ± 0.005 | 2.392 | 2.401 | 229.67 ± 7.28 |
| lanjian | input-kcen | 2.414 ± 0.003 | 2.411 | 2.416 | 231.27 ± 7.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|