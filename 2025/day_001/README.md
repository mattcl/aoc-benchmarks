# Day 1 benchmarks

[link to problem](https://adventofcode.com/2025/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 631.2 ± 162.5 | 0.0 | 1044.2 | 1.00 |
| whyando | input-lanjian | 649.2 ± 154.4 | 0.0 | 1363.9 | 1.03 ± 0.36 |
| whyando | input-whyando | 664.7 ± 161.2 | 7.6 | 1305.0 | 1.05 ± 0.37 |
| kcen | input-lanjian | 841.8 ± 175.6 | 0.0 | 1392.5 | 1.33 ± 0.44 |
| kcen | input-whyando | 863.0 ± 155.3 | 263.7 | 1633.4 | 1.37 ± 0.43 |
| kcen | input-mattcl | 927.2 ± 199.7 | 487.5 | 2360.4 | 1.47 ± 0.49 |
| mattcl | input-lanjian | 1018.8 ± 196.7 | 81.2 | 1775.2 | 1.61 ± 0.52 |
| mattcl | input-mattcl | 1043.7 ± 177.5 | 461.3 | 1731.3 | 1.65 ± 0.51 |
| mattcl | input-whyando | 1061.0 ± 160.4 | 407.3 | 1713.8 | 1.68 ± 0.50 |
| lanjian | input-lanjian | 1345.2 ± 202.8 | 636.2 | 2071.7 | 2.13 ± 0.64 |
| lanjian | input-whyando | 1354.1 ± 168.4 | 676.3 | 1709.4 | 2.15 ± 0.61 |
| lanjian | input-mattcl | 1360.9 ± 226.6 | 528.7 | 2692.0 | 2.16 ± 0.66 |
| mattcl-py | input-lanjian | 18297.0 ± 752.1 | 17192.1 | 21600.0 | 28.99 ± 7.56 |
| mattcl-py | input-mattcl | 18365.7 ± 759.0 | 17346.3 | 21548.6 | 29.10 ± 7.59 |
| mattcl-py | input-whyando | 18374.7 ± 743.1 | 16777.7 | 21231.9 | 29.11 ± 7.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|