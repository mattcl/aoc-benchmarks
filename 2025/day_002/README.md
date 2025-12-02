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
| mattcl | input-whyando | 565.6 ± 390.5 | 0.0 | 1116.7 | 1.00 |
| kcen | input-whyando | 841.0 ± 219.3 | 0.0 | 1505.0 | 1.49 ± 1.10 |
| kcen | input-mattcl | 903.6 ± 161.3 | 302.9 | 1387.8 | 1.60 ± 1.14 |
| mattcl | input-mattcl | 955.0 ± 186.8 | 34.2 | 1515.7 | 1.69 ± 1.21 |
| mattcl-py | input-whyando | 20426.6 ± 712.2 | 18956.6 | 23366.2 | 36.11 ± 24.96 |
| mattcl-py | input-mattcl | 20515.8 ± 671.1 | 19470.5 | 23511.1 | 36.27 ± 25.07 |
| whyando | input-mattcl | 82725.6 ± 2191.2 | 79539.4 | 90755.7 | 146.25 ± 101.04 |
| whyando | input-whyando | 109721.7 ± 1941.0 | 105962.8 | 113715.9 | 193.98 ± 133.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|