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
| whyando | input-mattcl | 675.7 ± 156.6 | 123.1 | 1138.1 | 1.00 |
| whyando | input-whyando | 676.6 ± 141.2 | 222.3 | 1248.9 | 1.00 ± 0.31 |
| whyando | input-lanjian | 703.9 ± 182.0 | 22.9 | 1301.5 | 1.04 ± 0.36 |
| kcen | input-mattcl | 907.4 ± 153.8 | 320.4 | 1478.5 | 1.34 ± 0.39 |
| kcen | input-lanjian | 921.0 ± 139.7 | 355.6 | 1194.7 | 1.36 ± 0.38 |
| kcen | input-whyando | 954.4 ± 152.8 | 255.9 | 1477.9 | 1.41 ± 0.40 |
| mattcl | input-whyando | 1051.1 ± 151.2 | 518.0 | 1702.7 | 1.56 ± 0.42 |
| mattcl | input-mattcl | 1063.4 ± 221.7 | 464.6 | 2663.5 | 1.57 ± 0.49 |
| mattcl | input-lanjian | 1068.5 ± 198.9 | 530.1 | 1954.1 | 1.58 ± 0.47 |
| lanjian | input-whyando | 1362.1 ± 283.2 | 803.1 | 2564.9 | 2.02 ± 0.63 |
| lanjian | input-mattcl | 1380.1 ± 273.8 | 830.3 | 2429.9 | 2.04 ± 0.62 |
| lanjian | input-lanjian | 1392.3 ± 275.3 | 849.8 | 2442.8 | 2.06 ± 0.63 |
| mattcl-py | input-mattcl | 21047.7 ± 502.7 | 19870.7 | 23561.4 | 31.15 ± 7.26 |
| mattcl-py | input-lanjian | 21074.9 ± 567.4 | 20052.7 | 23985.3 | 31.19 ± 7.28 |
| mattcl-py | input-whyando | 21236.4 ± 628.9 | 20297.0 | 24636.7 | 31.43 ± 7.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|