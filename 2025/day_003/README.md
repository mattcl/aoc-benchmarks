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
| whyando | input-whyando | 556.1 ± 161.8 | 0.0 | 1240.8 | 1.00 |
| whyando | input-lanjian | 558.1 ± 168.0 | 0.0 | 1037.2 | 1.00 ± 0.42 |
| whyando | input-mattcl | 577.4 ± 152.3 | 0.0 | 1126.9 | 1.04 ± 0.41 |
| mattcl | input-mattcl | 772.8 ± 145.8 | 0.0 | 1080.6 | 1.39 ± 0.48 |
| mattcl | input-whyando | 775.6 ± 140.3 | 305.8 | 1235.5 | 1.39 ± 0.48 |
| mattcl | input-lanjian | 787.7 ± 135.6 | 110.1 | 1202.7 | 1.42 ± 0.48 |
| kcen | input-whyando | 928.0 ± 158.3 | 0.0 | 1410.2 | 1.67 ± 0.56 |
| kcen | input-lanjian | 943.1 ± 193.0 | 0.0 | 1545.6 | 1.70 ± 0.60 |
| kcen | input-mattcl | 950.9 ± 142.1 | 386.0 | 1489.5 | 1.71 ± 0.56 |
| lanjian | input-whyando | 8627.0 ± 73.4 | 8460.0 | 8862.6 | 15.51 ± 4.52 |
| lanjian | input-lanjian | 8627.9 ± 82.5 | 8439.2 | 8983.9 | 15.52 ± 4.52 |
| lanjian | input-mattcl | 8630.1 ± 85.7 | 8407.2 | 9153.1 | 15.52 ± 4.52 |
| mattcl-py | input-lanjian | 21128.9 ± 573.6 | 19897.7 | 23814.7 | 38.00 ± 11.10 |
| mattcl-py | input-mattcl | 21135.9 ± 524.2 | 20075.1 | 24163.2 | 38.01 ± 11.10 |
| mattcl-py | input-whyando | 21380.3 ± 666.0 | 20192.5 | 24787.4 | 38.45 ± 11.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|