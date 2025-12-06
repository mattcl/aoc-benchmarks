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
| whyando | input-whyando | 349.4 ± 174.8 | 0.0 | 926.9 | 1.00 |
| whyando | input-lanjian | 394.3 ± 172.4 | 0.0 | 982.2 | 1.13 ± 0.75 |
| whyando | input-mattcl | 398.5 ± 165.5 | 0.0 | 843.3 | 1.14 ± 0.74 |
| mattcl | input-whyando | 616.9 ± 140.1 | 0.0 | 824.6 | 1.77 ± 0.97 |
| mattcl | input-lanjian | 640.9 ± 142.8 | 0.0 | 1032.2 | 1.83 ± 1.00 |
| mattcl | input-mattcl | 653.5 ± 165.9 | 0.0 | 1328.3 | 1.87 ± 1.05 |
| kcen | input-mattcl | 796.9 ± 183.2 | 0.0 | 1488.3 | 2.28 ± 1.26 |
| kcen | input-whyando | 799.4 ± 149.8 | 280.6 | 1391.8 | 2.29 ± 1.22 |
| lanjian | input-mattcl | 812.3 ± 148.6 | 103.6 | 1393.4 | 2.32 ± 1.24 |
| lanjian | input-whyando | 820.5 ± 155.5 | 144.7 | 1347.3 | 2.35 ± 1.26 |
| lanjian | input-lanjian | 829.0 ± 146.3 | 54.8 | 1362.0 | 2.37 ± 1.26 |
| kcen | input-lanjian | 835.9 ± 165.7 | 301.9 | 1324.5 | 2.39 ± 1.29 |
| mattcl-py | input-whyando | 20624.0 ± 777.4 | 19341.6 | 23800.1 | 59.02 ± 29.61 |
| mattcl-py | input-mattcl | 20675.9 ± 568.4 | 19723.2 | 23332.1 | 59.17 ± 29.64 |
| mattcl-py | input-lanjian | 20789.1 ± 755.7 | 19225.0 | 23960.0 | 59.49 ± 29.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|