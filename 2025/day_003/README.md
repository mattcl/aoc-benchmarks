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
| whyando | input-whyando | 664.6 ± 162.9 | 0.0 | 1179.2 | 1.00 |
| whyando | input-mattcl | 669.2 ± 155.9 | 0.0 | 1336.6 | 1.01 ± 0.34 |
| whyando | input-lanjian | 704.5 ± 128.7 | 41.4 | 1151.5 | 1.06 ± 0.32 |
| kcen | input-lanjian | 957.7 ± 137.0 | 411.5 | 1459.9 | 1.44 ± 0.41 |
| kcen | input-whyando | 966.3 ± 161.4 | 124.2 | 1514.9 | 1.45 ± 0.43 |
| kcen | input-mattcl | 974.3 ± 165.5 | 424.6 | 1523.1 | 1.47 ± 0.44 |
| mattcl | input-lanjian | 1023.3 ± 127.8 | 499.1 | 1306.0 | 1.54 ± 0.42 |
| mattcl | input-mattcl | 1036.5 ± 175.7 | 477.5 | 1699.1 | 1.56 ± 0.46 |
| mattcl | input-whyando | 1067.5 ± 181.2 | 593.1 | 1824.6 | 1.61 ± 0.48 |
| lanjian | input-lanjian | 1371.8 ± 283.9 | 811.6 | 2506.8 | 2.06 ± 0.66 |
| lanjian | input-mattcl | 1387.8 ± 297.2 | 841.5 | 2612.1 | 2.09 ± 0.68 |
| lanjian | input-whyando | 1389.1 ± 261.5 | 831.5 | 2378.2 | 2.09 ± 0.65 |
| mattcl-py | input-lanjian | 20860.2 ± 829.0 | 19657.9 | 24513.0 | 31.39 ± 7.79 |
| mattcl-py | input-mattcl | 20878.1 ± 700.8 | 19437.3 | 24010.2 | 31.41 ± 7.77 |
| mattcl-py | input-whyando | 20966.6 ± 466.7 | 20102.8 | 23536.3 | 31.55 ± 7.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|