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
| mattcl | input-mattcl | 553.7 ± 164.6 | 0.0 | 1062.1 | 1.00 |
| mattcl | input-lanjian | 569.6 ± 144.9 | 0.0 | 1038.4 | 1.03 ± 0.40 |
| mattcl | input-whyando | 587.0 ± 179.3 | 0.0 | 1293.7 | 1.06 ± 0.45 |
| whyando | input-lanjian | 846.4 ± 352.5 | 0.0 | 1729.8 | 1.53 ± 0.78 |
| kcen | input-mattcl | 884.6 ± 253.8 | 0.0 | 1635.7 | 1.60 ± 0.66 |
| kcen | input-lanjian | 937.0 ± 165.4 | 0.0 | 1595.2 | 1.69 ± 0.59 |
| kcen | input-whyando | 962.1 ± 150.1 | 400.9 | 1503.0 | 1.74 ± 0.58 |
| whyando | input-whyando | 1023.3 ± 148.3 | 480.6 | 1736.8 | 1.85 ± 0.61 |
| whyando | input-mattcl | 1104.6 ± 190.7 | 497.4 | 1725.3 | 1.99 ± 0.69 |
| lanjian | input-whyando | 8619.0 ± 72.9 | 8450.4 | 8894.4 | 15.57 ± 4.63 |
| lanjian | input-lanjian | 8619.0 ± 80.8 | 8430.2 | 8849.1 | 15.57 ± 4.63 |
| lanjian | input-mattcl | 8632.5 ± 83.3 | 8475.0 | 9184.3 | 15.59 ± 4.64 |
| mattcl-py | input-lanjian | 21142.8 ± 601.6 | 20261.6 | 24336.9 | 38.18 ± 11.41 |
| mattcl-py | input-mattcl | 21203.9 ± 761.4 | 19905.3 | 24190.9 | 38.30 ± 11.47 |
| mattcl-py | input-whyando | 21280.8 ± 543.8 | 20274.5 | 24005.8 | 38.43 ± 11.47 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|