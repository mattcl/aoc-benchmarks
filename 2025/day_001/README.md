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
| whyando | input-lanjian | 703.1 ± 137.4 | 254.0 | 1115.9 | 1.00 |
| whyando | input-mattcl | 716.1 ± 137.9 | 147.5 | 1192.0 | 1.02 ± 0.28 |
| whyando | input-whyando | 720.8 ± 154.4 | 0.0 | 1348.5 | 1.03 ± 0.30 |
| kcen | input-whyando | 805.3 ± 154.8 | 0.0 | 1310.3 | 1.15 ± 0.31 |
| kcen | input-mattcl | 848.1 ± 186.9 | 275.3 | 1426.7 | 1.21 ± 0.36 |
| kcen | input-lanjian | 866.1 ± 177.7 | 0.0 | 1817.5 | 1.23 ± 0.35 |
| mattcl | input-lanjian | 991.4 ± 170.6 | 441.2 | 1599.4 | 1.41 ± 0.37 |
| mattcl | input-whyando | 997.3 ± 185.4 | 145.2 | 1813.9 | 1.42 ± 0.38 |
| mattcl | input-mattcl | 1012.2 ± 168.0 | 556.7 | 1680.6 | 1.44 ± 0.37 |
| lanjian | input-lanjian | 1286.9 ± 233.1 | 244.1 | 2043.6 | 1.83 ± 0.49 |
| lanjian | input-whyando | 1340.9 ± 196.3 | 570.7 | 2049.1 | 1.91 ± 0.47 |
| lanjian | input-mattcl | 1358.1 ± 193.2 | 674.8 | 2529.2 | 1.93 ± 0.47 |
| mattcl-py | input-mattcl | 18043.6 ± 464.8 | 16813.2 | 20209.0 | 25.66 ± 5.06 |
| mattcl-py | input-lanjian | 18124.8 ± 722.7 | 16775.7 | 21898.0 | 25.78 ± 5.14 |
| mattcl-py | input-whyando | 18250.1 ± 713.9 | 17175.0 | 21078.2 | 25.96 ± 5.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|