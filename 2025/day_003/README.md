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
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 1.0 | 1.00 |
| mattcl | input-lanjian | 0.6 ± 0.2 | 0.0 | 1.2 | 1.06 ± 0.52 |
| mattcl | input-whyando | 0.6 ± 0.2 | 0.0 | 1.8 | 1.06 ± 0.55 |
| whyando | input-mattcl | 0.6 ± 0.2 | 0.0 | 2.8 | 1.09 ± 0.57 |
| mattcl | input-mattcl | 0.6 ± 0.1 | 0.1 | 0.8 | 1.10 ± 0.46 |
| whyando | input-whyando | 0.6 ± 0.2 | 0.0 | 1.1 | 1.11 ± 0.50 |
| kcen | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.5 | 1.72 ± 0.70 |
| kcen | input-whyando | 1.0 ± 0.1 | 0.4 | 1.5 | 1.78 ± 0.69 |
| kcen | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.8 | 1.88 ± 0.75 |
| lanjian | input-whyando | 4.1 ± 0.3 | 3.2 | 5.0 | 7.59 ± 2.77 |
| lanjian | input-lanjian | 4.1 ± 0.3 | 3.4 | 5.1 | 7.62 ± 2.78 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.5 | 4.9 | 7.70 ± 2.80 |
| mattcl-py | input-mattcl | 21.2 ± 0.7 | 19.9 | 24.4 | 39.43 ± 14.15 |
| mattcl-py | input-whyando | 21.2 ± 0.6 | 20.4 | 24.4 | 39.56 ± 14.18 |
| mattcl-py | input-lanjian | 21.3 ± 0.8 | 20.1 | 24.7 | 39.74 ± 14.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|