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
| kcen | input-mattcl | 810.5 ± 134.9 | 322.9 | 1367.6 | 1.00 |
| kcen | input-whyando | 872.6 ± 164.4 | 380.5 | 1579.1 | 1.08 ± 0.27 |
| mattcl | input-whyando | 1080.4 ± 153.2 | 547.4 | 1835.7 | 1.33 ± 0.29 |
| mattcl | input-mattcl | 1117.0 ± 214.8 | 370.0 | 1905.8 | 1.38 ± 0.35 |
| mattcl-py | input-whyando | 20172.8 ± 473.2 | 18879.3 | 22225.2 | 24.89 ± 4.18 |
| mattcl-py | input-mattcl | 20409.4 ± 612.2 | 19053.5 | 24075.7 | 25.18 ± 4.26 |
| whyando | input-mattcl | 82036.6 ± 1269.4 | 79963.3 | 85188.9 | 101.21 ± 16.91 |
| whyando | input-whyando | 109730.8 ± 4914.0 | 105678.5 | 133186.1 | 135.38 ± 23.33 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|