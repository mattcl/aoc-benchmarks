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
| whyando | input-mattcl | 551.9 ± 157.7 | 0.0 | 1037.6 | 1.00 |
| whyando | input-whyando | 567.6 ± 165.6 | 0.0 | 981.5 | 1.03 ± 0.42 |
| mattcl | input-whyando | 612.6 ± 312.2 | 0.0 | 1095.4 | 1.11 ± 0.65 |
| kcen | input-whyando | 795.4 ± 184.3 | 0.0 | 1453.4 | 1.44 ± 0.53 |
| kcen | input-mattcl | 804.1 ± 180.2 | 0.0 | 1341.3 | 1.46 ± 0.53 |
| mattcl | input-mattcl | 1038.4 ± 179.2 | 549.1 | 2439.6 | 1.88 ± 0.63 |
| mattcl-py | input-whyando | 20265.8 ± 818.4 | 18666.9 | 26473.7 | 36.72 ± 10.59 |
| mattcl-py | input-mattcl | 20354.2 ± 559.1 | 18984.5 | 22522.2 | 36.88 ± 10.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|