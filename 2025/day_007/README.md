# Day 7 benchmarks

[link to problem](https://adventofcode.com/2025/day/7)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 7)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 374.5 ± 175.6 | 0.0 | 1090.4 | 1.00 |
| whyando | input-whyando | 379.8 ± 147.4 | 0.0 | 910.6 | 1.01 ± 0.62 |
| mattcl | input-mattcl | 389.1 ± 157.1 | 0.0 | 902.0 | 1.04 ± 0.64 |
| whyando | input-lanjian | 389.8 ± 178.2 | 0.0 | 935.7 | 1.04 ± 0.68 |
| mattcl | input-whyando | 395.0 ± 168.1 | 0.0 | 928.4 | 1.05 ± 0.67 |
| mattcl | input-lanjian | 410.8 ± 172.8 | 0.0 | 1019.0 | 1.10 ± 0.69 |
| lanjian | input-mattcl | 596.8 ± 248.9 | 0.0 | 1101.1 | 1.59 ± 1.00 |
| kcen | input-mattcl | 649.5 ± 335.9 | 0.0 | 1409.9 | 1.73 ± 1.21 |
| lanjian | input-whyando | 728.6 ± 128.4 | 302.2 | 1459.8 | 1.95 ± 0.97 |
| lanjian | input-lanjian | 785.2 ± 193.0 | 0.0 | 1454.4 | 2.10 ± 1.11 |
| kcen | input-whyando | 884.0 ± 164.1 | 106.6 | 1452.9 | 2.36 ± 1.19 |
| kcen | input-lanjian | 969.5 ± 182.9 | 381.5 | 1869.4 | 2.59 ± 1.31 |
| mattcl-py | input-lanjian | 17491.4 ± 697.8 | 16189.2 | 20892.5 | 46.71 ± 21.98 |
| mattcl-py | input-whyando | 17580.2 ± 628.0 | 16589.8 | 20704.7 | 46.94 ± 22.08 |
| mattcl-py | input-mattcl | 17620.3 ± 616.9 | 16829.9 | 20786.1 | 47.05 ± 22.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|