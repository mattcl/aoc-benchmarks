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
| whyando | input-mattcl | 511.7 ± 155.6 | 0.0 | 952.0 | 1.00 |
| mattcl | input-mattcl | 513.9 ± 180.1 | 0.0 | 1025.7 | 1.00 ± 0.47 |
| mattcl | input-lanjian | 523.8 ± 175.0 | 0.0 | 1123.1 | 1.02 ± 0.46 |
| whyando | input-whyando | 533.5 ± 152.2 | 26.7 | 1059.2 | 1.04 ± 0.43 |
| whyando | input-lanjian | 569.0 ± 142.1 | 0.0 | 1052.2 | 1.11 ± 0.44 |
| mattcl | input-whyando | 573.0 ± 116.7 | 103.8 | 1049.4 | 1.12 ± 0.41 |
| kcen | input-mattcl | 834.8 ± 156.5 | 0.0 | 1302.9 | 1.63 ± 0.58 |
| kcen | input-lanjian | 853.1 ± 146.4 | 60.3 | 1327.4 | 1.67 ± 0.58 |
| kcen | input-whyando | 866.2 ± 139.5 | 301.7 | 1452.6 | 1.69 ± 0.58 |
| lanjian | input-lanjian | 881.2 ± 128.6 | 391.5 | 1379.5 | 1.72 ± 0.58 |
| lanjian | input-mattcl | 888.2 ± 149.7 | 449.0 | 1675.9 | 1.74 ± 0.60 |
| lanjian | input-whyando | 925.4 ± 185.6 | 308.9 | 2466.7 | 1.81 ± 0.66 |
| mattcl-py | input-mattcl | 18216.3 ± 574.9 | 17156.3 | 21508.3 | 35.60 ± 10.88 |
| mattcl-py | input-whyando | 18293.8 ± 674.3 | 17169.5 | 21136.4 | 35.75 ± 10.95 |
| mattcl-py | input-lanjian | 18302.4 ± 664.4 | 17054.3 | 21973.3 | 35.77 ± 10.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|