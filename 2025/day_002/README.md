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
| whyando | input-whyando | 538.2 ± 136.0 | 0.0 | 783.1 | 1.00 |
| whyando | input-mattcl | 550.7 ± 130.5 | 38.4 | 1053.4 | 1.02 ± 0.35 |
| whyando | input-lanjian | 555.3 ± 140.9 | 90.5 | 1006.6 | 1.03 ± 0.37 |
| kcen | input-mattcl | 793.6 ± 137.5 | 0.0 | 1332.2 | 1.47 ± 0.45 |
| kcen | input-lanjian | 800.3 ± 118.5 | 147.9 | 1128.8 | 1.49 ± 0.44 |
| kcen | input-whyando | 805.9 ± 151.7 | 0.0 | 1372.9 | 1.50 ± 0.47 |
| mattcl | input-whyando | 974.1 ± 136.1 | 504.9 | 1511.3 | 1.81 ± 0.52 |
| mattcl | input-mattcl | 982.7 ± 173.6 | 440.8 | 1747.4 | 1.83 ± 0.56 |
| mattcl | input-lanjian | 987.0 ± 165.3 | 446.8 | 1584.4 | 1.83 ± 0.56 |
| lanjian | input-whyando | 1095.8 ± 169.5 | 489.2 | 1821.1 | 2.04 ± 0.60 |
| lanjian | input-lanjian | 1103.4 ± 175.5 | 495.7 | 1792.7 | 2.05 ± 0.61 |
| lanjian | input-mattcl | 1107.5 ± 213.5 | 581.3 | 1876.0 | 2.06 ± 0.65 |
| mattcl-py | input-whyando | 20358.8 ± 774.7 | 18995.0 | 23857.7 | 37.83 ± 9.67 |
| mattcl-py | input-mattcl | 20475.1 ± 583.1 | 19403.9 | 23222.9 | 38.04 ± 9.68 |
| mattcl-py | input-lanjian | 20611.1 ± 632.7 | 18988.4 | 23606.1 | 38.30 ± 9.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|