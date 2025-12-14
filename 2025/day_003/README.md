# Day 3 benchmarks

[link to problem](https://adventofcode.com/2025/day/3)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 3)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 197.6 ± 237.4 | 0.0 | 1073.7 | 1.00 |
| mattcl | input-mattcl | 548.0 ± 177.1 | 0.0 | 971.6 | 2.77 ± 3.45 |
| whyando | input-lanjian | 561.2 ± 181.7 | 0.0 | 958.6 | 2.84 ± 3.53 |
| mattcl | input-lanjian | 576.3 ± 157.2 | 0.0 | 1039.3 | 2.92 ± 3.59 |
| whyando | input-whyando | 588.7 ± 173.5 | 0.0 | 1251.9 | 2.98 ± 3.68 |
| mattcl | input-whyando | 592.8 ± 152.2 | 0.0 | 946.5 | 3.00 ± 3.69 |
| kcen | input-whyando | 754.4 ± 285.8 | 0.0 | 1409.8 | 3.82 ± 4.81 |
| kcen | input-mattcl | 939.4 ± 194.6 | 327.8 | 1524.1 | 4.75 ± 5.79 |
| kcen | input-lanjian | 966.2 ± 171.3 | 357.8 | 1550.0 | 4.89 ± 5.94 |
| lanjian | input-whyando | 4089.3 ± 336.2 | 3300.5 | 5228.4 | 20.69 ± 24.92 |
| lanjian | input-lanjian | 4125.9 ± 304.2 | 3366.7 | 5082.2 | 20.88 ± 25.13 |
| lanjian | input-mattcl | 4134.5 ± 297.8 | 3392.8 | 5173.4 | 20.92 ± 25.18 |
| mattcl-py | input-lanjian | 21126.4 ± 649.1 | 20013.8 | 24923.9 | 106.90 ± 128.47 |
| mattcl-py | input-whyando | 21301.5 ± 497.2 | 20300.9 | 24339.3 | 107.79 ± 129.52 |
| mattcl-py | input-mattcl | 21439.1 ± 997.9 | 20313.2 | 29617.8 | 108.49 ± 130.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|