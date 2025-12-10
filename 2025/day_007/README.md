# Day 7 benchmarks

[link to problem](https://adventofcode.com/2025/day/7)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 7)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 358.5 ± 182.7 | 0.0 | 921.4 | 1.00 |
| whyando | input-lanjian | 383.5 ± 182.6 | 0.0 | 1029.1 | 1.07 ± 0.75 |
| mattcl | input-lanjian | 406.3 ± 174.7 | 0.0 | 932.0 | 1.13 ± 0.76 |
| whyando | input-whyando | 414.3 ± 171.9 | 0.0 | 1045.4 | 1.16 ± 0.76 |
| mattcl | input-whyando | 417.2 ± 153.2 | 0.0 | 983.3 | 1.16 ± 0.73 |
| mattcl | input-mattcl | 426.7 ± 160.3 | 0.0 | 1025.9 | 1.19 ± 0.75 |
| lanjian | input-whyando | 692.1 ± 148.3 | 105.2 | 1085.4 | 1.93 ± 1.07 |
| lanjian | input-mattcl | 703.4 ± 147.4 | 0.0 | 1108.0 | 1.96 ± 1.08 |
| lanjian | input-lanjian | 713.7 ± 186.8 | 147.3 | 1403.5 | 1.99 ± 1.14 |
| kcen | input-whyando | 866.4 ± 161.5 | 0.0 | 1401.2 | 2.42 ± 1.31 |
| kcen | input-lanjian | 879.6 ± 171.3 | 0.0 | 1424.3 | 2.45 ± 1.34 |
| kcen | input-mattcl | 932.6 ± 154.7 | 489.6 | 1555.8 | 2.60 ± 1.39 |
| mattcl-py | input-mattcl | 17410.4 ± 605.4 | 16468.3 | 20362.1 | 48.56 ± 24.80 |
| mattcl-py | input-lanjian | 17442.7 ± 613.0 | 16491.1 | 20258.8 | 48.65 ± 24.85 |
| mattcl-py | input-whyando | 17554.8 ± 587.1 | 16463.8 | 20290.7 | 48.97 ± 25.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|