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
| whyando | input-mattcl | 562.7 ± 217.0 | 0.0 | 1108.3 | 1.00 |
| mattcl | input-whyando | 598.5 ± 185.7 | 0.0 | 1046.2 | 1.06 ± 0.53 |
| mattcl | input-lanjian | 598.9 ± 195.2 | 0.0 | 1204.8 | 1.06 ± 0.54 |
| whyando | input-lanjian | 605.3 ± 222.0 | 0.0 | 2990.6 | 1.08 ± 0.57 |
| whyando | input-whyando | 606.2 ± 152.3 | 0.0 | 1054.3 | 1.08 ± 0.50 |
| mattcl | input-mattcl | 621.3 ± 175.2 | 0.0 | 1106.6 | 1.10 ± 0.53 |
| kcen | input-whyando | 714.3 ± 334.5 | 0.0 | 1368.4 | 1.27 ± 0.77 |
| kcen | input-mattcl | 908.6 ± 149.3 | 240.3 | 1377.1 | 1.61 ± 0.68 |
| kcen | input-lanjian | 928.7 ± 144.2 | 424.2 | 1557.9 | 1.65 ± 0.69 |
| lanjian | input-mattcl | 945.2 ± 153.2 | 297.9 | 1553.9 | 1.68 ± 0.70 |
| lanjian | input-lanjian | 950.5 ± 128.8 | 238.7 | 1377.4 | 1.69 ± 0.69 |
| lanjian | input-whyando | 956.0 ± 178.7 | 24.3 | 1518.9 | 1.70 ± 0.73 |
| mattcl-py | input-mattcl | 18335.3 ± 561.6 | 16894.8 | 21215.6 | 32.59 ± 12.61 |
| mattcl-py | input-whyando | 18477.6 ± 592.7 | 17540.2 | 21556.4 | 32.84 ± 12.71 |
| mattcl-py | input-lanjian | 18501.7 ± 819.9 | 17170.4 | 21987.1 | 32.88 ± 12.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|