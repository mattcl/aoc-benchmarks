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
| whyando | input-whyando | 453.7 ± 338.0 | 0.0 | 903.2 | 1.00 |
| mattcl | input-lanjian | 660.2 ± 212.6 | 0.0 | 980.8 | 1.46 ± 1.18 |
| whyando | input-lanjian | 686.1 ± 206.0 | 0.0 | 912.7 | 1.51 ± 1.21 |
| whyando | input-mattcl | 696.6 ± 173.0 | 0.0 | 926.5 | 1.54 ± 1.21 |
| mattcl | input-mattcl | 707.3 ± 186.1 | 97.7 | 999.9 | 1.56 ± 1.23 |
| kcen | input-lanjian | 847.6 ± 412.8 | 34.5 | 2960.4 | 1.87 ± 1.66 |
| mattcl | input-whyando | 960.5 ± 2327.0 | 0.0 | 15242.7 | 2.12 ± 5.37 |
| kcen | input-whyando | 1095.1 ± 154.5 | 494.7 | 1361.2 | 2.41 ± 1.83 |
| kcen | input-mattcl | 1118.4 ± 100.1 | 616.6 | 1319.2 | 2.47 ± 1.85 |
| lanjian | input-mattcl | 8886.0 ± 130.0 | 8627.0 | 9572.8 | 19.59 ± 14.59 |
| lanjian | input-whyando | 8935.6 ± 254.9 | 8654.5 | 11752.0 | 19.69 ± 14.68 |
| lanjian | input-lanjian | 9011.3 ± 337.1 | 8684.8 | 12905.5 | 19.86 ± 14.81 |
| mattcl-py | input-mattcl | 21614.7 ± 552.6 | 20354.7 | 24440.8 | 47.64 ± 35.51 |
| mattcl-py | input-whyando | 22893.6 ± 3998.1 | 20855.3 | 42345.2 | 50.46 ± 38.61 |
| mattcl-py | input-lanjian | 23146.4 ± 3794.9 | 20447.9 | 38369.6 | 51.02 ± 38.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|