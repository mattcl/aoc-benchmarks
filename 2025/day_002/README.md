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
| whyando | input-whyando | 401.3 ± 172.7 | 0.0 | 953.4 | 1.00 |
| whyando | input-mattcl | 406.1 ± 170.0 | 0.0 | 1020.1 | 1.01 ± 0.61 |
| whyando | input-lanjian | 413.9 ± 149.6 | 0.0 | 995.1 | 1.03 ± 0.58 |
| mattcl | input-whyando | 611.9 ± 174.9 | 0.0 | 1014.1 | 1.53 ± 0.79 |
| mattcl | input-lanjian | 622.5 ± 177.7 | 0.0 | 1220.3 | 1.55 ± 0.80 |
| lanjian | input-mattcl | 642.6 ± 165.7 | 0.0 | 1067.1 | 1.60 ± 0.80 |
| mattcl | input-mattcl | 644.5 ± 148.6 | 0.0 | 1077.8 | 1.61 ± 0.78 |
| lanjian | input-whyando | 660.8 ± 170.0 | 0.0 | 1213.4 | 1.65 ± 0.83 |
| lanjian | input-lanjian | 667.5 ± 156.0 | 0.0 | 1148.9 | 1.66 ± 0.81 |
| kcen | input-whyando | 769.6 ± 188.1 | 69.4 | 1457.3 | 1.92 ± 0.95 |
| kcen | input-lanjian | 803.9 ± 117.5 | 348.4 | 1209.7 | 2.00 ± 0.91 |
| kcen | input-mattcl | 830.7 ± 194.2 | 250.1 | 1370.7 | 2.07 ± 1.01 |
| mattcl-py | input-whyando | 20521.2 ± 649.6 | 19588.8 | 24435.4 | 51.14 ± 22.08 |
| mattcl-py | input-lanjian | 20601.4 ± 476.8 | 19488.8 | 22450.5 | 51.34 ± 22.14 |
| mattcl-py | input-mattcl | 20672.0 ± 653.8 | 19396.4 | 24371.1 | 51.52 ± 22.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|