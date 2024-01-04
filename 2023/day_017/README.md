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
| mattcl | input-lanjian | 0.011 ± 0.000 | 0.010 | 0.013 | 1.00 ± 0.06 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.012 | 1.00 ± 0.06 |
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.010 | 0.013 | 1.00 ± 0.06 |
| mattcl-py | input-pting | 0.382 ± 0.003 | 0.378 | 0.386 | 35.97 ± 1.57 |
| mattcl-py | input-lanjian | 0.385 ± 0.005 | 0.379 | 0.390 | 36.28 ± 1.62 |
| mattcl-py | input-mattcl | 0.386 ± 0.005 | 0.380 | 0.394 | 36.37 ± 1.63 |
| mattcl-py | input-kcen | 0.401 ± 0.020 | 0.388 | 0.444 | 37.78 ± 2.48 |
| pting | input-mattcl | 1.864 ± 0.018 | 1.845 | 1.879 | 175.60 ± 7.75 |
| pting | input-kcen | 1.879 ± 0.026 | 1.851 | 1.903 | 176.99 ± 8.02 |
| pting | input-lanjian | 1.893 ± 0.004 | 1.889 | 1.898 | 178.36 ± 7.70 |
| pting | input-pting | 1.945 ± 0.047 | 1.911 | 1.999 | 183.21 ± 9.06 |
| lanjian | input-mattcl | 2.387 ± 0.016 | 2.368 | 2.399 | 224.83 ± 9.81 |
| lanjian | input-kcen | 2.411 ± 0.023 | 2.384 | 2.428 | 227.09 ± 10.03 |
| lanjian | input-lanjian | 2.414 ± 0.037 | 2.374 | 2.448 | 227.37 ± 10.41 |
| lanjian | input-pting | 2.423 ± 0.073 | 2.366 | 2.506 | 228.28 ± 12.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|