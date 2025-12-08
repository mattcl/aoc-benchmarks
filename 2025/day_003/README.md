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
| mattcl | input-mattcl | 517.6 ± 189.9 | 0.0 | 1051.4 | 1.00 |
| whyando | input-mattcl | 533.0 ± 157.4 | 0.0 | 1015.3 | 1.03 ± 0.48 |
| mattcl | input-whyando | 539.9 ± 196.3 | 0.0 | 1206.5 | 1.04 ± 0.54 |
| whyando | input-whyando | 547.9 ± 153.4 | 28.4 | 1021.2 | 1.06 ± 0.49 |
| whyando | input-lanjian | 550.8 ± 157.5 | 0.0 | 900.7 | 1.06 ± 0.49 |
| mattcl | input-lanjian | 558.2 ± 163.3 | 30.7 | 1161.6 | 1.08 ± 0.51 |
| kcen | input-lanjian | 903.1 ± 161.2 | 207.1 | 1477.5 | 1.74 ± 0.71 |
| kcen | input-mattcl | 933.6 ± 189.2 | 64.9 | 1538.6 | 1.80 ± 0.76 |
| kcen | input-whyando | 944.8 ± 199.8 | 87.8 | 1601.1 | 1.83 ± 0.77 |
| lanjian | input-whyando | 8635.6 ± 131.3 | 8396.2 | 9440.5 | 16.68 ± 6.12 |
| lanjian | input-mattcl | 8646.2 ± 207.0 | 8446.2 | 11052.6 | 16.70 ± 6.14 |
| lanjian | input-lanjian | 8652.6 ± 241.6 | 8294.9 | 11186.2 | 16.72 ± 6.15 |
| mattcl-py | input-whyando | 21219.5 ± 521.1 | 19865.5 | 22780.2 | 40.99 ± 15.07 |
| mattcl-py | input-lanjian | 21279.2 ± 651.9 | 19900.1 | 25105.7 | 41.11 ± 15.13 |
| mattcl-py | input-mattcl | 21292.2 ± 525.2 | 20214.0 | 23074.5 | 41.13 ± 15.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|