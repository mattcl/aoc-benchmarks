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
| mattcl | input-pting | 0.011 ± 0.000 | 0.009 | 0.012 | 1.00 |
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl | input-lanjian | 0.011 ± 0.003 | 0.009 | 0.054 | 1.02 ± 0.30 |
| mattcl-py | input-pting | 0.299 ± 0.002 | 0.296 | 0.303 | 28.26 ± 1.03 |
| mattcl-py | input-lanjian | 0.301 ± 0.004 | 0.295 | 0.306 | 28.45 ± 1.08 |
| mattcl-py | input-mattcl | 0.301 ± 0.002 | 0.299 | 0.306 | 28.51 ± 1.03 |
| mattcl-py | input-kcen | 0.305 ± 0.003 | 0.299 | 0.308 | 28.83 ± 1.07 |
| pting | input-mattcl | 1.864 ± 0.023 | 1.838 | 1.882 | 176.45 ± 6.66 |
| pting | input-lanjian | 1.892 ± 0.038 | 1.849 | 1.919 | 179.11 ± 7.33 |
| pting | input-kcen | 1.899 ± 0.020 | 1.885 | 1.922 | 179.72 ± 6.69 |
| pting | input-pting | 1.954 ± 0.019 | 1.932 | 1.970 | 184.90 ± 6.85 |
| lanjian | input-pting | 2.380 ± 0.025 | 2.357 | 2.406 | 225.24 ± 8.37 |
| lanjian | input-mattcl | 2.392 ± 0.019 | 2.374 | 2.412 | 226.36 ± 8.27 |
| lanjian | input-kcen | 2.410 ± 0.021 | 2.386 | 2.425 | 228.12 ± 8.39 |
| lanjian | input-lanjian | 2.419 ± 0.001 | 2.418 | 2.420 | 228.97 ± 8.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|