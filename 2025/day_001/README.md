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
| mattcl | input-whyando | 319.8 ± 222.8 | 0.0 | 703.2 | 1.00 |
| mattcl | input-lanjian | 479.2 ± 171.7 | 0.0 | 740.7 | 1.50 ± 1.17 |
| mattcl | input-mattcl | 515.0 ± 141.0 | 30.8 | 980.4 | 1.61 ± 1.21 |
| kcen | input-whyando | 852.4 ± 127.7 | 481.5 | 1275.8 | 2.67 ± 1.90 |
| whyando | input-mattcl | 870.3 ± 231.8 | 0.0 | 1560.9 | 2.72 ± 2.03 |
| kcen | input-mattcl | 875.0 ± 188.1 | 0.0 | 1430.2 | 2.74 ± 1.99 |
| kcen | input-lanjian | 930.7 ± 185.8 | 326.2 | 1535.3 | 2.91 ± 2.11 |
| whyando | input-whyando | 987.4 ± 178.5 | 401.1 | 1528.2 | 3.09 ± 2.22 |
| whyando | input-lanjian | 1000.0 ± 198.8 | 207.8 | 1946.5 | 3.13 ± 2.27 |
| lanjian | input-whyando | 1134.5 ± 363.1 | 99.4 | 1555.5 | 3.55 ± 2.72 |
| lanjian | input-lanjian | 1352.5 ± 194.9 | 576.3 | 1853.8 | 4.23 ± 3.01 |
| lanjian | input-mattcl | 1353.2 ± 174.5 | 654.1 | 2130.0 | 4.23 ± 3.00 |
| mattcl-py | input-mattcl | 18167.5 ± 559.6 | 16924.3 | 21011.9 | 56.82 ± 39.62 |
| mattcl-py | input-lanjian | 18220.4 ± 556.9 | 16902.1 | 21395.1 | 56.98 ± 39.73 |
| mattcl-py | input-whyando | 18377.1 ± 913.9 | 17247.0 | 25869.9 | 57.47 ± 40.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|