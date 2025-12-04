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
| whyando | input-lanjian | 652.6 ± 158.1 | 0.0 | 1105.5 | 1.00 |
| whyando | input-mattcl | 662.4 ± 119.7 | 197.1 | 892.1 | 1.01 ± 0.31 |
| whyando | input-whyando | 674.5 ± 143.4 | 0.0 | 1068.2 | 1.03 ± 0.33 |
| kcen | input-mattcl | 920.5 ± 121.6 | 493.3 | 1380.8 | 1.41 ± 0.39 |
| kcen | input-whyando | 925.4 ± 167.2 | 0.0 | 1453.6 | 1.42 ± 0.43 |
| kcen | input-lanjian | 972.1 ± 186.1 | 263.9 | 1691.4 | 1.49 ± 0.46 |
| mattcl | input-lanjian | 1041.9 ± 233.9 | 0.0 | 1899.9 | 1.60 ± 0.53 |
| mattcl | input-mattcl | 1043.5 ± 182.1 | 350.9 | 1746.0 | 1.60 ± 0.48 |
| mattcl | input-whyando | 1097.7 ± 212.7 | 509.0 | 1814.1 | 1.68 ± 0.52 |
| lanjian | input-lanjian | 1348.1 ± 305.3 | 820.0 | 2507.9 | 2.07 ± 0.69 |
| lanjian | input-whyando | 1354.2 ± 264.5 | 830.6 | 2436.2 | 2.08 ± 0.65 |
| lanjian | input-mattcl | 1354.4 ± 291.5 | 821.8 | 2428.2 | 2.08 ± 0.67 |
| mattcl-py | input-lanjian | 20845.2 ± 588.1 | 20032.9 | 23841.2 | 31.94 ± 7.79 |
| mattcl-py | input-mattcl | 20896.7 ± 660.2 | 19685.5 | 23975.6 | 32.02 ± 7.82 |
| mattcl-py | input-whyando | 21108.3 ± 629.7 | 20194.7 | 24281.1 | 32.34 ± 7.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|