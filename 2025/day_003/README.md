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
| whyando | input-lanjian | 564.9 ± 152.0 | 0.0 | 1064.6 | 1.00 |
| whyando | input-mattcl | 574.0 ± 130.6 | 112.5 | 990.7 | 1.02 ± 0.36 |
| whyando | input-whyando | 575.4 ± 140.5 | 30.2 | 1098.2 | 1.02 ± 0.37 |
| mattcl | input-whyando | 808.9 ± 149.3 | 17.9 | 1373.4 | 1.43 ± 0.47 |
| mattcl | input-lanjian | 817.4 ± 153.9 | 283.1 | 1620.8 | 1.45 ± 0.48 |
| mattcl | input-mattcl | 834.8 ± 159.3 | 269.3 | 1436.9 | 1.48 ± 0.49 |
| kcen | input-mattcl | 966.6 ± 161.2 | 0.0 | 1450.5 | 1.71 ± 0.54 |
| kcen | input-lanjian | 969.0 ± 190.4 | 0.0 | 1600.7 | 1.72 ± 0.57 |
| kcen | input-whyando | 978.9 ± 137.9 | 458.8 | 1693.3 | 1.73 ± 0.53 |
| lanjian | input-mattcl | 8622.9 ± 75.2 | 8436.8 | 8796.2 | 15.26 ± 4.11 |
| lanjian | input-whyando | 8643.1 ± 153.6 | 8425.6 | 10273.4 | 15.30 ± 4.13 |
| lanjian | input-lanjian | 8649.4 ± 200.8 | 8374.6 | 10776.9 | 15.31 ± 4.13 |
| mattcl-py | input-mattcl | 21137.7 ± 522.6 | 20232.1 | 23847.8 | 37.42 ± 10.11 |
| mattcl-py | input-lanjian | 21190.3 ± 525.4 | 20126.8 | 23915.7 | 37.51 ± 10.13 |
| mattcl-py | input-whyando | 21357.2 ± 552.5 | 20158.9 | 24707.9 | 37.81 ± 10.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|