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
| whyando | input-lanjian | 527.8 ± 170.0 | 0.0 | 993.4 | 1.00 |
| whyando | input-whyando | 537.4 ± 173.3 | 0.0 | 1124.4 | 1.02 ± 0.46 |
| mattcl | input-whyando | 538.7 ± 178.7 | 0.0 | 985.4 | 1.02 ± 0.47 |
| mattcl | input-mattcl | 542.5 ± 192.8 | 0.0 | 1186.6 | 1.03 ± 0.49 |
| whyando | input-mattcl | 544.5 ± 183.0 | 0.0 | 1189.7 | 1.03 ± 0.48 |
| mattcl | input-lanjian | 545.3 ± 159.8 | 0.0 | 1015.6 | 1.03 ± 0.45 |
| kcen | input-whyando | 868.6 ± 196.0 | 0.0 | 1403.6 | 1.65 ± 0.65 |
| kcen | input-mattcl | 924.9 ± 163.7 | 422.8 | 1465.6 | 1.75 ± 0.64 |
| kcen | input-lanjian | 937.0 ± 152.3 | 392.3 | 1423.9 | 1.78 ± 0.64 |
| lanjian | input-mattcl | 8599.1 ± 64.9 | 8386.3 | 8782.6 | 16.29 ± 5.25 |
| lanjian | input-whyando | 8599.7 ± 65.4 | 8412.6 | 8799.8 | 16.29 ± 5.25 |
| lanjian | input-lanjian | 8600.1 ± 86.1 | 8418.5 | 8910.9 | 16.29 ± 5.25 |
| mattcl-py | input-mattcl | 21219.1 ± 625.7 | 19636.1 | 23713.7 | 40.20 ± 13.00 |
| mattcl-py | input-lanjian | 21219.4 ± 714.2 | 20040.7 | 24273.9 | 40.20 ± 13.01 |
| mattcl-py | input-whyando | 21426.6 ± 743.7 | 20409.9 | 24800.6 | 40.59 ± 13.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|