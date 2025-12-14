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
| whyando | input-mattcl | 473.1 ± 182.1 | 0.0 | 991.0 | 1.00 |
| mattcl | input-whyando | 530.6 ± 179.0 | 0.0 | 1094.2 | 1.12 ± 0.57 |
| mattcl | input-mattcl | 532.9 ± 202.4 | 0.0 | 1720.9 | 1.13 ± 0.61 |
| whyando | input-whyando | 539.2 ± 167.0 | 0.0 | 1069.9 | 1.14 ± 0.56 |
| mattcl | input-lanjian | 543.2 ± 168.4 | 0.0 | 1072.8 | 1.15 ± 0.57 |
| whyando | input-lanjian | 550.8 ± 156.7 | 0.0 | 1017.3 | 1.16 ± 0.56 |
| kcen | input-whyando | 842.0 ± 165.4 | 0.0 | 1490.0 | 1.78 ± 0.77 |
| kcen | input-mattcl | 847.3 ± 151.2 | 0.0 | 1298.2 | 1.79 ± 0.76 |
| lanjian | input-whyando | 855.1 ± 171.5 | 0.0 | 1327.2 | 1.81 ± 0.78 |
| lanjian | input-mattcl | 893.6 ± 151.6 | 420.4 | 1446.3 | 1.89 ± 0.79 |
| lanjian | input-lanjian | 925.8 ± 170.7 | 364.8 | 1521.9 | 1.96 ± 0.84 |
| kcen | input-lanjian | 954.8 ± 205.0 | 467.9 | 2476.3 | 2.02 ± 0.89 |
| mattcl-py | input-lanjian | 18271.1 ± 519.0 | 17342.8 | 20804.4 | 38.62 ± 14.91 |
| mattcl-py | input-whyando | 18310.1 ± 710.4 | 17000.2 | 21903.0 | 38.70 ± 14.97 |
| mattcl-py | input-mattcl | 18355.5 ± 713.3 | 16955.1 | 21523.8 | 38.80 ± 15.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|