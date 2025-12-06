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
| whyando | input-lanjian | 484.8 ± 263.0 | 0.0 | 2254.0 | 1.00 |
| whyando | input-whyando | 569.9 ± 160.7 | 0.0 | 1178.0 | 1.18 ± 0.72 |
| whyando | input-mattcl | 610.2 ± 126.5 | 128.5 | 1254.7 | 1.26 ± 0.73 |
| kcen | input-mattcl | 799.0 ± 155.1 | 0.0 | 1242.7 | 1.65 ± 0.95 |
| kcen | input-lanjian | 816.5 ± 132.2 | 0.0 | 1280.5 | 1.68 ± 0.95 |
| kcen | input-whyando | 873.7 ± 187.3 | 353.3 | 1562.6 | 1.80 ± 1.05 |
| mattcl | input-mattcl | 982.0 ± 163.2 | 344.6 | 1574.5 | 2.03 ± 1.15 |
| mattcl | input-lanjian | 995.2 ± 151.2 | 416.1 | 1611.2 | 2.05 ± 1.16 |
| mattcl | input-whyando | 1009.8 ± 171.0 | 465.9 | 1661.2 | 2.08 ± 1.18 |
| lanjian | input-mattcl | 1181.6 ± 229.6 | 23.3 | 2072.6 | 2.44 ± 1.40 |
| lanjian | input-whyando | 1200.1 ± 214.8 | 246.3 | 1839.8 | 2.48 ± 1.41 |
| lanjian | input-lanjian | 1213.0 ± 248.7 | 189.6 | 1968.8 | 2.50 ± 1.45 |
| mattcl-py | input-whyando | 20273.5 ± 664.1 | 19341.3 | 23255.9 | 41.82 ± 22.72 |
| mattcl-py | input-lanjian | 20674.9 ± 780.5 | 19784.1 | 26795.2 | 42.64 ± 23.19 |
| mattcl-py | input-mattcl | 20697.2 ± 563.6 | 19578.5 | 22890.3 | 42.69 ± 23.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|