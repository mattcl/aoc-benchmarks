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
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| kcen | input-mattcl | 840.1 ± 134.0 | 355.3 | 1351.9 | 1.00 |
| kcen | input-whyando | 852.3 ± 200.5 | 0.0 | 1346.2 | 1.01 ± 0.29 |
| mattcl | input-whyando | 1005.6 ± 288.8 | 221.3 | 1818.4 | 1.20 ± 0.39 |
| mattcl | input-mattcl | 1086.6 ± 166.4 | 298.6 | 1795.0 | 1.29 ± 0.29 |
| mattcl-py | input-whyando | 20140.8 ± 725.8 | 18806.5 | 23822.2 | 23.97 ± 3.92 |
| mattcl-py | input-mattcl | 20373.3 ± 414.9 | 19424.6 | 21951.3 | 24.25 ± 3.90 |
| whyando | input-mattcl | 81774.9 ± 1318.5 | 79165.4 | 85130.0 | 97.34 ± 15.61 |
| whyando | input-whyando | 109873.4 ± 1463.2 | 107689.6 | 113839.7 | 130.79 ± 20.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|