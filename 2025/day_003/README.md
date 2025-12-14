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
| mattcl | input-mattcl | 551.4 ± 175.2 | 0.0 | 1050.9 | 1.00 |
| mattcl | input-whyando | 560.6 ± 178.7 | 0.0 | 1059.1 | 1.02 ± 0.46 |
| whyando | input-mattcl | 575.0 ± 191.3 | 0.0 | 1188.4 | 1.04 ± 0.48 |
| mattcl | input-lanjian | 582.2 ± 130.5 | 31.4 | 917.8 | 1.06 ± 0.41 |
| whyando | input-lanjian | 584.5 ± 155.6 | 0.0 | 1145.6 | 1.06 ± 0.44 |
| whyando | input-whyando | 585.3 ± 137.0 | 0.0 | 1038.0 | 1.06 ± 0.42 |
| kcen | input-mattcl | 933.4 ± 156.8 | 46.8 | 1495.6 | 1.69 ± 0.61 |
| kcen | input-whyando | 963.2 ± 128.9 | 418.6 | 1501.9 | 1.75 ± 0.60 |
| kcen | input-lanjian | 963.5 ± 203.4 | 14.9 | 1931.1 | 1.75 ± 0.67 |
| lanjian | input-lanjian | 4063.8 ± 332.5 | 3318.0 | 4936.3 | 7.37 ± 2.42 |
| lanjian | input-mattcl | 4090.6 ± 295.0 | 3437.1 | 4883.3 | 7.42 ± 2.42 |
| lanjian | input-whyando | 4146.7 ± 306.7 | 3211.9 | 5014.7 | 7.52 ± 2.45 |
| mattcl-py | input-lanjian | 21267.0 ± 726.8 | 20156.2 | 24659.6 | 38.57 ± 12.32 |
| mattcl-py | input-mattcl | 21278.3 ± 788.1 | 20233.2 | 24710.6 | 38.59 ± 12.34 |
| mattcl-py | input-whyando | 21406.7 ± 637.6 | 20493.2 | 24373.3 | 38.82 ± 12.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|