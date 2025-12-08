# Day 7 benchmarks

[link to problem](https://adventofcode.com/2025/day/7)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 7)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-whyando | 62.0 ± 432.1 | 0.0 | 5573.1 | 1.00 |
| mattcl | input-mattcl | 227.3 ± 172.4 | 0.0 | 597.2 | 3.67 ± 25.74 |
| whyando | input-lanjian | 369.0 ± 171.9 | 0.0 | 620.2 | 5.96 ± 41.63 |
| whyando | input-whyando | 369.0 ± 164.6 | 0.0 | 649.2 | 5.96 ± 41.63 |
| whyando | input-mattcl | 394.1 ± 156.5 | 0.0 | 704.0 | 6.36 ± 44.45 |
| mattcl | input-lanjian | 426.4 ± 168.6 | 0.0 | 720.6 | 6.88 ± 48.09 |
| kcen | input-whyando | 905.5 ± 646.6 | 262.1 | 9437.6 | 14.62 ± 102.47 |
| kcen | input-lanjian | 908.0 ± 155.8 | 295.6 | 1126.8 | 14.66 ± 102.26 |
| kcen | input-mattcl | 914.6 ± 162.4 | 8.3 | 1159.6 | 14.76 ± 103.00 |
| mattcl-py | input-mattcl | 18086.8 ± 521.0 | 17095.7 | 20559.4 | 291.95 ± 2036.34 |
| mattcl-py | input-lanjian | 18204.6 ± 627.4 | 17058.8 | 20735.8 | 293.85 ± 2049.62 |
| mattcl-py | input-whyando | 18934.4 ± 2360.4 | 17282.8 | 26541.3 | 305.63 ± 2132.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|