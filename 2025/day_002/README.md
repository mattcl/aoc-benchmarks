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
| whyando | input-whyando | 567.1 ± 163.8 | 0.0 | 1027.9 | 1.00 |
| whyando | input-lanjian | 586.5 ± 119.8 | 96.8 | 768.6 | 1.03 ± 0.37 |
| whyando | input-mattcl | 590.4 ± 126.7 | 89.8 | 1008.3 | 1.04 ± 0.37 |
| kcen | input-whyando | 811.6 ± 141.5 | 0.0 | 1220.4 | 1.43 ± 0.48 |
| kcen | input-mattcl | 817.2 ± 147.5 | 0.0 | 1261.5 | 1.44 ± 0.49 |
| kcen | input-lanjian | 884.2 ± 193.2 | 299.5 | 1583.4 | 1.56 ± 0.56 |
| mattcl | input-lanjian | 981.6 ± 169.7 | 153.8 | 1624.1 | 1.73 ± 0.58 |
| mattcl | input-whyando | 999.3 ± 126.6 | 597.4 | 1519.5 | 1.76 ± 0.56 |
| mattcl | input-mattcl | 1002.3 ± 169.7 | 520.2 | 1651.2 | 1.77 ± 0.59 |
| lanjian | input-whyando | 1093.3 ± 174.4 | 508.6 | 1823.1 | 1.93 ± 0.64 |
| lanjian | input-mattcl | 1101.9 ± 184.6 | 387.2 | 1795.1 | 1.94 ± 0.65 |
| lanjian | input-lanjian | 1186.5 ± 199.1 | 712.0 | 1948.8 | 2.09 ± 0.70 |
| mattcl-py | input-whyando | 20385.3 ± 606.1 | 19103.2 | 22904.3 | 35.95 ± 10.44 |
| mattcl-py | input-mattcl | 20573.2 ± 564.6 | 19460.4 | 23420.9 | 36.28 ± 10.53 |
| mattcl-py | input-lanjian | 20600.0 ± 614.2 | 19089.8 | 23664.1 | 36.32 ± 10.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|