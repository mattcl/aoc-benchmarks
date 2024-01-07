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
| mattcl | input-pting | 0.010 ± 0.000 | 0.010 | 0.011 | 1.00 |
| mattcl | input-mattcl | 0.010 ± 0.000 | 0.010 | 0.013 | 1.01 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl | input-lanjian | 0.011 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl-py | input-pting | 0.295 ± 0.005 | 0.290 | 0.303 | 28.38 ± 1.02 |
| mattcl-py | input-mattcl | 0.299 ± 0.002 | 0.297 | 0.303 | 28.83 ± 0.96 |
| mattcl-py | input-lanjian | 0.300 ± 0.002 | 0.297 | 0.304 | 28.85 ± 0.97 |
| mattcl-py | input-kcen | 0.307 ± 0.007 | 0.302 | 0.323 | 29.55 ± 1.16 |
| pting | input-kcen | 1.904 ± 0.016 | 1.888 | 1.919 | 183.38 ± 6.18 |
| pting | input-mattcl | 1.908 ± 0.027 | 1.877 | 1.926 | 183.77 ± 6.54 |
| pting | input-lanjian | 1.923 ± 0.067 | 1.875 | 2.000 | 185.22 ± 8.88 |
| pting | input-pting | 1.948 ± 0.036 | 1.926 | 1.989 | 187.62 ± 7.02 |
| lanjian | input-mattcl | 2.351 ± 0.013 | 2.339 | 2.364 | 226.47 ± 7.50 |
| lanjian | input-pting | 2.352 ± 0.009 | 2.342 | 2.360 | 226.55 ± 7.45 |
| lanjian | input-kcen | 2.396 ± 0.002 | 2.393 | 2.397 | 230.74 ± 7.54 |
| lanjian | input-lanjian | 2.420 ± 0.048 | 2.379 | 2.473 | 233.06 ± 8.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|