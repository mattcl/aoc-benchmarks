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
| kcen | input-lanjian | 893.2 ± 265.5 | 0.0 | 1156.5 | 1.00 |
| kcen | input-mattcl | 959.9 ± 191.5 | 166.9 | 1223.3 | 1.07 ± 0.38 |
| kcen | input-whyando | 997.6 ± 142.5 | 374.5 | 1183.9 | 1.12 ± 0.37 |
| whyando | input-lanjian | 1066.8 ± 131.1 | 558.8 | 1268.6 | 1.19 ± 0.38 |
| whyando | input-mattcl | 1098.3 ± 150.2 | 384.7 | 1330.8 | 1.23 ± 0.40 |
| whyando | input-whyando | 1113.6 ± 162.3 | 403.1 | 1323.7 | 1.25 ± 0.41 |
| mattcl | input-mattcl | 1120.6 ± 178.9 | 271.4 | 1358.6 | 1.25 ± 0.42 |
| mattcl | input-lanjian | 1152.7 ± 243.6 | 194.8 | 3289.7 | 1.29 ± 0.47 |
| mattcl | input-whyando | 1192.0 ± 162.8 | 103.7 | 1460.1 | 1.33 ± 0.44 |
| lanjian | input-mattcl | 1241.7 ± 233.9 | 233.5 | 1987.3 | 1.39 ± 0.49 |
| lanjian | input-lanjian | 1291.1 ± 202.7 | 458.9 | 1509.4 | 1.45 ± 0.49 |
| lanjian | input-whyando | 1324.6 ± 174.4 | 481.9 | 1540.3 | 1.48 ± 0.48 |
| mattcl-py | input-whyando | 20976.6 ± 593.3 | 19731.7 | 24477.0 | 23.48 ± 7.01 |
| mattcl-py | input-lanjian | 21029.1 ± 528.0 | 19790.4 | 23862.2 | 23.54 ± 7.02 |
| mattcl-py | input-mattcl | 22494.4 ± 3687.2 | 20114.7 | 32738.6 | 25.18 ± 8.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|