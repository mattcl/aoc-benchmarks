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

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 0.6 ± 0.2 | 0.0 | 1.3 | 1.00 |
| whyando | input-lanjian | 0.6 ± 0.2 | 0.0 | 1.1 | 1.01 ± 0.47 |
| whyando | input-whyando | 0.6 ± 0.1 | 0.1 | 1.1 | 1.03 ± 0.44 |
| whyando | input-mattcl | 0.6 ± 0.1 | 0.1 | 1.1 | 1.04 ± 0.45 |
| mattcl | input-whyando | 0.6 ± 0.2 | 0.0 | 1.1 | 1.05 ± 0.47 |
| mattcl | input-mattcl | 0.6 ± 0.2 | 0.0 | 1.2 | 1.08 ± 0.47 |
| kcen | input-whyando | 1.0 ± 0.2 | 0.3 | 1.5 | 1.72 ± 0.67 |
| kcen | input-mattcl | 1.0 ± 0.2 | 0.4 | 1.6 | 1.77 ± 0.72 |
| kcen | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.7 | 1.78 ± 0.71 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.3 | 5.0 | 7.19 ± 2.58 |
| lanjian | input-lanjian | 4.1 ± 0.3 | 3.3 | 4.9 | 7.20 ± 2.58 |
| lanjian | input-whyando | 4.1 ± 0.3 | 3.2 | 5.1 | 7.28 ± 2.62 |
| mattcl-py | input-lanjian | 21.2 ± 0.7 | 20.0 | 24.7 | 37.53 ± 13.25 |
| mattcl-py | input-mattcl | 21.2 ± 0.7 | 19.9 | 24.3 | 37.54 ± 13.26 |
| mattcl-py | input-whyando | 21.3 ± 0.7 | 20.1 | 24.7 | 37.70 ± 13.31 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|