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
| whyando | input-lanjian | 501.1 ± 166.1 | 0.0 | 740.3 | 1.00 |
| whyando | input-whyando | 540.1 ± 162.7 | 0.0 | 1015.0 | 1.08 ± 0.48 |
| whyando | input-mattcl | 550.6 ± 148.0 | 128.8 | 1050.1 | 1.10 ± 0.47 |
| kcen | input-lanjian | 774.8 ± 157.6 | 0.0 | 1290.3 | 1.55 ± 0.60 |
| kcen | input-mattcl | 779.8 ± 162.9 | 0.0 | 1293.2 | 1.56 ± 0.61 |
| kcen | input-whyando | 791.2 ± 131.0 | 284.4 | 1391.7 | 1.58 ± 0.58 |
| mattcl | input-whyando | 1002.9 ± 172.1 | 287.3 | 1511.0 | 2.00 ± 0.75 |
| mattcl | input-mattcl | 1007.0 ± 193.3 | 320.6 | 1711.6 | 2.01 ± 0.77 |
| mattcl | input-lanjian | 1009.7 ± 137.3 | 481.2 | 1596.2 | 2.02 ± 0.72 |
| lanjian | input-mattcl | 1078.7 ± 219.0 | 68.9 | 1855.7 | 2.15 ± 0.84 |
| lanjian | input-lanjian | 1127.2 ± 159.7 | 479.5 | 1842.9 | 2.25 ± 0.81 |
| lanjian | input-whyando | 1182.4 ± 199.7 | 564.5 | 2116.7 | 2.36 ± 0.88 |
| mattcl-py | input-whyando | 20318.6 ± 736.2 | 18932.7 | 23235.1 | 40.55 ± 13.52 |
| mattcl-py | input-lanjian | 20521.4 ± 501.9 | 19542.8 | 22958.4 | 40.96 ± 13.61 |
| mattcl-py | input-mattcl | 20706.5 ± 737.1 | 19713.4 | 24179.1 | 41.33 ± 13.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|