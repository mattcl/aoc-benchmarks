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
| whyando | input-mattcl | 587.7 ± 139.0 | 38.5 | 946.9 | 1.00 |
| whyando | input-whyando | 605.0 ± 149.1 | 0.0 | 1175.4 | 1.03 ± 0.35 |
| kcen | input-whyando | 820.9 ± 124.3 | 271.9 | 1038.7 | 1.40 ± 0.39 |
| kcen | input-mattcl | 885.3 ± 176.5 | 0.0 | 1437.6 | 1.51 ± 0.47 |
| mattcl | input-whyando | 1027.4 ± 142.9 | 412.6 | 1576.4 | 1.75 ± 0.48 |
| mattcl | input-mattcl | 1039.8 ± 197.6 | 407.0 | 1732.1 | 1.77 ± 0.54 |
| lanjian | input-mattcl | 1088.2 ± 153.6 | 412.4 | 1765.0 | 1.85 ± 0.51 |
| lanjian | input-whyando | 1146.3 ± 195.5 | 477.7 | 1805.5 | 1.95 ± 0.57 |
| mattcl-py | input-whyando | 20172.1 ± 482.7 | 19009.8 | 21725.6 | 34.32 ± 8.16 |
| mattcl-py | input-mattcl | 20458.8 ± 599.8 | 19261.4 | 23136.3 | 34.81 ± 8.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|