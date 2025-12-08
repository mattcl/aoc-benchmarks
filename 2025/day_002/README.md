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
| whyando | input-mattcl | 386.1 ± 170.3 | 0.0 | 969.9 | 1.00 |
| whyando | input-whyando | 394.4 ± 162.2 | 0.0 | 900.8 | 1.02 ± 0.62 |
| whyando | input-lanjian | 411.0 ± 155.8 | 0.0 | 949.6 | 1.06 ± 0.62 |
| mattcl | input-mattcl | 693.4 ± 146.2 | 113.3 | 1079.7 | 1.80 ± 0.88 |
| mattcl | input-lanjian | 699.9 ± 148.5 | 96.5 | 1370.8 | 1.81 ± 0.89 |
| mattcl | input-whyando | 740.2 ± 153.0 | 136.6 | 1341.4 | 1.92 ± 0.93 |
| kcen | input-whyando | 768.1 ± 167.8 | 67.7 | 1213.2 | 1.99 ± 0.98 |
| kcen | input-lanjian | 800.4 ± 158.6 | 0.0 | 1268.7 | 2.07 ± 1.00 |
| lanjian | input-whyando | 831.1 ± 162.1 | 0.0 | 1329.9 | 2.15 ± 1.04 |
| lanjian | input-lanjian | 837.7 ± 136.0 | 290.9 | 1249.7 | 2.17 ± 1.02 |
| kcen | input-mattcl | 868.9 ± 198.5 | 244.7 | 1340.7 | 2.25 ± 1.12 |
| lanjian | input-mattcl | 883.1 ± 188.4 | 0.0 | 1492.7 | 2.29 ± 1.12 |
| mattcl-py | input-whyando | 20444.2 ± 528.1 | 19419.4 | 23221.2 | 52.95 ± 23.40 |
| mattcl-py | input-lanjian | 20740.4 ± 572.5 | 19588.5 | 23995.3 | 53.72 ± 23.75 |
| mattcl-py | input-mattcl | 20792.8 ± 727.6 | 19728.2 | 23837.6 | 53.86 ± 23.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|