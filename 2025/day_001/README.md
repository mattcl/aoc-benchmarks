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
| whyando | input-lanjian | 576.8 ± 159.2 | 0.0 | 964.7 | 1.00 |
| whyando | input-whyando | 592.0 ± 154.3 | 0.0 | 1018.4 | 1.03 ± 0.39 |
| whyando | input-mattcl | 611.6 ± 150.3 | 148.3 | 1138.3 | 1.06 ± 0.39 |
| kcen | input-whyando | 797.3 ± 140.8 | 0.0 | 1260.6 | 1.38 ± 0.45 |
| kcen | input-mattcl | 810.4 ± 155.5 | 0.0 | 1307.6 | 1.40 ± 0.47 |
| kcen | input-lanjian | 837.5 ± 142.8 | 213.4 | 1416.0 | 1.45 ± 0.47 |
| mattcl | input-mattcl | 969.5 ± 178.9 | 46.5 | 1654.1 | 1.68 ± 0.56 |
| mattcl | input-lanjian | 986.7 ± 135.6 | 233.3 | 1585.3 | 1.71 ± 0.53 |
| mattcl | input-whyando | 1002.7 ± 179.0 | 381.6 | 1680.3 | 1.74 ± 0.57 |
| lanjian | input-mattcl | 1267.7 ± 231.5 | 308.5 | 1730.4 | 2.20 ± 0.73 |
| lanjian | input-lanjian | 1322.8 ± 189.9 | 627.1 | 2110.1 | 2.29 ± 0.71 |
| lanjian | input-whyando | 1331.4 ± 202.3 | 637.7 | 2103.8 | 2.31 ± 0.73 |
| mattcl-py | input-whyando | 18229.2 ± 419.3 | 17256.3 | 20005.6 | 31.60 ± 8.75 |
| mattcl-py | input-lanjian | 18260.8 ± 731.9 | 17169.0 | 21373.9 | 31.66 ± 8.83 |
| mattcl-py | input-mattcl | 18354.7 ± 795.3 | 16983.0 | 21872.4 | 31.82 ± 8.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|