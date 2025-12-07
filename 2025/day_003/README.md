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
| mattcl | input-whyando | 505.2 ± 186.2 | 0.0 | 1066.0 | 1.00 |
| whyando | input-lanjian | 514.7 ± 168.3 | 0.0 | 1063.0 | 1.02 ± 0.50 |
| whyando | input-mattcl | 526.9 ± 160.8 | 0.0 | 936.8 | 1.04 ± 0.50 |
| mattcl | input-mattcl | 548.6 ± 162.4 | 0.0 | 1155.1 | 1.09 ± 0.51 |
| mattcl | input-lanjian | 550.9 ± 149.6 | 0.0 | 1158.2 | 1.09 ± 0.50 |
| whyando | input-whyando | 551.7 ± 177.4 | 0.0 | 1014.6 | 1.09 ± 0.53 |
| kcen | input-whyando | 907.0 ± 166.2 | 273.9 | 1501.9 | 1.80 ± 0.74 |
| kcen | input-lanjian | 936.6 ± 141.5 | 459.1 | 1480.6 | 1.85 ± 0.74 |
| kcen | input-mattcl | 953.1 ± 190.8 | 9.9 | 1714.3 | 1.89 ± 0.79 |
| lanjian | input-mattcl | 1345.4 ± 280.2 | 794.7 | 2590.3 | 2.66 ± 1.13 |
| lanjian | input-lanjian | 1368.6 ± 275.6 | 813.9 | 2446.9 | 2.71 ± 1.14 |
| lanjian | input-whyando | 1413.6 ± 350.6 | 808.4 | 4315.4 | 2.80 ± 1.24 |
| mattcl-py | input-mattcl | 21212.5 ± 811.5 | 19890.5 | 24825.9 | 41.99 ± 15.56 |
| mattcl-py | input-whyando | 21228.4 ± 659.8 | 20309.3 | 24301.4 | 42.02 ± 15.54 |
| mattcl-py | input-lanjian | 21237.1 ± 638.3 | 20242.4 | 24082.7 | 42.04 ± 15.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|