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
| whyando | input-lanjian | 523.4 ± 173.9 | 0.0 | 1122.4 | 1.00 |
| whyando | input-whyando | 543.2 ± 185.1 | 0.0 | 1111.8 | 1.04 ± 0.49 |
| whyando | input-mattcl | 564.6 ± 141.2 | 0.0 | 996.4 | 1.08 ± 0.45 |
| kcen | input-whyando | 842.0 ± 136.5 | 321.9 | 1210.9 | 1.61 ± 0.59 |
| kcen | input-mattcl | 863.7 ± 186.9 | 291.8 | 1556.2 | 1.65 ± 0.65 |
| kcen | input-lanjian | 901.8 ± 192.5 | 393.3 | 1531.5 | 1.72 ± 0.68 |
| mattcl | input-whyando | 944.5 ± 159.9 | 360.0 | 1431.5 | 1.80 ± 0.67 |
| mattcl | input-lanjian | 999.7 ± 151.1 | 424.4 | 1659.4 | 1.91 ± 0.70 |
| mattcl | input-mattcl | 1004.7 ± 181.6 | 409.5 | 1938.5 | 1.92 ± 0.73 |
| lanjian | input-lanjian | 1124.3 ± 238.0 | 517.7 | 2262.6 | 2.15 ± 0.85 |
| lanjian | input-whyando | 1186.2 ± 216.6 | 444.6 | 1882.5 | 2.27 ± 0.86 |
| lanjian | input-mattcl | 1203.6 ± 235.7 | 442.1 | 2543.7 | 2.30 ± 0.89 |
| mattcl-py | input-whyando | 20490.3 ± 710.5 | 18904.3 | 23860.5 | 39.15 ± 13.08 |
| mattcl-py | input-mattcl | 20504.1 ± 604.8 | 19537.2 | 23647.4 | 39.18 ± 13.07 |
| mattcl-py | input-lanjian | 20736.8 ± 702.3 | 19927.1 | 24062.4 | 39.62 ± 13.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|