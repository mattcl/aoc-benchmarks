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
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.009 | 0.012 | 1.00 |
| mattcl | input-lanjian | 0.011 ± 0.000 | 0.010 | 0.012 | 1.00 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.009 | 0.012 | 1.01 ± 0.05 |
| mattcl | input-pting | 0.011 ± 0.002 | 0.009 | 0.041 | 1.01 ± 0.21 |
| mattcl-py | input-pting | 0.299 ± 0.004 | 0.295 | 0.307 | 28.25 ± 1.14 |
| mattcl-py | input-lanjian | 0.300 ± 0.003 | 0.295 | 0.305 | 28.33 ± 1.12 |
| mattcl-py | input-mattcl | 0.301 ± 0.002 | 0.299 | 0.305 | 28.47 ± 1.10 |
| mattcl-py | input-kcen | 0.303 ± 0.003 | 0.299 | 0.307 | 28.63 ± 1.13 |
| pting | input-pting | 1.884 ± 0.035 | 1.845 | 1.913 | 177.94 ± 7.58 |
| pting | input-mattcl | 1.890 ± 0.004 | 1.887 | 1.894 | 178.49 ± 6.86 |
| pting | input-lanjian | 1.892 ± 0.028 | 1.864 | 1.921 | 178.74 ± 7.36 |
| pting | input-kcen | 1.923 ± 0.011 | 1.911 | 1.934 | 181.60 ± 7.05 |
| lanjian | input-lanjian | 2.395 ± 0.029 | 2.361 | 2.417 | 226.19 ± 9.12 |
| lanjian | input-pting | 2.399 ± 0.042 | 2.360 | 2.443 | 226.58 ± 9.55 |
| lanjian | input-kcen | 2.404 ± 0.028 | 2.375 | 2.430 | 227.09 ± 9.10 |
| lanjian | input-mattcl | 2.410 ± 0.042 | 2.383 | 2.458 | 227.63 ± 9.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|