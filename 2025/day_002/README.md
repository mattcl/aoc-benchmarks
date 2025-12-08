# Day 2 benchmarks

[link to problem](https://adventofcode.com/2025/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 384.5 ± 170.5 | 0.0 | 991.2 | 1.00 |
| whyando | input-mattcl | 399.6 ± 159.5 | 0.0 | 969.9 | 1.04 ± 0.62 |
| whyando | input-whyando | 417.6 ± 158.6 | 0.0 | 961.5 | 1.09 ± 0.63 |
| mattcl | input-whyando | 612.1 ± 173.3 | 0.0 | 1034.4 | 1.59 ± 0.84 |
| mattcl | input-mattcl | 646.5 ± 150.7 | 109.0 | 1160.4 | 1.68 ± 0.84 |
| mattcl | input-lanjian | 710.3 ± 205.8 | 54.5 | 1683.9 | 1.85 ± 0.98 |
| kcen | input-whyando | 794.9 ± 184.1 | 0.0 | 1276.3 | 2.07 ± 1.03 |
| lanjian | input-mattcl | 814.5 ± 146.4 | 0.0 | 1219.3 | 2.12 ± 1.01 |
| kcen | input-mattcl | 839.0 ± 161.7 | 340.1 | 1467.8 | 2.18 ± 1.06 |
| lanjian | input-lanjian | 858.7 ± 126.1 | 381.8 | 1292.0 | 2.23 ± 1.04 |
| lanjian | input-whyando | 870.7 ± 202.7 | 0.0 | 1693.2 | 2.26 ± 1.13 |
| kcen | input-lanjian | 906.0 ± 203.4 | 283.5 | 1479.5 | 2.36 ± 1.17 |
| mattcl-py | input-whyando | 20567.7 ± 704.2 | 19315.4 | 23766.8 | 53.49 ± 23.79 |
| mattcl-py | input-mattcl | 20696.1 ± 605.6 | 19800.6 | 24065.5 | 53.82 ± 23.92 |
| mattcl-py | input-lanjian | 20709.2 ± 686.9 | 19779.9 | 23962.4 | 53.86 ± 23.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|