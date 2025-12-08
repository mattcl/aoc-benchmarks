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
| whyando | input-lanjian | 453.9 ± 194.9 | 0.0 | 1150.9 | 1.00 |
| whyando | input-mattcl | 481.5 ± 157.5 | 0.0 | 1125.0 | 1.06 ± 0.57 |
| whyando | input-whyando | 495.0 ± 169.8 | 0.0 | 1131.9 | 1.09 ± 0.60 |
| mattcl | input-whyando | 738.1 ± 149.6 | 136.7 | 1149.4 | 1.63 ± 0.77 |
| mattcl | input-mattcl | 752.0 ± 152.1 | 235.3 | 1294.4 | 1.66 ± 0.79 |
| mattcl | input-lanjian | 758.1 ± 146.4 | 0.0 | 1181.2 | 1.67 ± 0.79 |
| kcen | input-whyando | 830.6 ± 177.2 | 0.0 | 1422.7 | 1.83 ± 0.88 |
| kcen | input-mattcl | 834.7 ± 141.4 | 300.8 | 1303.0 | 1.84 ± 0.85 |
| kcen | input-lanjian | 864.5 ± 134.2 | 289.8 | 1372.7 | 1.90 ± 0.87 |
| lanjian | input-lanjian | 1092.5 ± 155.3 | 508.9 | 1756.2 | 2.41 ± 1.09 |
| lanjian | input-whyando | 1135.8 ± 209.4 | 584.2 | 1849.0 | 2.50 ± 1.17 |
| lanjian | input-mattcl | 1141.6 ± 201.8 | 327.5 | 1774.3 | 2.52 ± 1.17 |
| mattcl-py | input-whyando | 18202.6 ± 572.9 | 17194.1 | 21268.0 | 40.10 ± 17.26 |
| mattcl-py | input-lanjian | 18243.8 ± 635.3 | 17325.9 | 21284.0 | 40.19 ± 17.31 |
| mattcl-py | input-mattcl | 18308.5 ± 703.8 | 16986.6 | 21757.2 | 40.33 ± 17.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|