# Day 3 benchmarks

[link to problem](https://adventofcode.com/2024/day/3)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 3)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)
- [mikofo](https://github.com/mikofo/aoc2024) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| kcen | input-kcen | 978.8 ± 279.1 | 0.0 | 1727.4 | 1.00 |
| mattcl | input-kcen | 1068.9 ± 174.3 | 499.8 | 1780.9 | 1.09 ± 0.36 |
| mattcl | input-lanjian | 1088.9 ± 197.8 | 425.8 | 1944.3 | 1.11 ± 0.38 |
| mattcl | input-mikofo | 1101.7 ± 217.3 | 316.9 | 1850.0 | 1.13 ± 0.39 |
| kcen | input-mattcl | 1140.5 ± 206.9 | 459.3 | 1773.9 | 1.17 ± 0.39 |
| mattcl | input-mattcl | 1146.2 ± 208.4 | 487.8 | 1981.5 | 1.17 ± 0.40 |
| kcen | input-lanjian | 1152.3 ± 216.1 | 413.0 | 1840.8 | 1.18 ± 0.40 |
| kcen | input-mikofo | 1160.6 ± 208.6 | 513.2 | 1862.4 | 1.19 ± 0.40 |
| lanjian | input-kcen | 1800.3 ± 360.8 | 1066.6 | 3094.1 | 1.84 ± 0.64 |
| lanjian | input-lanjian | 1853.9 ± 393.6 | 892.0 | 2938.6 | 1.89 ± 0.67 |
| lanjian | input-mattcl | 1855.7 ± 377.3 | 1162.1 | 3008.1 | 1.90 ± 0.66 |
| lanjian | input-mikofo | 1863.8 ± 370.0 | 598.8 | 2752.4 | 1.90 ± 0.66 |
| mattcl-py | input-lanjian | 16770.3 ± 596.6 | 15897.2 | 19946.7 | 17.13 ± 4.92 |
| mattcl-py | input-mikofo | 16836.1 ± 743.0 | 15639.9 | 20592.7 | 17.20 ± 4.96 |
| mattcl-py | input-kcen | 16888.8 ± 553.0 | 15583.3 | 20074.9 | 17.25 ± 4.95 |
| mattcl-py | input-mattcl | 16909.9 ± 605.6 | 15871.0 | 19513.6 | 17.28 ± 4.97 |
| mikofo | input-kcen | 19455.3 ± 592.8 | 18403.4 | 23593.0 | 19.88 ± 5.70 |
| mikofo | input-mattcl | 19490.5 ± 610.8 | 18473.9 | 22569.9 | 19.91 ± 5.71 |
| mikofo | input-lanjian | 19516.7 ± 566.8 | 18452.5 | 22578.5 | 19.94 ± 5.72 |
| mikofo | input-mikofo | 19628.8 ± 696.1 | 18341.1 | 22652.0 | 20.05 ± 5.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>165225049</pre>|<pre>108830766</pre>|
|input-lanjian|<pre>182619815</pre>|<pre>80747545</pre>|
|input-mattcl|<pre>170068701</pre>|<pre>78683433</pre>|
|input-mikofo|<pre>189527826</pre>|<pre>63013756</pre>|