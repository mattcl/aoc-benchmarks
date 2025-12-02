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
| kcen | input-mattcl | 753.4 ± 114.9 | 267.0 | 924.7 | 1.00 |
| kcen | input-whyando | 775.6 ± 113.5 | 270.1 | 1189.7 | 1.03 ± 0.22 |
| mattcl | input-mattcl | 1090.0 ± 220.4 | 452.2 | 1789.0 | 1.45 ± 0.37 |
| mattcl | input-whyando | 1130.1 ± 223.9 | 447.5 | 1935.9 | 1.50 ± 0.38 |
| mattcl-py | input-whyando | 20186.2 ± 616.1 | 18933.8 | 22339.8 | 26.79 ± 4.17 |
| mattcl-py | input-mattcl | 20296.5 ± 561.4 | 19172.8 | 22508.2 | 26.94 ± 4.17 |
| whyando | input-mattcl | 82127.1 ± 2439.3 | 79420.8 | 92197.5 | 109.00 ± 16.93 |
| whyando | input-whyando | 109213.8 ± 1116.8 | 107389.7 | 111707.1 | 144.95 ± 22.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|