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
| whyando | input-mattcl | 396.0 ± 197.0 | 0.0 | 771.2 | 1.00 |
| whyando | input-lanjian | 452.0 ± 155.6 | 0.0 | 834.8 | 1.14 ± 0.69 |
| mattcl | input-whyando | 462.6 ± 176.1 | 0.0 | 861.7 | 1.17 ± 0.73 |
| mattcl | input-mattcl | 470.0 ± 189.8 | 0.0 | 1087.3 | 1.19 ± 0.76 |
| mattcl | input-lanjian | 482.7 ± 176.2 | 0.0 | 1113.7 | 1.22 ± 0.75 |
| whyando | input-whyando | 483.6 ± 149.9 | 0.0 | 1048.5 | 1.22 ± 0.72 |
| lanjian | input-whyando | 693.5 ± 272.1 | 0.0 | 1391.1 | 1.75 ± 1.11 |
| kcen | input-whyando | 785.3 ± 161.7 | 0.0 | 1210.9 | 1.98 ± 1.07 |
| kcen | input-lanjian | 804.2 ± 147.2 | 241.6 | 1299.6 | 2.03 ± 1.08 |
| lanjian | input-lanjian | 810.7 ± 169.4 | 0.0 | 1359.1 | 2.05 ± 1.10 |
| kcen | input-mattcl | 827.5 ± 165.9 | 375.3 | 1792.9 | 2.09 ± 1.12 |
| lanjian | input-mattcl | 840.6 ± 125.1 | 288.8 | 1341.4 | 2.12 ± 1.10 |
| mattcl-py | input-mattcl | 18183.8 ± 619.7 | 17138.0 | 21452.5 | 45.92 ± 22.90 |
| mattcl-py | input-lanjian | 18236.7 ± 665.8 | 17267.7 | 21739.6 | 46.06 ± 22.97 |
| mattcl-py | input-whyando | 18379.1 ± 765.6 | 17205.9 | 21672.0 | 46.42 ± 23.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|