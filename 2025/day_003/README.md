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
| whyando | input-whyando | 682.5 ± 151.4 | 160.1 | 1086.7 | 1.00 |
| whyando | input-mattcl | 684.5 ± 140.0 | 134.7 | 1068.0 | 1.00 ± 0.30 |
| whyando | input-lanjian | 691.1 ± 153.1 | 111.8 | 1224.1 | 1.01 ± 0.32 |
| kcen | input-mattcl | 909.7 ± 137.4 | 172.6 | 1431.0 | 1.33 ± 0.36 |
| kcen | input-lanjian | 910.5 ± 149.5 | 183.5 | 1442.2 | 1.33 ± 0.37 |
| kcen | input-whyando | 951.2 ± 160.1 | 316.8 | 1522.3 | 1.39 ± 0.39 |
| mattcl | input-whyando | 1055.6 ± 168.5 | 401.0 | 1734.5 | 1.55 ± 0.42 |
| mattcl | input-lanjian | 1079.5 ± 183.3 | 329.3 | 1807.4 | 1.58 ± 0.44 |
| mattcl | input-mattcl | 1081.9 ± 200.0 | 439.4 | 1772.3 | 1.59 ± 0.46 |
| lanjian | input-mattcl | 1332.2 ± 290.4 | 814.2 | 2501.9 | 1.95 ± 0.61 |
| lanjian | input-whyando | 1364.9 ± 279.3 | 832.1 | 2557.2 | 2.00 ± 0.60 |
| lanjian | input-lanjian | 1369.7 ± 277.1 | 864.7 | 2718.9 | 2.01 ± 0.60 |
| mattcl-py | input-mattcl | 20914.6 ± 603.1 | 19865.2 | 24046.6 | 30.64 ± 6.85 |
| mattcl-py | input-lanjian | 20934.0 ± 575.9 | 19874.3 | 23712.4 | 30.67 ± 6.85 |
| mattcl-py | input-whyando | 21122.9 ± 635.9 | 19844.7 | 24274.3 | 30.95 ± 6.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|