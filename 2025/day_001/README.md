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
| whyando | input-mattcl | 648.8 ± 141.6 | 0.0 | 1098.5 | 1.00 |
| whyando | input-whyando | 665.3 ± 139.0 | 187.1 | 1062.7 | 1.03 ± 0.31 |
| whyando | input-lanjian | 679.4 ± 136.1 | 59.8 | 1182.1 | 1.05 ± 0.31 |
| kcen | input-mattcl | 860.7 ± 137.0 | 38.3 | 1323.1 | 1.33 ± 0.36 |
| kcen | input-lanjian | 869.7 ± 159.1 | 0.0 | 1423.6 | 1.34 ± 0.38 |
| kcen | input-whyando | 925.8 ± 202.6 | 187.8 | 1513.7 | 1.43 ± 0.44 |
| mattcl | input-mattcl | 1043.3 ± 219.2 | 402.8 | 1807.8 | 1.61 ± 0.49 |
| mattcl | input-lanjian | 1062.6 ± 169.2 | 510.3 | 1689.7 | 1.64 ± 0.44 |
| mattcl | input-whyando | 1115.4 ± 224.6 | 519.1 | 2489.7 | 1.72 ± 0.51 |
| lanjian | input-whyando | 1362.7 ± 216.3 | 284.1 | 2008.8 | 2.10 ± 0.57 |
| lanjian | input-lanjian | 1392.7 ± 212.1 | 618.5 | 2060.4 | 2.15 ± 0.57 |
| lanjian | input-mattcl | 1405.3 ± 231.0 | 735.1 | 2702.2 | 2.17 ± 0.59 |
| mattcl-py | input-mattcl | 18256.1 ± 677.6 | 17190.3 | 23318.9 | 28.14 ± 6.23 |
| mattcl-py | input-lanjian | 18289.6 ± 688.5 | 16841.7 | 21069.3 | 28.19 ± 6.24 |
| mattcl-py | input-whyando | 18364.5 ± 765.3 | 17244.5 | 21481.4 | 28.30 ± 6.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|