# Day 1 benchmarks

[link to problem](https://adventofcode.com/2025/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 714.4 ± 124.7 | 169.1 | 1079.8 | 1.00 |
| whyando | input-whyando | 727.9 ± 126.3 | 265.2 | 1161.5 | 1.02 ± 0.25 |
| whyando | input-mattcl | 741.6 ± 141.5 | 0.0 | 1108.4 | 1.04 ± 0.27 |
| kcen | input-whyando | 829.0 ± 141.4 | 309.0 | 1294.2 | 1.16 ± 0.28 |
| kcen | input-mattcl | 829.5 ± 151.8 | 260.7 | 1306.4 | 1.16 ± 0.29 |
| kcen | input-lanjian | 848.4 ± 148.8 | 369.8 | 1463.2 | 1.19 ± 0.29 |
| mattcl | input-mattcl | 1009.4 ± 203.4 | 286.3 | 1725.5 | 1.41 ± 0.38 |
| mattcl | input-whyando | 1029.0 ± 185.1 | 460.4 | 1715.9 | 1.44 ± 0.36 |
| mattcl | input-lanjian | 1052.0 ± 195.8 | 282.5 | 1723.5 | 1.47 ± 0.38 |
| lanjian | input-whyando | 1309.0 ± 196.1 | 487.3 | 2535.3 | 1.83 ± 0.42 |
| lanjian | input-mattcl | 1323.8 ± 240.5 | 135.7 | 2126.4 | 1.85 ± 0.47 |
| lanjian | input-lanjian | 1377.7 ± 178.9 | 619.3 | 2028.5 | 1.93 ± 0.42 |
| mattcl-py | input-lanjian | 18205.6 ± 622.6 | 16852.6 | 21317.2 | 25.48 ± 4.53 |
| mattcl-py | input-mattcl | 18268.5 ± 734.9 | 17279.3 | 21770.7 | 25.57 ± 4.58 |
| mattcl-py | input-whyando | 18277.3 ± 823.2 | 17229.3 | 21847.5 | 25.58 ± 4.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|