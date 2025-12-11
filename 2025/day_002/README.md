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
| whyando | input-lanjian | 428.2 ± 164.6 | 0.0 | 692.6 | 1.00 |
| whyando | input-mattcl | 430.2 ± 1847.4 | 0.0 | 14983.6 | 1.00 ± 4.33 |
| whyando | input-whyando | 449.2 ± 157.4 | 0.0 | 744.5 | 1.05 ± 0.55 |
| mattcl | input-lanjian | 669.7 ± 153.7 | 0.0 | 873.4 | 1.56 ± 0.70 |
| kcen | input-mattcl | 674.2 ± 296.4 | 0.0 | 1050.3 | 1.57 ± 0.92 |
| lanjian | input-lanjian | 681.9 ± 185.3 | 0.0 | 911.3 | 1.59 ± 0.75 |
| mattcl | input-mattcl | 690.2 ± 154.0 | 0.0 | 892.6 | 1.61 ± 0.72 |
| mattcl | input-whyando | 700.7 ± 159.0 | 0.0 | 904.7 | 1.64 ± 0.73 |
| lanjian | input-mattcl | 703.9 ± 203.3 | 0.0 | 1015.8 | 1.64 ± 0.79 |
| lanjian | input-whyando | 744.0 ± 140.5 | 273.1 | 995.1 | 1.74 ± 0.74 |
| kcen | input-lanjian | 804.1 ± 166.3 | 0.0 | 1015.4 | 1.88 ± 0.82 |
| kcen | input-whyando | 884.9 ± 1852.3 | 0.0 | 18785.3 | 2.07 ± 4.40 |
| mattcl-py | input-lanjian | 21053.5 ± 680.2 | 19745.1 | 25324.9 | 49.17 ± 18.97 |
| mattcl-py | input-mattcl | 21387.1 ± 1925.9 | 19920.8 | 32827.0 | 49.95 ± 19.72 |
| mattcl-py | input-whyando | 22291.5 ± 526.7 | 21476.8 | 24929.8 | 52.06 ± 20.05 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|