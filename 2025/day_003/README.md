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
| whyando | input-mattcl | 499.8 ± 236.4 | 0.0 | 818.7 | 1.00 |
| mattcl | input-whyando | 542.4 ± 212.6 | 0.0 | 798.0 | 1.09 ± 0.67 |
| mattcl | input-mattcl | 546.6 ± 206.2 | 0.0 | 822.7 | 1.09 ± 0.66 |
| whyando | input-whyando | 561.2 ± 186.2 | 0.0 | 837.2 | 1.12 ± 0.65 |
| whyando | input-lanjian | 592.4 ± 156.6 | 0.0 | 826.2 | 1.19 ± 0.64 |
| mattcl | input-lanjian | 607.5 ± 186.1 | 0.0 | 860.8 | 1.22 ± 0.68 |
| kcen | input-lanjian | 949.2 ± 156.7 | 255.7 | 1157.2 | 1.90 ± 0.95 |
| kcen | input-mattcl | 960.8 ± 150.5 | 347.7 | 1153.4 | 1.92 ± 0.96 |
| kcen | input-whyando | 967.8 ± 154.3 | 0.0 | 1154.7 | 1.94 ± 0.97 |
| lanjian | input-whyando | 4054.4 ± 294.6 | 3212.2 | 4867.8 | 8.11 ± 3.88 |
| lanjian | input-lanjian | 4058.9 ± 296.6 | 3407.0 | 5020.4 | 8.12 ± 3.89 |
| lanjian | input-mattcl | 4061.4 ± 309.8 | 3352.1 | 4949.8 | 8.13 ± 3.89 |
| mattcl-py | input-mattcl | 21468.1 ± 714.0 | 20310.3 | 27976.1 | 42.95 ± 20.36 |
| mattcl-py | input-lanjian | 22969.2 ± 3578.8 | 20287.6 | 33149.6 | 45.96 ± 22.88 |
| mattcl-py | input-whyando | 23035.9 ± 3611.4 | 20561.5 | 33630.2 | 46.09 ± 22.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|