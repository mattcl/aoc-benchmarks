# Day 1 benchmarks

[link to problem](https://adventofcode.com/2025/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 713.1 ± 163.8 | 34.9 | 1280.5 | 1.00 |
| whyando | input-whyando | 723.6 ± 175.5 | 0.0 | 1257.3 | 1.01 ± 0.34 |
| whyando | input-mattcl | 727.8 ± 135.8 | 82.6 | 916.7 | 1.02 ± 0.30 |
| kcen | input-mattcl | 840.1 ± 147.7 | 338.9 | 1359.3 | 1.18 ± 0.34 |
| kcen | input-whyando | 842.3 ± 161.8 | 267.1 | 1346.5 | 1.18 ± 0.35 |
| kcen | input-lanjian | 946.7 ± 179.7 | 3.8 | 1539.7 | 1.33 ± 0.40 |
| mattcl | input-mattcl | 1012.2 ± 168.8 | 440.2 | 1733.6 | 1.42 ± 0.40 |
| mattcl | input-lanjian | 1019.2 ± 173.7 | 426.1 | 1845.6 | 1.43 ± 0.41 |
| mattcl | input-whyando | 1020.8 ± 189.5 | 148.4 | 1667.3 | 1.43 ± 0.42 |
| lanjian | input-mattcl | 1355.9 ± 250.6 | 233.6 | 2699.7 | 1.90 ± 0.56 |
| lanjian | input-lanjian | 1399.7 ± 182.1 | 401.1 | 2439.6 | 1.96 ± 0.52 |
| lanjian | input-whyando | 1404.7 ± 129.2 | 858.0 | 1991.8 | 1.97 ± 0.49 |
| mattcl-py | input-whyando | 18181.4 ± 597.8 | 16889.8 | 21409.0 | 25.50 ± 5.92 |
| mattcl-py | input-lanjian | 18318.1 ± 745.1 | 17285.4 | 21766.9 | 25.69 ± 5.99 |
| mattcl-py | input-mattcl | 18409.9 ± 817.3 | 17178.3 | 21961.9 | 25.82 ± 6.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|