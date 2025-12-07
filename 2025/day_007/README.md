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


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-whyando | 430.7 ± 186.9 | 0.0 | 1041.0 | 1.00 |
| mattcl | input-lanjian | 436.7 ± 166.4 | 0.0 | 962.6 | 1.01 ± 0.59 |
| mattcl | input-mattcl | 465.4 ± 149.1 | 0.0 | 908.5 | 1.08 ± 0.58 |
| kcen | input-whyando | 921.1 ± 127.9 | 495.2 | 1407.0 | 2.14 ± 0.97 |
| kcen | input-mattcl | 929.2 ± 142.3 | 350.0 | 1474.5 | 2.16 ± 0.99 |
| kcen | input-lanjian | 998.8 ± 192.2 | 354.4 | 1924.3 | 2.32 ± 1.10 |
| lanjian | input-whyando | 1404.2 ± 211.6 | 430.4 | 1931.4 | 3.26 ± 1.50 |
| lanjian | input-mattcl | 1406.6 ± 176.4 | 737.4 | 1713.6 | 3.27 ± 1.48 |
| lanjian | input-lanjian | 1447.5 ± 150.3 | 770.2 | 2370.9 | 3.36 ± 1.50 |
| mattcl-py | input-mattcl | 17243.2 ± 507.2 | 15999.4 | 19841.7 | 40.04 ± 17.41 |
| mattcl-py | input-lanjian | 17370.5 ± 741.1 | 16259.2 | 20927.2 | 40.33 ± 17.58 |
| mattcl-py | input-whyando | 17467.1 ± 602.2 | 16373.7 | 20501.8 | 40.56 ± 17.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|