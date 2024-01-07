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
| mattcl | input-kcen | 0.011 ± 0.003 | 0.009 | 0.058 | 1.04 ± 0.32 |
| mattcl-py | input-pting | 0.294 ± 0.002 | 0.291 | 0.296 | 27.97 ± 0.94 |
| mattcl-py | input-mattcl | 0.298 ± 0.005 | 0.292 | 0.310 | 28.33 ± 1.07 |
| mattcl-py | input-lanjian | 0.299 ± 0.003 | 0.296 | 0.303 | 28.47 ± 0.98 |
| mattcl-py | input-kcen | 0.307 ± 0.010 | 0.300 | 0.333 | 29.18 ± 1.38 |
| pting | input-mattcl | 1.878 ± 0.014 | 1.862 | 1.889 | 178.73 ± 6.07 |
| pting | input-lanjian | 1.895 ± 0.027 | 1.877 | 1.926 | 180.33 ± 6.50 |
| pting | input-kcen | 1.897 ± 0.042 | 1.852 | 1.936 | 180.53 ± 7.20 |
| pting | input-pting | 1.910 ± 0.021 | 1.896 | 1.935 | 181.81 ± 6.36 |
| lanjian | input-mattcl | 2.352 ± 0.004 | 2.349 | 2.357 | 223.89 ± 7.44 |
| lanjian | input-pting | 2.359 ± 0.010 | 2.353 | 2.370 | 224.52 ± 7.50 |
| lanjian | input-lanjian | 2.375 ± 0.011 | 2.366 | 2.387 | 226.07 ± 7.56 |
| lanjian | input-kcen | 2.401 ± 0.005 | 2.396 | 2.406 | 228.55 ± 7.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|