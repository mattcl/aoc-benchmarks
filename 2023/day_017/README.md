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
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.010 | 0.012 | 1.00 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.013 | 1.01 ± 0.05 |
| mattcl-py | input-pting | 0.298 ± 0.003 | 0.290 | 0.302 | 27.96 ± 1.12 |
| mattcl-py | input-lanjian | 0.301 ± 0.004 | 0.296 | 0.308 | 28.22 ± 1.14 |
| mattcl-py | input-kcen | 0.303 ± 0.005 | 0.297 | 0.313 | 28.43 ± 1.18 |
| mattcl-py | input-mattcl | 0.304 ± 0.005 | 0.295 | 0.311 | 28.49 ± 1.19 |
| pting | input-mattcl | 1.875 ± 0.018 | 1.856 | 1.891 | 175.71 ± 6.96 |
| pting | input-kcen | 1.875 ± 0.032 | 1.842 | 1.904 | 175.74 ± 7.38 |
| pting | input-lanjian | 1.901 ± 0.024 | 1.875 | 1.921 | 178.21 ± 7.20 |
| pting | input-pting | 1.904 ± 0.039 | 1.860 | 1.935 | 178.48 ± 7.78 |
| lanjian | input-lanjian | 2.400 ± 0.022 | 2.375 | 2.415 | 224.96 ± 8.89 |
| lanjian | input-mattcl | 2.402 ± 0.038 | 2.367 | 2.441 | 225.09 ± 9.35 |
| lanjian | input-pting | 2.410 ± 0.007 | 2.402 | 2.417 | 225.87 ± 8.71 |
| lanjian | input-kcen | 2.416 ± 0.032 | 2.381 | 2.443 | 226.42 ± 9.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|