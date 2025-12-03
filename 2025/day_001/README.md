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
| whyando | input-whyando | 705.9 ± 149.3 | 0.0 | 1127.6 | 1.00 |
| whyando | input-lanjian | 707.2 ± 144.2 | 11.3 | 1127.4 | 1.00 ± 0.29 |
| whyando | input-mattcl | 726.3 ± 141.5 | 261.9 | 1283.2 | 1.03 ± 0.30 |
| kcen | input-lanjian | 793.0 ± 159.0 | 340.7 | 1289.2 | 1.12 ± 0.33 |
| kcen | input-mattcl | 816.5 ± 155.6 | 357.6 | 1433.7 | 1.16 ± 0.33 |
| kcen | input-whyando | 821.3 ± 130.6 | 416.5 | 1294.1 | 1.16 ± 0.31 |
| mattcl | input-lanjian | 992.0 ± 154.9 | 233.6 | 1655.8 | 1.41 ± 0.37 |
| mattcl | input-mattcl | 995.9 ± 182.5 | 498.0 | 1665.8 | 1.41 ± 0.39 |
| mattcl | input-whyando | 1056.0 ± 179.1 | 445.0 | 1913.3 | 1.50 ± 0.41 |
| lanjian | input-lanjian | 1296.6 ± 238.6 | 198.6 | 2459.0 | 1.84 ± 0.51 |
| lanjian | input-mattcl | 1304.8 ± 232.2 | 528.9 | 2382.9 | 1.85 ± 0.51 |
| lanjian | input-whyando | 1347.4 ± 170.9 | 624.8 | 2054.2 | 1.91 ± 0.47 |
| mattcl-py | input-whyando | 18062.8 ± 677.0 | 17143.6 | 21226.4 | 25.59 ± 5.50 |
| mattcl-py | input-mattcl | 18117.9 ± 660.9 | 16734.1 | 21506.6 | 25.67 ± 5.51 |
| mattcl-py | input-lanjian | 18124.9 ± 652.2 | 16999.9 | 21704.2 | 25.68 ± 5.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|