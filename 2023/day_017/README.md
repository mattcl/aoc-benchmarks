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
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.001 | 0.009 | 0.015 | 1.01 ± 0.06 |
| mattcl-py | input-pting | 0.296 ± 0.004 | 0.291 | 0.303 | 27.82 ± 1.07 |
| mattcl-py | input-mattcl | 0.299 ± 0.004 | 0.295 | 0.306 | 28.06 ± 1.06 |
| mattcl-py | input-kcen | 0.304 ± 0.002 | 0.300 | 0.307 | 28.52 ± 1.04 |
| mattcl-py | input-lanjian | 0.305 ± 0.006 | 0.297 | 0.320 | 28.59 ± 1.18 |
| pting | input-mattcl | 1.869 ± 0.018 | 1.848 | 1.880 | 175.39 ± 6.50 |
| pting | input-lanjian | 1.876 ± 0.016 | 1.864 | 1.893 | 176.02 ± 6.46 |
| pting | input-kcen | 1.896 ± 0.021 | 1.872 | 1.910 | 177.89 ± 6.65 |
| pting | input-pting | 1.934 ± 0.074 | 1.870 | 2.014 | 181.47 ± 9.47 |
| lanjian | input-mattcl | 2.378 ± 0.025 | 2.349 | 2.394 | 223.12 ± 8.30 |
| lanjian | input-pting | 2.384 ± 0.024 | 2.357 | 2.400 | 223.68 ± 8.30 |
| lanjian | input-lanjian | 2.401 ± 0.032 | 2.370 | 2.435 | 225.33 ± 8.61 |
| lanjian | input-kcen | 2.423 ± 0.003 | 2.420 | 2.426 | 227.39 ± 8.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|