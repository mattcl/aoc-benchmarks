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
| whyando | input-lanjian | 653.9 ± 159.2 | 0.0 | 1069.5 | 1.00 |
| whyando | input-mattcl | 690.0 ± 171.2 | 44.6 | 1304.0 | 1.06 ± 0.37 |
| whyando | input-whyando | 699.4 ± 144.4 | 29.1 | 1145.1 | 1.07 ± 0.34 |
| kcen | input-lanjian | 899.6 ± 178.3 | 0.0 | 1414.1 | 1.38 ± 0.43 |
| kcen | input-mattcl | 938.9 ± 165.9 | 437.2 | 1514.9 | 1.44 ± 0.43 |
| kcen | input-whyando | 951.3 ± 179.8 | 393.5 | 1666.1 | 1.45 ± 0.45 |
| mattcl | input-lanjian | 1038.4 ± 171.3 | 471.9 | 1640.2 | 1.59 ± 0.47 |
| mattcl | input-whyando | 1043.7 ± 192.2 | 354.8 | 1667.9 | 1.60 ± 0.49 |
| mattcl | input-mattcl | 1062.0 ± 202.2 | 105.4 | 1733.3 | 1.62 ± 0.50 |
| lanjian | input-lanjian | 1340.5 ± 295.9 | 835.8 | 2439.7 | 2.05 ± 0.67 |
| lanjian | input-mattcl | 1370.2 ± 279.2 | 867.9 | 2422.1 | 2.10 ± 0.67 |
| lanjian | input-whyando | 1389.8 ± 254.2 | 910.7 | 2365.8 | 2.13 ± 0.65 |
| mattcl-py | input-lanjian | 20970.7 ± 726.3 | 19672.5 | 24334.2 | 32.07 ± 7.88 |
| mattcl-py | input-mattcl | 21063.3 ± 757.4 | 19862.6 | 23826.8 | 32.21 ± 7.93 |
| mattcl-py | input-whyando | 21141.0 ± 696.4 | 20109.8 | 24043.8 | 32.33 ± 7.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|