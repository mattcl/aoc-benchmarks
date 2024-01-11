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
| mattcl | input-lanjian | 0.011 ± 0.000 | 0.010 | 0.013 | 1.00 ± 0.05 |
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.010 | 0.013 | 1.01 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.009 | 0.012 | 1.01 ± 0.05 |
| mattcl-py | input-pting | 0.299 ± 0.005 | 0.291 | 0.309 | 28.10 ± 1.03 |
| mattcl-py | input-mattcl | 0.300 ± 0.004 | 0.295 | 0.309 | 28.26 ± 1.01 |
| mattcl-py | input-kcen | 0.302 ± 0.004 | 0.294 | 0.310 | 28.38 ± 1.00 |
| mattcl-py | input-lanjian | 0.303 ± 0.008 | 0.296 | 0.323 | 28.49 ± 1.20 |
| pting | input-kcen | 1.862 ± 0.004 | 1.857 | 1.865 | 175.14 ± 5.78 |
| pting | input-mattcl | 1.882 ± 0.022 | 1.860 | 1.905 | 177.00 ± 6.19 |
| pting | input-lanjian | 1.886 ± 0.012 | 1.872 | 1.894 | 177.43 ± 5.95 |
| pting | input-pting | 1.907 ± 0.050 | 1.856 | 1.955 | 179.42 ± 7.54 |
| lanjian | input-pting | 2.383 ± 0.029 | 2.350 | 2.405 | 224.15 ± 7.86 |
| lanjian | input-mattcl | 2.394 ± 0.009 | 2.383 | 2.402 | 225.15 ± 7.46 |
| lanjian | input-lanjian | 2.407 ± 0.003 | 2.405 | 2.411 | 226.44 ± 7.46 |
| lanjian | input-kcen | 2.422 ± 0.010 | 2.410 | 2.430 | 227.86 ± 7.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|