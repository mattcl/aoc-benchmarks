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
| whyando | input-lanjian | 735.4 ± 143.6 | 0.0 | 1215.4 | 1.00 |
| whyando | input-whyando | 737.4 ± 135.5 | 0.0 | 1055.0 | 1.00 ± 0.27 |
| whyando | input-mattcl | 739.2 ± 165.8 | 12.7 | 1214.2 | 1.01 ± 0.30 |
| kcen | input-whyando | 831.5 ± 157.0 | 241.1 | 1361.6 | 1.13 ± 0.31 |
| kcen | input-mattcl | 851.9 ± 158.3 | 245.1 | 1371.1 | 1.16 ± 0.31 |
| kcen | input-lanjian | 855.1 ± 166.7 | 0.0 | 1392.3 | 1.16 ± 0.32 |
| mattcl | input-whyando | 1025.2 ± 235.1 | 23.2 | 1936.2 | 1.39 ± 0.42 |
| mattcl | input-lanjian | 1035.2 ± 136.3 | 442.4 | 1716.0 | 1.41 ± 0.33 |
| mattcl | input-mattcl | 1090.7 ± 220.2 | 396.9 | 2029.7 | 1.48 ± 0.42 |
| lanjian | input-mattcl | 1315.5 ± 231.2 | 529.2 | 1885.1 | 1.79 ± 0.47 |
| lanjian | input-lanjian | 1345.3 ± 216.4 | 484.1 | 2087.4 | 1.83 ± 0.46 |
| lanjian | input-whyando | 1348.2 ± 229.9 | 395.2 | 2563.5 | 1.83 ± 0.48 |
| mattcl-py | input-mattcl | 18291.7 ± 611.9 | 17288.5 | 21674.6 | 24.87 ± 4.93 |
| mattcl-py | input-lanjian | 18396.9 ± 812.5 | 17247.6 | 21946.0 | 25.02 ± 5.01 |
| mattcl-py | input-whyando | 18489.7 ± 643.4 | 17344.8 | 21440.5 | 25.14 ± 4.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|