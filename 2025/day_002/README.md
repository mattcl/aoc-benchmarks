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
| whyando | input-whyando | 414.6 ± 185.9 | 0.0 | 987.0 | 1.00 |
| whyando | input-lanjian | 425.8 ± 160.4 | 0.0 | 903.2 | 1.03 ± 0.60 |
| whyando | input-mattcl | 473.7 ± 133.1 | 0.0 | 1048.6 | 1.14 ± 0.60 |
| mattcl | input-whyando | 644.2 ± 146.5 | 81.2 | 1324.8 | 1.55 ± 0.78 |
| mattcl | input-lanjian | 663.6 ± 264.6 | 0.0 | 3339.5 | 1.60 ± 0.96 |
| mattcl | input-mattcl | 665.4 ± 171.5 | 0.0 | 1120.1 | 1.61 ± 0.83 |
| lanjian | input-whyando | 673.6 ± 139.8 | 0.0 | 1047.3 | 1.62 ± 0.80 |
| lanjian | input-mattcl | 690.8 ± 146.2 | 0.0 | 1379.7 | 1.67 ± 0.83 |
| lanjian | input-lanjian | 722.9 ± 120.3 | 290.7 | 1031.5 | 1.74 ± 0.83 |
| kcen | input-mattcl | 808.2 ± 154.7 | 0.0 | 1282.5 | 1.95 ± 0.95 |
| kcen | input-lanjian | 814.0 ± 151.6 | 254.4 | 1264.4 | 1.96 ± 0.95 |
| kcen | input-whyando | 821.3 ± 142.0 | 306.6 | 1477.4 | 1.98 ± 0.95 |
| mattcl-py | input-whyando | 20435.1 ± 563.6 | 19127.8 | 24058.4 | 49.29 ± 22.15 |
| mattcl-py | input-lanjian | 20756.7 ± 685.5 | 19512.9 | 24022.0 | 50.07 ± 22.52 |
| mattcl-py | input-mattcl | 20845.2 ± 755.0 | 19792.1 | 24299.6 | 50.28 ± 22.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|