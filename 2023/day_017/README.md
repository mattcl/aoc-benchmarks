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
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl-py | input-pting | 0.296 ± 0.004 | 0.289 | 0.303 | 27.77 ± 1.08 |
| mattcl-py | input-mattcl | 0.297 ± 0.004 | 0.293 | 0.305 | 27.84 ± 1.07 |
| mattcl-py | input-lanjian | 0.301 ± 0.003 | 0.295 | 0.305 | 28.16 ± 1.05 |
| mattcl-py | input-kcen | 0.303 ± 0.003 | 0.300 | 0.310 | 28.42 ± 1.06 |
| pting | input-mattcl | 1.869 ± 0.030 | 1.835 | 1.887 | 175.07 ± 6.89 |
| pting | input-kcen | 1.905 ± 0.017 | 1.887 | 1.920 | 178.44 ± 6.60 |
| pting | input-pting | 1.910 ± 0.020 | 1.891 | 1.931 | 178.84 ± 6.70 |
| pting | input-lanjian | 1.921 ± 0.052 | 1.871 | 1.975 | 179.92 ± 8.08 |
| lanjian | input-mattcl | 2.369 ± 0.028 | 2.338 | 2.392 | 221.89 ± 8.38 |
| lanjian | input-pting | 2.382 ± 0.035 | 2.344 | 2.412 | 223.12 ± 8.66 |
| lanjian | input-lanjian | 2.405 ± 0.008 | 2.400 | 2.415 | 225.27 ± 8.13 |
| lanjian | input-kcen | 2.416 ± 0.005 | 2.410 | 2.421 | 226.24 ± 8.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|