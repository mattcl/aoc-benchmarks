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
| kcen | input-whyando | 679.7 ± 254.8 | 0.0 | 1266.6 | 1.00 |
| kcen | input-mattcl | 753.7 ± 122.2 | 284.1 | 1276.9 | 1.11 ± 0.45 |
| mattcl | input-whyando | 800.0 ± 287.5 | 0.0 | 1498.3 | 1.18 ± 0.61 |
| mattcl | input-mattcl | 925.4 ± 128.4 | 426.8 | 1435.0 | 1.36 ± 0.54 |
| mattcl-py | input-whyando | 20185.8 ± 565.5 | 19222.3 | 22446.5 | 29.70 ± 11.16 |
| mattcl-py | input-mattcl | 20469.3 ± 609.8 | 19305.1 | 23289.1 | 30.12 ± 11.33 |
| whyando | input-mattcl | 82114.7 ± 1422.0 | 79163.6 | 84745.8 | 120.81 ± 45.34 |
| whyando | input-whyando | 109668.7 ± 1821.6 | 106557.2 | 114113.2 | 161.35 ± 60.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|