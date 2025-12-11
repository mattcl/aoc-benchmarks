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
| whyando | input-whyando | 368.2 ± 156.0 | 0.0 | 816.4 | 1.00 |
| mattcl | input-whyando | 380.9 ± 175.0 | 0.0 | 1035.6 | 1.03 ± 0.65 |
| whyando | input-lanjian | 400.3 ± 159.2 | 0.0 | 1006.8 | 1.09 ± 0.63 |
| whyando | input-mattcl | 409.5 ± 169.0 | 0.0 | 978.4 | 1.11 ± 0.66 |
| mattcl | input-lanjian | 410.9 ± 174.0 | 0.0 | 885.7 | 1.12 ± 0.67 |
| mattcl | input-mattcl | 420.4 ± 171.3 | 0.0 | 1058.4 | 1.14 ± 0.67 |
| lanjian | input-mattcl | 711.8 ± 138.4 | 196.5 | 1323.3 | 1.93 ± 0.90 |
| lanjian | input-lanjian | 735.7 ± 183.9 | 258.0 | 1184.5 | 2.00 ± 0.98 |
| lanjian | input-whyando | 746.2 ± 172.7 | 78.8 | 1358.0 | 2.03 ± 0.98 |
| kcen | input-mattcl | 882.9 ± 172.3 | 274.1 | 1649.4 | 2.40 ± 1.12 |
| kcen | input-whyando | 884.8 ± 144.8 | 380.1 | 1444.8 | 2.40 ± 1.09 |
| kcen | input-lanjian | 945.7 ± 169.7 | 340.3 | 1570.5 | 2.57 ± 1.18 |
| mattcl-py | input-whyando | 17529.7 ± 624.0 | 16269.1 | 20674.5 | 47.61 ± 20.24 |
| mattcl-py | input-mattcl | 17597.3 ± 704.4 | 16529.9 | 21094.0 | 47.79 ± 20.34 |
| mattcl-py | input-lanjian | 17646.2 ± 788.7 | 16123.0 | 20822.5 | 47.92 ± 20.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|