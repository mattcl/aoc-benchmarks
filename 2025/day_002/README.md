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
| whyando | input-lanjian | 124.0 ± 140.2 | 0.0 | 523.9 | 1.00 |
| mattcl | input-mattcl | 206.0 ± 232.6 | 0.0 | 1027.9 | 1.66 ± 2.65 |
| lanjian | input-mattcl | 235.4 ± 231.0 | 0.0 | 893.8 | 1.90 ± 2.84 |
| whyando | input-mattcl | 357.6 ± 181.2 | 0.0 | 1000.4 | 2.88 ± 3.57 |
| kcen | input-mattcl | 373.1 ± 246.9 | 0.0 | 941.4 | 3.01 ± 3.94 |
| whyando | input-whyando | 373.7 ± 157.7 | 0.0 | 905.7 | 3.01 ± 3.64 |
| mattcl | input-lanjian | 604.2 ± 154.1 | 0.0 | 1017.8 | 4.87 ± 5.65 |
| lanjian | input-whyando | 621.1 ± 165.2 | 0.0 | 1052.5 | 5.01 ± 5.82 |
| mattcl | input-whyando | 621.6 ± 175.3 | 0.0 | 1315.2 | 5.01 ± 5.84 |
| lanjian | input-lanjian | 649.9 ± 163.0 | 0.0 | 1719.1 | 5.24 ± 6.07 |
| kcen | input-lanjian | 780.1 ± 150.9 | 165.2 | 1280.1 | 6.29 ± 7.22 |
| kcen | input-whyando | 823.7 ± 161.8 | 356.5 | 1363.3 | 6.64 ± 7.62 |
| mattcl-py | input-whyando | 20392.8 ± 549.8 | 19113.9 | 23427.3 | 164.46 ± 186.01 |
| mattcl-py | input-mattcl | 20726.2 ± 713.4 | 19580.9 | 23672.4 | 167.15 ± 189.08 |
| mattcl-py | input-lanjian | 20827.2 ± 1028.7 | 19479.2 | 29154.7 | 167.97 ± 190.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|