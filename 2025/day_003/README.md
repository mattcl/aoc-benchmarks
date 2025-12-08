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
| whyando | input-whyando | 552.1 ± 197.1 | 0.0 | 1060.1 | 1.00 |
| whyando | input-mattcl | 552.6 ± 166.3 | 0.0 | 940.5 | 1.00 ± 0.47 |
| whyando | input-lanjian | 554.9 ± 161.4 | 0.0 | 1084.3 | 1.01 ± 0.46 |
| mattcl | input-mattcl | 781.0 ± 151.5 | 0.0 | 1266.2 | 1.41 ± 0.57 |
| mattcl | input-lanjian | 815.8 ± 149.4 | 288.1 | 1543.1 | 1.48 ± 0.59 |
| mattcl | input-whyando | 822.1 ± 170.2 | 44.4 | 1623.4 | 1.49 ± 0.61 |
| kcen | input-mattcl | 940.6 ± 170.4 | 0.0 | 1439.9 | 1.70 ± 0.68 |
| kcen | input-lanjian | 945.5 ± 122.0 | 446.8 | 1487.1 | 1.71 ± 0.65 |
| kcen | input-whyando | 961.0 ± 173.1 | 236.7 | 1608.0 | 1.74 ± 0.70 |
| lanjian | input-mattcl | 8624.5 ± 66.7 | 8458.4 | 8961.4 | 15.62 ± 5.58 |
| lanjian | input-lanjian | 8625.9 ± 73.4 | 8453.0 | 8848.4 | 15.62 ± 5.58 |
| lanjian | input-whyando | 8653.5 ± 221.6 | 8457.9 | 10921.0 | 15.67 ± 5.61 |
| mattcl-py | input-mattcl | 21191.3 ± 608.9 | 19998.7 | 24388.8 | 38.38 ± 13.74 |
| mattcl-py | input-lanjian | 21280.6 ± 594.4 | 20268.5 | 24447.2 | 38.54 ± 13.80 |
| mattcl-py | input-whyando | 21414.4 ± 616.7 | 20400.7 | 24437.9 | 38.79 ± 13.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|