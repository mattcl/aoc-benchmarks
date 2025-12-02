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
| kcen | input-whyando | 778.8 ± 171.9 | 27.0 | 1278.9 | 1.00 |
| kcen | input-mattcl | 788.0 ± 137.4 | 0.0 | 1361.8 | 1.01 ± 0.28 |
| mattcl | input-whyando | 944.3 ± 189.3 | 0.0 | 1493.7 | 1.21 ± 0.36 |
| mattcl | input-mattcl | 984.5 ± 145.2 | 492.1 | 1580.7 | 1.26 ± 0.34 |
| mattcl-py | input-whyando | 20090.5 ± 604.4 | 18976.0 | 22849.4 | 25.80 ± 5.75 |
| mattcl-py | input-mattcl | 20537.0 ± 687.7 | 19324.9 | 23773.9 | 26.37 ± 5.89 |
| whyando | input-mattcl | 82448.9 ± 1546.1 | 78925.1 | 85411.4 | 105.86 ± 23.46 |
| whyando | input-whyando | 109655.1 ± 2161.1 | 105924.2 | 117925.8 | 140.80 ± 31.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|