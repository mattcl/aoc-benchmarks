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
| mattcl | input-mattcl | 0.6 ± 0.2 | 0.0 | 1.1 | 1.00 |
| mattcl | input-whyando | 0.6 ± 0.1 | 0.0 | 0.9 | 1.01 ± 0.37 |
| mattcl | input-lanjian | 0.6 ± 0.2 | 0.0 | 1.1 | 1.07 ± 0.41 |
| kcen | input-mattcl | 0.9 ± 0.2 | 0.0 | 1.6 | 1.66 ± 0.55 |
| kcen | input-whyando | 1.0 ± 0.2 | 0.0 | 1.6 | 1.73 ± 0.58 |
| kcen | input-lanjian | 1.0 ± 0.2 | 0.1 | 1.6 | 1.76 ± 0.58 |
| whyando | input-whyando | 1.0 ± 0.1 | 0.4 | 1.3 | 1.80 ± 0.57 |
| whyando | input-mattcl | 1.1 ± 0.2 | 0.1 | 1.7 | 1.89 ± 0.61 |
| whyando | input-lanjian | 1.1 ± 0.2 | 0.6 | 2.0 | 1.98 ± 0.65 |
| lanjian | input-whyando | 1.4 ± 0.3 | 0.9 | 2.5 | 2.45 ± 0.84 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.9 | 2.6 | 2.46 ± 0.80 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.5 | 2.46 ± 0.82 |
| mattcl-py | input-lanjian | 21.1 ± 0.7 | 20.0 | 24.4 | 37.03 ± 10.54 |
| mattcl-py | input-mattcl | 21.2 ± 0.8 | 19.6 | 24.7 | 37.07 ± 10.57 |
| mattcl-py | input-whyando | 21.2 ± 0.6 | 20.3 | 23.9 | 37.17 ± 10.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|