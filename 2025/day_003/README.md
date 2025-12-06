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
| kcen | input-lanjian | 631.2 ± 408.3 | 72.4 | 1551.0 | 1.00 |
| mattcl | input-lanjian | 1070.1 ± 378.5 | 156.2 | 2054.4 | 1.70 ± 1.25 |
| kcen | input-whyando | 1112.1 ± 160.3 | 603.2 | 1676.4 | 1.76 ± 1.17 |
| kcen | input-mattcl | 1116.4 ± 160.0 | 565.8 | 1864.1 | 1.77 ± 1.17 |
| whyando | input-mattcl | 1194.1 ± 164.6 | 247.8 | 1875.1 | 1.89 ± 1.25 |
| whyando | input-whyando | 1218.2 ± 169.1 | 540.0 | 1851.6 | 1.93 ± 1.28 |
| mattcl | input-whyando | 1234.4 ± 174.1 | 708.9 | 1939.2 | 1.96 ± 1.29 |
| whyando | input-lanjian | 1243.5 ± 212.4 | 332.4 | 2038.5 | 1.97 ± 1.32 |
| mattcl | input-mattcl | 1284.3 ± 222.4 | 600.5 | 2082.6 | 2.03 ± 1.36 |
| lanjian | input-lanjian | 1537.6 ± 349.0 | 1025.7 | 4771.3 | 2.44 ± 1.67 |
| lanjian | input-mattcl | 1537.7 ± 221.1 | 993.0 | 2664.4 | 2.44 ± 1.61 |
| lanjian | input-whyando | 1560.9 ± 278.6 | 1030.6 | 2671.5 | 2.47 ± 1.66 |
| mattcl-py | input-lanjian | 21284.4 ± 660.8 | 20017.4 | 24470.2 | 33.72 ± 21.83 |
| mattcl-py | input-mattcl | 21372.6 ± 713.4 | 20034.6 | 24936.6 | 33.86 ± 21.93 |
| mattcl-py | input-whyando | 21442.6 ± 600.7 | 20595.4 | 24589.1 | 33.97 ± 21.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|