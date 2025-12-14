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
| whyando | input-mattcl | 509.9 ± 178.7 | 0.0 | 972.6 | 1.00 |
| whyando | input-whyando | 547.7 ± 182.9 | 0.0 | 998.7 | 1.07 ± 0.52 |
| mattcl | input-whyando | 548.2 ± 162.0 | 0.0 | 1082.4 | 1.08 ± 0.49 |
| mattcl | input-mattcl | 554.7 ± 192.3 | 0.0 | 1162.6 | 1.09 ± 0.54 |
| whyando | input-lanjian | 566.3 ± 182.4 | 0.0 | 1383.0 | 1.11 ± 0.53 |
| mattcl | input-lanjian | 576.2 ± 197.2 | 0.0 | 1639.9 | 1.13 ± 0.55 |
| kcen | input-lanjian | 862.8 ± 136.7 | 340.1 | 1371.1 | 1.69 ± 0.65 |
| lanjian | input-mattcl | 870.7 ± 177.0 | 58.4 | 1328.5 | 1.71 ± 0.69 |
| kcen | input-mattcl | 879.2 ± 138.6 | 419.2 | 1494.0 | 1.72 ± 0.66 |
| lanjian | input-lanjian | 912.4 ± 151.3 | 0.0 | 1438.4 | 1.79 ± 0.69 |
| kcen | input-whyando | 928.0 ± 168.6 | 233.7 | 1461.4 | 1.82 ± 0.72 |
| lanjian | input-whyando | 974.8 ± 141.5 | 368.8 | 1442.0 | 1.91 ± 0.73 |
| mattcl-py | input-lanjian | 18322.0 ± 591.8 | 17240.8 | 22145.7 | 35.93 ± 12.65 |
| mattcl-py | input-whyando | 18339.7 ± 672.8 | 17245.0 | 21956.1 | 35.97 ± 12.67 |
| mattcl-py | input-mattcl | 18347.1 ± 673.4 | 17247.2 | 21311.2 | 35.98 ± 12.68 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|