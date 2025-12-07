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
| whyando | input-lanjian | 550.7 ± 163.2 | 0.0 | 1067.0 | 1.00 |
| whyando | input-mattcl | 557.3 ± 154.3 | 0.0 | 1020.6 | 1.01 ± 0.41 |
| mattcl | input-whyando | 563.9 ± 162.4 | 0.0 | 801.6 | 1.02 ± 0.42 |
| whyando | input-whyando | 570.5 ± 151.9 | 0.0 | 1058.7 | 1.04 ± 0.41 |
| mattcl | input-mattcl | 593.8 ± 173.6 | 0.0 | 1222.3 | 1.08 ± 0.45 |
| mattcl | input-lanjian | 598.2 ± 169.1 | 0.0 | 1230.9 | 1.09 ± 0.44 |
| kcen | input-mattcl | 933.3 ± 154.8 | 340.3 | 1489.0 | 1.69 ± 0.58 |
| kcen | input-lanjian | 937.9 ± 141.6 | 366.4 | 1447.6 | 1.70 ± 0.57 |
| kcen | input-whyando | 944.1 ± 141.4 | 358.5 | 1461.9 | 1.71 ± 0.57 |
| lanjian | input-mattcl | 8621.3 ± 72.9 | 8381.0 | 8814.2 | 15.65 ± 4.64 |
| lanjian | input-lanjian | 8622.6 ± 76.9 | 8420.9 | 8855.2 | 15.66 ± 4.64 |
| lanjian | input-whyando | 8673.7 ± 301.9 | 8387.2 | 11583.4 | 15.75 ± 4.70 |
| mattcl-py | input-lanjian | 21104.6 ± 614.3 | 20079.6 | 24392.1 | 38.32 ± 11.41 |
| mattcl-py | input-mattcl | 21147.4 ± 598.6 | 20237.7 | 23764.3 | 38.40 ± 11.43 |
| mattcl-py | input-whyando | 21329.3 ± 737.6 | 20404.8 | 24834.7 | 38.73 ± 11.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|