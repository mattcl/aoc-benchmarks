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
| whyando | input-mattcl | 453.0 ± 271.2 | 0.0 | 840.4 | 1.00 |
| whyando | input-whyando | 563.8 ± 194.0 | 0.0 | 845.2 | 1.24 ± 0.86 |
| whyando | input-lanjian | 564.4 ± 171.1 | 0.0 | 773.6 | 1.25 ± 0.84 |
| mattcl | input-mattcl | 569.7 ± 186.3 | 0.0 | 851.2 | 1.26 ± 0.86 |
| mattcl | input-whyando | 571.6 ± 157.2 | 0.0 | 785.3 | 1.26 ± 0.83 |
| mattcl | input-lanjian | 585.2 ± 168.5 | 0.0 | 815.4 | 1.29 ± 0.86 |
| kcen | input-whyando | 933.3 ± 162.5 | 311.3 | 1159.7 | 2.06 ± 1.28 |
| kcen | input-mattcl | 939.6 ± 154.0 | 0.0 | 1208.3 | 2.07 ± 1.29 |
| kcen | input-lanjian | 942.4 ± 222.2 | 0.0 | 1238.6 | 2.08 ± 1.34 |
| lanjian | input-whyando | 4041.7 ± 276.8 | 3459.2 | 5077.2 | 8.92 ± 5.38 |
| lanjian | input-mattcl | 4053.9 ± 311.5 | 3313.0 | 4942.2 | 8.95 ± 5.40 |
| lanjian | input-lanjian | 4080.1 ± 303.9 | 3111.9 | 4936.1 | 9.01 ± 5.43 |
| mattcl-py | input-mattcl | 21549.0 ± 733.5 | 20244.5 | 24885.2 | 47.57 ± 28.52 |
| mattcl-py | input-lanjian | 23039.0 ± 3572.7 | 20455.1 | 33322.9 | 50.85 ± 31.45 |
| mattcl-py | input-whyando | 23058.3 ± 3523.2 | 20288.0 | 35276.2 | 50.90 ± 31.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|