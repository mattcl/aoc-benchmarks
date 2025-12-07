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
| mattcl | input-lanjian | 355.3 ± 264.7 | 0.0 | 845.6 | 1.00 |
| whyando | input-mattcl | 488.7 ± 184.0 | 0.0 | 903.3 | 1.38 ± 1.15 |
| mattcl | input-mattcl | 514.4 ± 208.5 | 0.0 | 771.4 | 1.45 ± 1.23 |
| whyando | input-lanjian | 544.0 ± 178.9 | 0.0 | 799.7 | 1.53 ± 1.25 |
| whyando | input-whyando | 545.0 ± 136.8 | 36.0 | 917.7 | 1.53 ± 1.21 |
| mattcl | input-whyando | 554.9 ± 166.6 | 0.0 | 787.1 | 1.56 ± 1.25 |
| kcen | input-mattcl | 852.1 ± 492.7 | 0.0 | 6415.5 | 2.40 ± 2.26 |
| kcen | input-lanjian | 921.1 ± 161.6 | 222.2 | 1194.6 | 2.59 ± 1.98 |
| kcen | input-whyando | 932.9 ± 134.1 | 465.9 | 1413.6 | 2.63 ± 1.99 |
| lanjian | input-lanjian | 8795.8 ± 148.7 | 8513.9 | 9516.4 | 24.76 ± 18.45 |
| lanjian | input-whyando | 8865.0 ± 287.0 | 8362.6 | 11744.7 | 24.95 ± 18.61 |
| lanjian | input-mattcl | 11697.0 ± 8966.3 | 8708.3 | 62951.6 | 32.92 ± 35.19 |
| mattcl-py | input-whyando | 21328.2 ± 702.8 | 20077.5 | 24479.4 | 60.03 ± 44.77 |
| mattcl-py | input-lanjian | 21568.2 ± 571.3 | 20562.3 | 24227.5 | 60.70 ± 45.25 |
| mattcl-py | input-mattcl | 21964.4 ± 687.5 | 20265.5 | 24905.8 | 61.82 ± 46.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|