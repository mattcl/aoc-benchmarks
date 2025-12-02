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
| whyando | input-whyando | 640.5 ± 121.7 | 0.0 | 964.8 | 1.00 |
| whyando | input-mattcl | 641.5 ± 142.4 | 0.0 | 1259.2 | 1.00 ± 0.29 |
| kcen | input-mattcl | 842.9 ± 202.4 | 0.0 | 1492.6 | 1.32 ± 0.40 |
| kcen | input-whyando | 895.6 ± 190.0 | 249.4 | 1848.6 | 1.40 ± 0.40 |
| mattcl | input-mattcl | 1026.1 ± 177.3 | 432.3 | 1632.8 | 1.60 ± 0.41 |
| mattcl | input-whyando | 1047.8 ± 169.3 | 435.9 | 1693.5 | 1.64 ± 0.41 |
| mattcl-py | input-whyando | 20190.5 ± 603.1 | 18748.5 | 23382.3 | 31.52 ± 6.06 |
| mattcl-py | input-mattcl | 20460.7 ± 611.9 | 19403.4 | 23095.5 | 31.95 ± 6.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|