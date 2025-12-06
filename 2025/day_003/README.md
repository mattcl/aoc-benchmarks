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
| whyando | input-whyando | 657.9 ± 178.6 | 0.0 | 1023.4 | 1.00 |
| whyando | input-lanjian | 673.0 ± 139.8 | 54.3 | 1051.4 | 1.02 ± 0.35 |
| whyando | input-mattcl | 726.1 ± 158.3 | 153.2 | 1208.9 | 1.10 ± 0.38 |
| kcen | input-mattcl | 932.0 ± 166.0 | 311.5 | 1596.6 | 1.42 ± 0.46 |
| kcen | input-lanjian | 968.5 ± 131.2 | 486.4 | 1522.3 | 1.47 ± 0.45 |
| kcen | input-whyando | 998.2 ± 162.5 | 442.6 | 1598.2 | 1.52 ± 0.48 |
| mattcl | input-lanjian | 1058.8 ± 214.9 | 3.5 | 1737.5 | 1.61 ± 0.55 |
| mattcl | input-mattcl | 1081.4 ± 214.5 | 407.0 | 3019.1 | 1.64 ± 0.55 |
| mattcl | input-whyando | 1114.8 ± 189.1 | 612.5 | 1748.0 | 1.69 ± 0.54 |
| lanjian | input-whyando | 1376.1 ± 300.9 | 852.6 | 2656.6 | 2.09 ± 0.73 |
| lanjian | input-mattcl | 1379.0 ± 291.8 | 859.8 | 2697.0 | 2.10 ± 0.72 |
| lanjian | input-lanjian | 1388.8 ± 252.0 | 869.7 | 2432.6 | 2.11 ± 0.69 |
| mattcl-py | input-mattcl | 21174.0 ± 768.1 | 20144.3 | 24092.8 | 32.18 ± 8.81 |
| mattcl-py | input-whyando | 21247.7 ± 726.8 | 20241.1 | 24701.8 | 32.30 ± 8.83 |
| mattcl-py | input-lanjian | 21260.9 ± 790.0 | 19751.5 | 24171.3 | 32.32 ± 8.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|