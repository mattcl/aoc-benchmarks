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
| whyando | input-lanjian | 514.4 ± 155.1 | 0.0 | 1010.0 | 1.00 |
| whyando | input-mattcl | 519.8 ± 174.3 | 0.0 | 1126.3 | 1.01 ± 0.46 |
| whyando | input-whyando | 541.5 ± 150.8 | 0.0 | 1030.4 | 1.05 ± 0.43 |
| kcen | input-lanjian | 763.7 ± 131.5 | 0.0 | 1206.1 | 1.48 ± 0.52 |
| kcen | input-whyando | 775.2 ± 135.5 | 123.2 | 1337.3 | 1.51 ± 0.53 |
| kcen | input-mattcl | 792.8 ± 146.7 | 286.7 | 1379.7 | 1.54 ± 0.55 |
| mattcl | input-whyando | 933.9 ± 119.3 | 357.4 | 1457.2 | 1.82 ± 0.59 |
| mattcl | input-mattcl | 967.8 ± 183.2 | 274.6 | 1602.6 | 1.88 ± 0.67 |
| mattcl | input-lanjian | 995.0 ± 154.3 | 390.2 | 1596.5 | 1.93 ± 0.66 |
| lanjian | input-mattcl | 1039.4 ± 185.9 | 448.9 | 2389.3 | 2.02 ± 0.71 |
| lanjian | input-whyando | 1065.6 ± 168.5 | 551.2 | 1769.0 | 2.07 ± 0.71 |
| lanjian | input-lanjian | 1075.9 ± 172.5 | 433.6 | 1840.8 | 2.09 ± 0.71 |
| mattcl-py | input-whyando | 20348.6 ± 771.8 | 18765.1 | 22920.4 | 39.56 ± 12.02 |
| mattcl-py | input-lanjian | 20435.0 ± 646.4 | 19013.6 | 23057.8 | 39.73 ± 12.04 |
| mattcl-py | input-mattcl | 20459.1 ± 592.1 | 19370.2 | 23671.6 | 39.77 ± 12.05 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|