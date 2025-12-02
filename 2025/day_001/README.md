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
| whyando | input-mattcl | 711.5 ± 155.3 | 0.0 | 1128.0 | 1.00 |
| whyando | input-whyando | 736.6 ± 158.2 | 194.0 | 1479.7 | 1.04 ± 0.32 |
| whyando | input-lanjian | 740.2 ± 137.5 | 0.0 | 1135.9 | 1.04 ± 0.30 |
| kcen | input-whyando | 811.3 ± 155.9 | 30.2 | 1140.1 | 1.14 ± 0.33 |
| kcen | input-mattcl | 859.0 ± 167.9 | 312.4 | 1571.1 | 1.21 ± 0.35 |
| kcen | input-lanjian | 951.7 ± 176.4 | 480.2 | 1741.1 | 1.34 ± 0.38 |
| mattcl | input-mattcl | 1001.3 ± 176.9 | 153.9 | 1742.1 | 1.41 ± 0.40 |
| mattcl | input-whyando | 1020.4 ± 219.0 | 80.4 | 2116.1 | 1.43 ± 0.44 |
| mattcl | input-lanjian | 1037.6 ± 179.9 | 509.2 | 1736.2 | 1.46 ± 0.41 |
| lanjian | input-lanjian | 1298.3 ± 241.4 | 523.5 | 2056.5 | 1.82 ± 0.52 |
| lanjian | input-mattcl | 1302.9 ± 232.3 | 504.3 | 2475.2 | 1.83 ± 0.52 |
| lanjian | input-whyando | 1318.9 ± 244.0 | 565.8 | 2124.5 | 1.85 ± 0.53 |
| mattcl-py | input-lanjian | 18163.7 ± 631.5 | 16931.1 | 22039.8 | 25.53 ± 5.64 |
| mattcl-py | input-mattcl | 18167.5 ± 673.8 | 17068.8 | 21019.6 | 25.54 ± 5.65 |
| mattcl-py | input-whyando | 18358.5 ± 1059.0 | 16812.6 | 27105.5 | 25.80 ± 5.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|