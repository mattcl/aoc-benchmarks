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
| whyando | input-lanjian | 305.8 ± 318.5 | 0.0 | 921.0 | 1.00 |
| whyando | input-mattcl | 627.0 ± 269.7 | 0.0 | 1219.3 | 2.05 ± 2.31 |
| kcen | input-mattcl | 649.7 ± 308.4 | 0.0 | 1492.2 | 2.12 ± 2.43 |
| whyando | input-whyando | 706.7 ± 135.6 | 190.5 | 1125.2 | 2.31 ± 2.45 |
| kcen | input-whyando | 794.1 ± 166.6 | 69.0 | 1286.5 | 2.60 ± 2.76 |
| kcen | input-lanjian | 825.7 ± 113.4 | 245.8 | 1245.1 | 2.70 ± 2.84 |
| mattcl | input-lanjian | 992.4 ± 158.6 | 306.6 | 1605.2 | 3.25 ± 3.42 |
| mattcl | input-mattcl | 1001.0 ± 149.0 | 533.7 | 1680.6 | 3.27 ± 3.44 |
| mattcl | input-whyando | 1008.3 ± 181.2 | 323.4 | 1684.9 | 3.30 ± 3.48 |
| lanjian | input-lanjian | 1256.1 ± 208.7 | 456.8 | 2079.8 | 4.11 ± 4.33 |
| lanjian | input-mattcl | 1271.7 ± 243.6 | 120.5 | 2104.3 | 4.16 ± 4.40 |
| lanjian | input-whyando | 1314.8 ± 231.8 | 472.1 | 2516.4 | 4.30 ± 4.54 |
| mattcl-py | input-whyando | 18260.6 ± 838.2 | 16693.3 | 21466.1 | 59.71 ± 62.24 |
| mattcl-py | input-mattcl | 18341.3 ± 735.4 | 17107.4 | 22087.8 | 59.97 ± 62.51 |
| mattcl-py | input-lanjian | 18368.7 ± 706.9 | 17386.3 | 21781.3 | 60.06 ± 62.60 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|