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
| mattcl | input-lanjian | 0.011 ± 0.000 | 0.009 | 0.013 | 1.00 |
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.010 | 0.012 | 1.00 ± 0.06 |
| mattcl | input-pting | 0.011 ± 0.000 | 0.010 | 0.013 | 1.00 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.009 | 0.013 | 1.01 ± 0.06 |
| mattcl-py | input-pting | 0.295 ± 0.003 | 0.290 | 0.300 | 27.54 ± 1.16 |
| mattcl-py | input-lanjian | 0.299 ± 0.004 | 0.295 | 0.306 | 27.94 ± 1.19 |
| mattcl-py | input-mattcl | 0.301 ± 0.003 | 0.295 | 0.305 | 28.08 ± 1.18 |
| mattcl-py | input-kcen | 0.302 ± 0.003 | 0.296 | 0.306 | 28.17 ± 1.19 |
| pting | input-mattcl | 1.886 ± 0.043 | 1.845 | 1.931 | 176.09 ± 8.24 |
| pting | input-kcen | 1.888 ± 0.023 | 1.863 | 1.909 | 176.26 ± 7.51 |
| pting | input-lanjian | 1.906 ± 0.017 | 1.888 | 1.921 | 177.97 ± 7.42 |
| pting | input-pting | 1.929 ± 0.014 | 1.913 | 1.940 | 180.05 ± 7.45 |
| lanjian | input-mattcl | 2.391 ± 0.036 | 2.351 | 2.421 | 223.21 ± 9.69 |
| lanjian | input-lanjian | 2.405 ± 0.029 | 2.372 | 2.423 | 224.51 ± 9.53 |
| lanjian | input-kcen | 2.409 ± 0.029 | 2.376 | 2.431 | 224.91 ± 9.56 |
| lanjian | input-pting | 2.412 ± 0.009 | 2.404 | 2.421 | 225.16 ± 9.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|