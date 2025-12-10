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
| whyando | input-lanjian | 499.8 ± 211.7 | 0.0 | 1470.4 | 1.00 |
| whyando | input-mattcl | 500.0 ± 159.6 | 0.0 | 833.9 | 1.00 ± 0.53 |
| mattcl | input-whyando | 511.8 ± 179.2 | 0.0 | 1045.6 | 1.02 ± 0.56 |
| mattcl | input-lanjian | 522.7 ± 167.7 | 0.0 | 945.2 | 1.05 ± 0.56 |
| mattcl | input-mattcl | 529.6 ± 167.4 | 0.0 | 1183.0 | 1.06 ± 0.56 |
| whyando | input-whyando | 559.6 ± 174.8 | 0.0 | 1221.1 | 1.12 ± 0.59 |
| kcen | input-whyando | 905.8 ± 158.5 | 273.0 | 1630.9 | 1.81 ± 0.83 |
| kcen | input-lanjian | 916.5 ± 140.5 | 347.8 | 1473.9 | 1.83 ± 0.83 |
| kcen | input-mattcl | 931.3 ± 203.4 | 21.8 | 1806.8 | 1.86 ± 0.89 |
| lanjian | input-mattcl | 4016.0 ± 311.6 | 3266.6 | 5001.4 | 8.04 ± 3.46 |
| lanjian | input-lanjian | 4045.0 ± 309.0 | 3351.5 | 5070.4 | 8.09 ± 3.48 |
| lanjian | input-whyando | 4063.0 ± 326.0 | 3215.0 | 5144.8 | 8.13 ± 3.50 |
| mattcl-py | input-lanjian | 21308.7 ± 868.0 | 20116.8 | 27282.6 | 42.64 ± 18.14 |
| mattcl-py | input-mattcl | 21313.3 ± 847.6 | 20193.8 | 24770.5 | 42.65 ± 18.14 |
| mattcl-py | input-whyando | 21368.2 ± 848.9 | 20124.8 | 24931.9 | 42.76 ± 18.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|