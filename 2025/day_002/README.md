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
| whyando | input-lanjian | 369.9 ± 197.3 | 0.0 | 658.6 | 1.00 |
| whyando | input-whyando | 394.8 ± 191.8 | 0.0 | 1119.0 | 1.07 ± 0.77 |
| kcen | input-mattcl | 599.6 ± 524.5 | 0.0 | 5989.0 | 1.62 ± 1.66 |
| whyando | input-mattcl | 629.0 ± 2117.3 | 0.0 | 19000.6 | 1.70 ± 5.79 |
| mattcl | input-whyando | 641.9 ± 162.8 | 0.0 | 917.4 | 1.74 ± 1.02 |
| lanjian | input-lanjian | 664.2 ± 187.2 | 0.0 | 872.9 | 1.80 ± 1.08 |
| mattcl | input-lanjian | 667.1 ± 173.2 | 0.0 | 937.0 | 1.80 ± 1.07 |
| lanjian | input-whyando | 679.8 ± 191.0 | 0.0 | 939.8 | 1.84 ± 1.11 |
| lanjian | input-mattcl | 683.4 ± 176.4 | 0.0 | 901.3 | 1.85 ± 1.09 |
| mattcl | input-mattcl | 702.6 ± 135.6 | 0.0 | 912.9 | 1.90 ± 1.08 |
| kcen | input-lanjian | 780.4 ± 170.0 | 10.9 | 1020.2 | 2.11 ± 1.22 |
| kcen | input-whyando | 1279.7 ± 3075.3 | 0.0 | 22324.1 | 3.46 ± 8.52 |
| mattcl-py | input-whyando | 20877.8 ± 399.3 | 20013.4 | 23294.1 | 56.44 ± 30.11 |
| mattcl-py | input-lanjian | 21065.2 ± 548.2 | 19941.1 | 23148.8 | 56.94 ± 30.40 |
| mattcl-py | input-mattcl | 21209.6 ± 598.4 | 20348.3 | 24098.2 | 57.33 ± 30.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|