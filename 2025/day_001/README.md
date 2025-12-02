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
| whyando | input-lanjian | 681.5 ± 157.1 | 103.0 | 1090.9 | 1.00 |
| whyando | input-mattcl | 688.4 ± 125.0 | 185.1 | 1113.1 | 1.01 ± 0.30 |
| whyando | input-whyando | 716.1 ± 109.0 | 185.3 | 1047.0 | 1.05 ± 0.29 |
| kcen | input-lanjian | 814.4 ± 159.4 | 215.6 | 1628.3 | 1.19 ± 0.36 |
| kcen | input-mattcl | 833.0 ± 134.4 | 310.1 | 1320.5 | 1.22 ± 0.34 |
| kcen | input-whyando | 857.7 ± 151.2 | 330.7 | 1589.2 | 1.26 ± 0.37 |
| mattcl | input-lanjian | 977.5 ± 169.9 | 289.3 | 1729.3 | 1.43 ± 0.41 |
| mattcl | input-mattcl | 1032.9 ± 184.7 | 397.7 | 1742.8 | 1.52 ± 0.44 |
| mattcl | input-whyando | 1079.3 ± 196.3 | 428.3 | 1810.3 | 1.58 ± 0.47 |
| lanjian | input-lanjian | 1210.5 ± 239.2 | 519.5 | 2142.3 | 1.78 ± 0.54 |
| lanjian | input-mattcl | 1296.0 ± 236.3 | 571.2 | 2525.1 | 1.90 ± 0.56 |
| lanjian | input-whyando | 1331.9 ± 211.4 | 588.4 | 2211.1 | 1.95 ± 0.55 |
| mattcl-py | input-mattcl | 18067.5 ± 634.5 | 16648.7 | 21351.7 | 26.51 ± 6.18 |
| mattcl-py | input-lanjian | 18138.8 ± 739.0 | 16736.6 | 21265.2 | 26.61 ± 6.23 |
| mattcl-py | input-whyando | 18145.2 ± 592.6 | 17104.0 | 21717.2 | 26.62 ± 6.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|